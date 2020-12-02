---
layout: post
title: "Strategy change"
date: "2020-12-01 19:05:59 -0500"
---

I've been experimenting with a new content strategy for [@chswx](https://chswx.com) that I've been fairly happy with so far (with caveats).

In short, I am beginning to originate most content from the WordPress blog that houses chswx.com. This isn't just blog posts, either, as I am beginning to do more microblogging directly on-site. Using [micro.blog](https://micro.blog), I am able to crosspost to Twitter and other networks if so desired. I accomplish this by using WordPress's Post Formats feature to set these posts as asides, pinging micro.blog on post, and then having the site retrieve my asides feed, upon which it will post to Twitter (I am considering adding Mastodon support as well). A cursory search of Micro.blog suggests that [@chswx](https://micro.blog/chswx) is the first account of its kind there, totally dedicated to local weather. (Please correct me if I am mistaken!)

Micro.blog handles Tweeting quite well, but I've run into a couple issues that I need to iron out in my workflow:

- Posting animated GIFs to WordPress is a pain, as it will often run a resize operation on your GIF that strips the animation. This is not great in my situation, as I'm often posting radar or satellite loops. (You don't realize just how seamless Twitter's animated GIF support is until you try to use something else.) When I do get the GIF to post, sometimes it is resized by other means that degrade image quality substantially when it heads over to Twitter. If I use the micro.blog native app, it will also strip the animation. This is definitely something I will need to work out with time. (And I haven't gotten to the obvious performance implications of posting GIFs directly, vs. Twitter and other sites' conversion to video formats which can be hardware accelerated and are often much smaller than said GIFs.)
- I have always been a proponent of newlines in tweets. Unfortunately, micro.blog will strip additional newlines beyond the first one when tweeting. :( Maybe I can bug someone to get that fixed...
- It'd be cool if micro.blog recognized featured images for long blog posts. I made a custom feed to get around this (with a nifty hack that uses Jetpack's Publicize text for the excerpt), but this is probably something that should be natively supported.

This is a first step. Overall, the goal is to continue to originate more and more rich content on the site, and rely less on Twitter as a primary source. Owning your own content is pretty rad and more people really should look into it. Note that I am not abandoning social media wholesale: Twitter is an essential part of the conversation, and still an important vector especially for receiving severe weather reports.

Now, the trick will be sustaining this! Stay tuned...
