---
layout: post
title: "My Way to the Perfect Blogging Experience"
date: 2013-12-07 13:57
logo: /assets/images/logo.png
---

Since I started hosting my own website myself I have changed it so many times I lost count. This domain was home to [Wordpress](http://wordpress.org/), [Anchor](http://anchorcms.com/), [Ghost](http://ghost.org/), static HTML, [Koken](http://koken.me/) and some less known software &mdash; all in effort to provide: 

- **me** &mdash; the best blogging experience possible, in technical and visual terms as well as in the way posts are written and published
- **you** &mdash; the cleanest, most readable website I could possibly have without **any kind** of advertisements or clickbait articles written only with SEO in mind (which I hate with passion)

Simple, right? Well, for my perfectionist self not so much. I always strive for the best possible results in this, which is both good and bad. Good, because I am constantly improving the *end product* as it were, the visual and technical quality of my website. Bad, since a lot of people might have been put off by my constant changes conducted on a live production server. This, hopefully, **changes now**. 

This is because I have finally found something meeting all conditions as required by me. Incredibly fast, transparent, simple, hacker-friendly and secure. I present you [**Jekyll**](http://jekyllrb.com/).


<img src="/images/jekyll.jpg">


> Jekyll is a simple, blog aware, static site generator. It takes a template directory (representing the raw form of a website), runs it through Textile or Markdown and Liquid converters, and spits out a complete, static website suitable for serving with Apache or your favorite web server.

As a true <s>hacker</s> nerd I had to try it out and learn it &mdash; and it is **glorious**. There are a lot of blogging platforms out there, but WordPress, Anchor or even the newly released Ghost based on Node.JS &mdash; praised for its speed &mdash; can't load articles as fast as static sites do. It is a fact and you can compare load times using your favourite tool to your heart's content, results are conclusive. Moreover, by using a static site you immensely increase security, since there is no admin panel or MySQL database to hack. You do not have to worry about any updates and can, literally, put Jekyll-generated sites pretty much anywhere with minimal configuration. The only downsides I can see is that it doesn't fit certain scenarios, more elaborate projects, but if [Obama campaign could've been using Jekyll](http://kylerush.net/blog/meet-the-obama-campaigns-250-million-fundraising-platform/), it is safe to say that it's possible to make it suit your needs as you can modify and scale it all you want.

The other reason I am in love with Jekyll is that you can host your sites on [GitHub](https://github.com/) **for free** &mdash; custom domain name and all. This makes your blog's code visible to pretty much anyone by virtue of public nature of GitHub service. One can opt for private repositories, but that's 7 dollars a month and since your personal site is going to be public anyway, why not share the code? Oh snap, someone will steal your amazing theme you designed yourself &mdash; tough shit. You can host your website yourself then, not a problem. Speaking of the devil, programmers are much more willing to share their stuff than *designers* (who know fewer languages), and why, I will never know. I know some cool people &mdash; including the [man who designed previous iteration of this website](http://coletownsend.com/), but most designers are elitist pricks charging 49,99 for another utter shit of a recycled WordPress theme. Sigh.

> The great pleasure in life is doing what people say you cannot do.
> <br> &mdash; Walter Bagehot 

I am skipping Jekyll website creation process here since you are smart and can figure it out yourself. However, we're going to talk about articles &mdash; from writing to publishing. The current trend on the Internet is to write in [Markdown](http://daringfireball.net/projects/markdown/) and unsurprisingly, you do that with Jekyll. One can also use [Textile](http://textile.sitemonks.com/), whatever floats your boat, really. I use the former &mdash; it's more popular, I found and learned it first, so there. Each post must start with the so called [YAML](http://yaml.org/) *front-matter* to be processed by Jekyll. It must take the form of valid YAML set between triple-dashed lines and you can see an example taken from this very post below.

{% highlight yaml linenos %}
---
layout: post
title: "My Way to the Perfect Blogging Experience"
date: 2013-12-07 13:57
---
{% endhighlight %}

Below that you write in regular Markdown and HTML &mdash; it's clean, transparent and beautiful. The file itself should be named in *YEAR-MONTH-DAY-title.MARKUP* format, in case of this post &mdash; *2013-12-07-blogging-experience.md*. Publishing is equally easy, all you need is **git** and basic knowledge required to interact with your repository. Given that your site is already built and live on GitHub, push your new article to the **posts** folder. [GitHub Pages](http://pages.github.com/) are powered by Jekyll behind the scenes, so all you need to do is push changes, they will do the rest automagically. **Easy**.

Now I can write my stuff offline using any editor [I like at the moment](http://code52.org/DownmarkerWPF/), I don't have to pay hosting fees, care about security or speed and the domain itself is the only thing left to worry about. Still, there is the issue of my e-mail &mdash; a choice between paid and good box with a different domain or deployment of my own mail server **@kubalojewski.pl** (after my current hosting plan expires). I might try [OpenShift](http://openshift.com/) for the second option, I think mail could work on PaaS.
