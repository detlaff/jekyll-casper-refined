---
layout: post
title: "Privacy and Security"
date: 2014-01-17 18:13
description: "I believe everyone who is even remotely interested in world events is familiar with the name Edward Snowden. The former NSA contractor proved what many people, including me, already knew, but that's beside the point. What's important is that your data is not your own anymore on The Internet, given that you use mainstream software and web applications — still, this is not the worst problem. The biggest issue is that the majority of people don't give a shit about their own privacy."
image: privacy.jpg
---

I believe everyone who is even remotely interested in world events is familiar with the name **Edward Snowden**. The former NSA contractor proved what many people, including me, already knew, but that's beside the point. What's important is that *your data* is not your own anymore on The Internet, given that you use mainstream software and web applications — still, this is not the worst problem. The biggest issue is that the majority of people don't give a shit about their own privacy.

### Technical Illiteracy

Let me start off by saying how terrible the majority of *educated population* is with computers and all associated peripherals. Because they are, **seriously**. Even people who call themselves programmers or web designers sometimes display signs of utter stupidity, but fortunately, those are rare cases.

Marc Scott's [blog post](http://coding2learn.org/blog/2013/07/29/kids-cant-use-computers/) (fantastic, well worth a read) inspired me to write this, and as he did, I will present some examples of my own. Fasten your seatbelts. It might feel a bit like recycling what Marc have written, but his article struck me as his experiences are identical to mine.

<img src="/images/privacy.jpg">

A few years back I was called to fix my friend's printer, which was apparently not working. She claimed she checked it inside out, that it was working the day before and now suddenly Windows can't "see" it. Well, after ten seconds, I plugged the power cord and the printer came back to life. Can she use a computer?

Another time I was summoned to fix a computer of a guy who downloaded a whole bunch of viruses by clicking flashy banners and installing every single program in a way I like to call *Spam Next & Let Me Play*, without reading absolutely anything. His browser, Firefox (at least he got that right), had 5 toolbars below the adress bar, taking up like one third of the screen. He didn't know he can remove them. When I told him this is so messy, it'd be best to format and reinstall the OS, his eyes went bigger than ever. Can he use a computer?

Once, a friend was about to sell his computer (as broken) because it wouldn't boot up. As the price was really low for hardware of this power, I wanted to take a look at it. The BIOS was loading fine, then derp, error, my friend looking at me like I'm about to perform a magic trick. He admitted that he wanted to play around with Linux, so he installed Ubuntu, had his fun for a few weeks and then decided to get rid of it. He did it by booting into Windows and formatting every single Ext4 partition he found using disk partitioning software, pretty much like you'd remove a folder. Including /boot, effectively removing GRUB bootloader responsible for OS launch instead of Windows' MBR. I asked for a Windows 7 installation disk, reinstalled MBR, done. He decided not to sell it. Can he use a computer?

> So can I use Facebook now?

There is truly a stereotype that younger people are inherently good with technology. Frankly, this couldn't be further from the truth. Too many people, especially parents, think that spending hours upon hours on Facebook and other social media will make their kids better with computers. No, it won't. Still, most teenagers and adults alike spend their time on PCs doing exactly that.

In fact, I'm willing to bet a lot that the majority of PC users would be content with having only a browser, file explorer and a communicator of some sort installed. Moreover, it absolutely **must** *just work*. I know people are busy, I am busy too, but sometimes it is necessary to research stuff when you want it to work properly. This was especially true in the past — you wanted something fixed, you had to fix it yourself most likely. Nowadays, however, we have phones and computers which maintain themselves, requiring no setup whatsoever. Windows 7&8, Mac OS X's and most GNU/Linux distros now run out of the box with pretty much everything preconfigured. Same thing with iOS and Android — yes, you can jailbreak, you can root, but how many people do that? Finally, **of course** it is convenient. Modern computer experience is designed that way, so that anyone, a child or an elder can use it without an issue. 

