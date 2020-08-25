---
title: "Setting up a Hugo Blog"
date: 2020-08-09T22:43:17+01:00
draft: false
toc: false
comments: false
images:
  - "https://images.unsplash.com/photo-1489533119213-66a5cd877091"
tags:
  - "Hugo"
  - "Go"

---

{{< figure src="https://images.unsplash.com/photo-1489533119213-66a5cd877091" alt="coffee-mug-on-table" caption="Photo by [Danielle MacInnes](https://unsplash.com/@dsmacinnes?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/start?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)">}}

:wave: Welcome to my blog. I've always been very passionate about software and tech in general, and I'm often inclined to rant for hours on end to anyone who will listen. Unfortunately, this is not an optimal way of educating the masses. 

After much deliberation, I decided that a personal website and blog would best enable me to spread my propaganda as freely as possible. It would be a place where I could carefully document my rant pieces and share them with the world. Now all that was left was to implement it.

# Why Hugo?

As an experienced web developer, I had a myriad of options to pick from when trying to decide on how to implement my personal website. To make the selection process more manageable, I decided to outline the requirements of my website:

1. It should be a static site, so no dynamic content needed
2. It should be easy to add, remove and alter blog posts
3. It should be quick to set up and require minimal maintenance

It became glaring after some research that what I needed was a static site generator. While searching through [StaticGen](https://www.staticgen.com/) for a static site generator to use, I stumbled upon [Hugo](). What instantly stuck out was that Hugo is implemented in Go (which is a language I personally love :heart:) claimed to be much faster than the more mainstream alternatives.

{{< figure src="https://forestry.io/uploads/2018/01/hugo-vs-jekyll-totals.jpg" alt="hugo-vs-jekyll" caption="Hugo vs Jekyll by [Forestry](https://forestry.io/blog/hugo-vs-jekyll-benchmark/#a-clear-winner)">}}

# Final Thoughts

Hugo has excellent documentation and [this]() guide will get you set up in under five minutes. Also adding new pages is as simple as creating new markdown files in the `/content` directory, which was easy, convenient and exactly what I was looking for. Finally, deployed the site on Netlify which automatically rebuilds and publishes the site on every push to the main branch.

Overall I am very pleased with the setup and look forward to writing more blog posts soon! 