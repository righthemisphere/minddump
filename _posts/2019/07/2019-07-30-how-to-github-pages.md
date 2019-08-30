---
layout: post
title:  "How to Github Pages"
date:   2019-07-30 17:46:00 -0700
categories: [meta]
tags: [readme howto]
---

Hey, Laurie!
======

This is Github Pages. I promise it's really easy to get really fast when using Github Pages, but it's going to have a slight learning curve. I promise, it's not that big...

**Buckle your seatbelt.**

This is not quite as, um, convenient as using something like Wordpress is, but for what I believe is a _small_ sacrifice of convenience you get a lot more power. The power that you get is that Github Pages uses _markdown_, which is a markup language designed to be mostly human-readable **without needing to render fonts, colors, styles, just content** and at the same time be compiled to HTML. Think of it as "HTML Light".

This means that you can do almost anything you want to do in HTML in a document that's way more readable than HTML is. (In fact, raw, direct HTML is valid Markdown, so you can do literally anything HTML can do...)

For instance, I want to give you a link to a website that describes Markdown, so I'm going to [give you a link](https://www.markdownguide.org/basic-syntax/) to that website. If you view [the raw file](https://raw.githubusercontent.com/righthemisphere/minddump/master/_posts/2019/07/2019-07-30-how-to-github-pages.md) here, you can see what the link looks like both when you're authoring it and when it's previewed in HTML on [your website](http://righthemisphere.github.io/minddump/meta/2019/07/31/how-to-github-pages.html/)

I expect we'll spend more time chatting about how to set up the site (it's very convention-driven, but you'll learn for sure) but for now, if you just create new files under the `_posts` directory using the Github editor, and committing them, we can capture that content and publish it later.


### Front matter

So I see in [this post](https://github.com/righthemisphere/minddump/blob/master/_posts/2019/07/2019-08-01-Nadi-Bay-Declaration) that you marked "Tag with Climate Anxiety". I'm going to describe how Github Pages "Front Matter" works.

There is a section at the beginning of *this* post that starts and ends with 3 dashes. This is the "Front Matter" and it won't be rendered in your final post; it contains the metadata of the post, like when it was *actually* dated. Since we don't have you totally set up on Github Pages it's hard to see what's going where, but it will be relevant at some point.

For now, take a look at this post on your Github Pages site to see some bare-bones comparisons:

* Compare what's in the front matter [in your repository](https://github.com/righthemisphere/minddump/blob/master/_posts/2019/07/2019-07-30-how-to-github-pages.md)
* See how it renders on your [Github Pages site](https://righthemisphere.github.io/minddump/meta/2019/07/31/how-to-github-pages.html).
* Notice the URL mapping between your repository, the Github Pages site, and the information in the front matter. (Specifically, the Github Pages url contains "meta" and "readme" and your repository does not.)
  * (Note: I have a suspicion why the date this is published is shown as on the 31st, but the front matter says the 30th - I think it's a time zone offset thing that's misconfigured. I'll fix that at some point, but the date in the front matter *should* be reflected in Github Pages).

[The front matter is specific to Github Pages, yes this link is really long so you are tempted to click on it and read the official documentation](https://jekyllrb.com/docs/front-matter/) so it does require learning fresh when you're getting started, but it's not that complicated, so hopefully it'll not take too much effort. Basically, it takes the form of `key: value` where the key can be interpreted by the software that builds your website (like `tags` or `categories`) and the value is what you want to set for that particular bit of data. Tags and categories are very similar: for now, **use tags** until we reorganize later.

Other than that, for now, keep typing up your thoughts in plain text (or look at this file in your repository and on Github Pages on your own time to learn some Markdown) and we'll circle back later.