> What happened? :(

It's all cool and nice until it fucks up. Then, *talented computer users* panic, clicking the same *X* button in the corner ten times, seemingly unaware that it doesn't work. They try the old **Ctrl+Alt+Del** and sometimes it works. When it doesn't, they hold the power button until it halts, hoping for the best. If even this is fruitless, they call me.

Honestly, almost everyone thinks of serious tech people stereotypically. We are all neck-bearded nerds, servants of the Machine God, sexually inactive, unattractive and socially retarded. No matter how we **actually** look and behave, this image will stick for at least a while whenever you meet a new person. Funny thing is, every single *sexually attractive, social star* needs tech support, every time something isn't working, be it a camera, a tablet, a Wi-Fi connection or an Office Suite. There's no need to even start talking about formatting, web design or advanced computing, that's a far away land. *There be dragons*.

I have to blaim illiteracy first on this modern, convenient, *all-works-out-of-the-box* approach (kids don't have to learn how it works, since it seemingly just works), and second on the lack of creativity. **Most issues** people have, and I do mean like 90%, are easily fixed in less than thirty seconds. All you need is half a brain and an idea on how to fix it, or even on how it *should* work and what can I do to make it work again — find an obstacle between A and B. People lack that, unfortunately, missing obvious power switches, not connected cables, firewalls or hidden icons. People don't read warning messages, they click OK as soon as possible. They click next a thousand times, oblivious to the software they install **in addition** to the one they want.

> All of the above, I believe, is the main reason folks are so naive when dealing with their data online. As they do not understand tech, they do not understand the connection between their real lives and the stuff they put online.

### Main Offenders

Let's go back to the privacy issue, then. Almost everyone I know uses and has accounts on Facebook, Twitter, Pinterest, YouTube, Picasa, Gmail (and other various Google services), Last.fm, GoodReads, Dropbox, what have you. Sadly, I am no different, but I consequently try to remove them from my life (and with great success thus far). People are all seemingly unaware of the dangers social networks bring to the table, or they just simply don't care much. There is a very popular opinion on this, shared by most who are aware of surveillance, including intelligent, educated individuals. I am frankly shocked because of how often it pops up everywhere this topic is discussed.

> Honest folks should have nothing to fear, those who want to keeps things secret are most likely terrorists hiding something nasty.

How utterly preposterous. I mean, are people seriously so brainwashed by the corporations, that they are willing to give away everything that was once a private matter? Maybe I don't want to share my daily routine with the world. Same goes to my location, my favorite films, a CV, private documents (often stored in a cloud nowadays) or photos. Don't even get me started on people who upload pictures of their newborn children to Facebook. *Look, I know you're a happy parent now, but those will stay there **forever** now, as the file for your kid is being built (as it is for you).*

Social networks collect as much information on every single person as they possibly can. Facebook is a good example, because it is one of the worst in this department and people are willingly giving their data away. So, this platform knows all of your music/film/sport/etc preferences, your job history, your real name and location, the dates of your graduation/marriage/etc and a ton of other stuff. 

Some people wonder why I hate Facebook chat (and absolutely everyone seems to use it these days). Well, all of your messages are stored in the cloud and while you can remove your copy, the other person may not. Now let's say someone hacks their way to yours or that person's profile (or s/he didn't logout, or had a password like 1234) — your private conversations are compromised. Then there's the other thing: every single word you type is automatically processed (read) in the background by a computer looking for brands, interests, most likely even things like "bomb". This primarily serves as an additional method to serve more accurate advertisements, but creeps the hell out of me. Again, the vast majority of Facebook users are oblivious to this happening.

> Note: even the "share" or "like" buttons Twitter and Facebook let people put on their sites are collecting data — even without you clicking them. It is enough for them to load and they know you were on a website. That's why I use custom (and obsolete) share buttons, not the official ones.

Finally, there's the NSA. Every big social network is based in the US of A. American law these days allows the Agency to demand private customer data from any company there, and they [did time and again with their nicely called program](https://en.wikipedia.org/wiki/PRISM_%28surveillance_program%29). Sure enough, after Snowden revelations, Google, Facebook, Microsoft and every other mentioned company are fighting tooth and nail to disconnect themselves from Prism. While I am really hopeful that this will spark some change in the regulations, I do not trust any of them.

### Possible Solutions

Given that one is willing to change some habits, there are a lot of ways to protect privacy online. I'm going to present what I can, in no particular order, and this list isn't definitive by all means.

**Operating System**. This matters little, to be honest. Linux machines are inherently very secure, but let's be honest, a casual user won't like them. Both Mac OS X and newer (and by that I mean 7-8) Windows boxes are fine too.

**Browser**. Use Firefox, as it is the only open-source big-name browser available. This guarantees security and any hole is patched up very fast. There's also a selection of very good quality, privacy-enhancing extensions. At minimum, I suggest:

* [Adblock Plus](https://addons.mozilla.org/en-US/firefox/addon/adblock-plus/) - it blocks ads (the fact so many of my friends aren't using it even today boggles the mind)
* [HTTPS Everywhere](https://www.eff.org/https-everywhere) - it forces the HTTPS versions of sites wherever possible
* [DuckDuckGo](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-ssl/) - a search engine, very solid, modern and privacy oriented (seriously, stop using Google, stop saying "let's Google it")
* [Disconnect.me](https://disconnect.me/search) - if you have to use Google for some stupid reason, at least install this - whenever you search for anything using a search engine of your choice, this free VPN will enable you to do that securely and without tracking

Also, take a look at [Privacy Fix](https://privacyfix.com/start/install). It's going to help you adjust Facebook and Google privacy settings in an understandable way.

**Web services and social networks**. Remove your accounts. Not all of them, but I'm deadly serious.

* [Facebook](https://www.facebook.com/) - I have an account, used only to keep in touch with friends I'd otherwise lose because of the distance. I am thinking of taking it down anyway.
* [Google+](https://plus.google.com/) - same as the above, really. I do not have an account though, never will.
* [Twitter](https://twitter.com/) - this is the smallest culprit of the bunch. There are no "likes" on Twitter, no actual profile and all is very public by nature. Keep it or leave it.
* E-mail - preferably, keep it on your own server and if you can't, choose a hosting with a smaller company. For the love of all that is holy, **do not** use Gmail, unless you like all of your mail read in a way described in Facebook example.
* [Dropbox](https://www.dropbox.com/) - and all of similar services. This one has to go. A lot of people hoard important stuff there, but this data is not yours anymore. Use [BitTorrent Sync](http://www.bittorrent.com/intl/pl/sync) without hosting or [SparkleShare](http://sparkleshare.org/) if you've got a dedicated backup server.
* [Picasa](http://picasa.google.com/), [Flickr](https://secure.flickr.com/) - again, the pictures are not yours alone. Fortunately, there are a lot of alternatives, namely self-hosted [Koken](http://koken.me/) for bigger websites/galleries or [img.bi](https://img.bi/) for quick, encrypted single image upload.
* [YouTube](https://www.youtube.com/) - that's a pickle. There's simply no other service like that. Use a fake Google account made solely for that purpose.
* [Google Analytics](http://www.google.com/analytics/) - the one for my web designer friends. Yes, it is free, but so is [Piwik](http://piwik.org/) which doesn't steal your visitors data.

There's a whole list of alternative, spy-free software [here](http://prism-break.org/en/), and a guide on how to protect your chosen browser [here](http://fixtracking.com/). So please, protect your privacy and care about it, because **it is** important to you, your children and your friends. Don't give it away for free.