---
title: Building This Blog Site
date: 2022-12-01
---

I finally had some time to build a personal site and blog "platform" to both better manage content for personal projects and pontification re. technology and other topics, but also upgrade to current or future-proof methods.  

Following are the criteria I wanted to accomplish:

## Manage Content in a Git Repo

I am a dev(sec)ops nerd, so it's a no-brainer that the solution had to manage content using a modern VMS using [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow).  Naturally I chose my favorite platform [GitHub](https://github.com).  It offers some other benefits which I will detail in the following sections.

Also, the solution needed to manage content and code privately but allow me to invite others to critique posts, contribute, etc. if need be.

## Use Modern Static Site Generator

The solution had to allow posting content using Markdown and auto-render it to responsive HTML5 using a modern static generator (SSG).  Being a child of the early 90's, I've had my share of coding HTML, CSS, JavaScript, and I didn't want to unnecessarily carry that luggage anymore (who does these days?).  Regardless of its final destination or form 99% of the "content" I generate is with Markdown, , so it had to be Markdown-friendly without adding overhead.

Although I had used [Jekyll](https://jekyllrb.com/) before, I wanted to move to [Hugo](https://gohugo.io) partly just to test drive it to see if it was feasible for low-scale personal sites with blog-style content.

## Publish to GitHub Pages Using a Custom Domain

The solution had to be able publish to [GitHub Pages](https://pages.github.com) and use a custom domain.  By default, GitHub Pages renders using Jekyll, but with Actions you can "intercept" that using Hugo instead.

## Precise, Cost-Effective CICD

Last but certainly not the least, it had to offer precise and cost-effective CICD.  I've been doing dev(sec)ops for many years (as well as Scaled Agile Framework), and I love [GitHub Actions](https://docs.github.com/en/actions).  I think it's not a fully-capable, ready-for-prime-time CICD platform, and it's available for no cost as long as you stay within parameters.

Using GitHub's [relatively new direct to Pages feature](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow), it takes just seconds to generate and deploy (publish) this site.  And it doesn't use Jekyll at all!

## Conclusion

So far, this platform has been a joy to set up and use.  I might post details re. my experience if anything relevant comes up, but most of the methods used so far are fully supported fairly well-documented.  Nothing "funky" or kludgy has been used so far!
