---
layout: post
title: "Hosting My Email With My Own Domain"
date: 2013-12-08 18:26
description: "Yesterday I wrote an article about blogging. Since I can host my Jekyll-generated website on GitHub (fast, reliable and secure) for free, the only problem I had left was to find an email solution that works with my domain, ideally for free."
---

Yesterday I [wrote an article](http://kubalojewski.pl/articles/blogging-experience) about blogging. Since I can host my Jekyll-generated website on [GitHub](http://github.com/) (fast, reliable and secure) for free, the only problem I had left was to find an email solution that works with my domain, ideally for free. I have to cash out for the domain itself, this is a step you cannot skip, unless you want a *.tk* or something crappy like that. One can argue that using a free domain ruins credibility, which might be true, I don't really care. Either way, I got my name as a domain with my country's *.pl*, so I'm satisfied. Registration was dirt-cheap, renewal will be 5x as much but worth it I guess.

It's not that I can't pay for all this, up to this point I was doing that, but this is more for my own enjoyment that anything else. Furthermore, it is to prove a point that you don't have to spend a dime to have a ton of amazing, usually paid-for features for yourself if your requirements are not through the roof.

To the matter at hand then &mdash; how I managed to solve my email issue. Well, surprisingly enough, with **Microsoft**'s help, hence some people will be disappointed that I didn't try harder. I have tried to use PaaS, [OpenShift](http://openshift.com/) in particular, to host [Mailgun](http://www.mailgun.com/) mail server in conjunction with [Roundcube](http://www.roundcube.net/). Change of plans, for a number of reasons. First, let me quote Mailgun's documentation.

> Large, virtual cloud environments are generally not the best environments for email for a few reasons:

> * The IP address should be static so that your domain(s) and IP address(es) build a reputation together. Also, some more strict recipients ESPs may require whitelisting your IP address. Unfortunately, these should be IPv4.
> * The IP address and surrounding IP addresses should have a good reputation. This is rarely the case at large cloud environments due to their ease of use and lax monitoring (which is inviting to spammers).
> * Mail Transfer Agents should ideally be on real (non-virtual) machines, optimized for I/O.

As you can see, these guys have a different viewpoint [than OpenShift folk](https://www.openshift.com/blogs/free-paas-email-server-with-roundcube). Moreover, it didn't occur to me earlier that one can simply look for existing mail server operators which provide a way to use your own domain &mdash; a feature, admittedly, quite rare. Yes, I know, I could host my own server in the corner of my bedroom (for this website as well), but this is not an option at the moment.

I'd appreciate it if my old and faithful paid email provider ([Onet.pl](http://onet.pl)) allowed custom domains, sadly, it is not possible &mdash; my account there ends with *@onet.eu*. With that in mind, I tried [Zoho Mail](https://www.zoho.com/mail/) out, but was put off by slow server response in addition to crazy POP behaviour &mdash; whenever I sent an email using the web interface, that message was automatically copied and pushed into my POP (Thunderbird) Inbox, effectively creating senseless duplicates. I might understand the purpose behind this, but at least make it optional &mdash; a lot of people were complaining about this *functionality*, yet you cannot switch it off.

A few minutes of searching later, I found out that Microsoft's fairly new [Outlook](http://www.microsoft.com/en-us/outlook-com/default.aspx) service offers custom domains, no problem whatsoever. It has a nice, modern web interface (*...I will never use*), virtually unlimited storage and pretty much everything you'd want out of an email provider.

<figure>
	<img src="/images/outlook.jpg">
</figure>

Configuration was simple and straightforward. First of all, make sure you already have a Microsoft account - it can be just another email. After that's done, visit [Windows Live Admin Center](https://domains.live.com/Signup/SignupDomain.aspx) and register your domain, verify ownership and set up MX and SPF records in your DNS control panel. I think no tutorial is necessary as this process it really simple and painless, furthermore differs from registrar to registrar. Note that it might take a while for the new DNS to update across the web, depending on your TTL settings. Finally, add an account to this domain and there you go. Not really a hacker's way to do things, but it works and I'm willing to trust Microsoft much more than, say, Google. Outlook takes care of spam, SSL and speed for me in exchange for hosting my stuff, I can live with that. I've been really busy lately too, with work and university, so... Free email hosting, custom domain, unlimited storage. **Nice**.
