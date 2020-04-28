---
layout: default
title: How I have set up this blog
published: 2020-04-28T19:00:11.778Z
date: 2020-04-28T19:00:11.789Z
categories: web
tags:
  - web
  - serverless
comments: false
---
Hello fellow readers and welcome to my blog! I have not found a better way to start this blog  than a post that explains how I have set up this. So, I will try to explain the arquitecture I have used, why I have elected to use this and what other alternatives do we have when it comes to having a site on the Internet.

<!--more-->

## Introduction

I have decided to follow a modern serverless arquitecture using a static site generator, but why?.. Well, why not?

Static site generators have been with us for more than \[REVISAR ESTO]. They are simple, they have no database, no updates, no mantenances... just your content!

The most important thing when you set up a blog (at least a personal blog) is your content, thats where the effor should go. I wanted to look for the easiest way of starting to publish my content to the word as quick and easy as posible. 

Nevertheless, this option is not for everybody. I consider that at least you need to have a little bit of knowing of what you are doing or at least you should have a good friend that set up all for you, because when it is already setyp, as you will see, it is really easy to mantain and to update.

## Jekyll

There are a ton of static site generators this days. Almost every javascript framework or lenguaje have it own generator. Yo don't believe me? Take a look at [this ](https://www.staticgen.com/)and tell me. We have options for JS React framework ([Gatsby](https://www.gatsbyjs.org/), [Next.js](https://nextjs.org/)), pure Javascript ([Docusaurus](https://docusaurus.io/)), Go lenguaje ([Hugo](https://gohugo.io/)), Ruby ([Jekyll](https://jekyllrb.com/)), Python ([Sphinx](https://www.sphinx-doc.org/en/master/)) and much more. These are just one of the most used ones. Some are focused on generating documentation for developers, others are more for blog/web but the concept is exactly the same.

And now the question is: Why Jekyll?... And the answer another time is *Why not?*

I really don't know why but the first thing it came up to my mind when I think about static site generator is Jekyll. Perhaps because it is (I think) one of the first to came along, perhaps it is because its integration with Github Pages... But for me talking about static site generator is talking about Jekyll. 

How do they work? It is actually very simple: The user writes the content, normally, as a [Markdown ](https://en.wikipedia.org/wiki/Markdown)files, the static site generator, in this case Jekyll, take this Mardown files, and renders it to produce a complete, static HTML website ready to be deployed in your favourite hosting. Notice that this is plain HTML static files (plus css and js), so there is not interpreter, no PHP, no backend, no database, no nothing! So you just need a simple Apache that everybody gives for free nowaday that serve this files to the browser.

Jekyll, and all the others static generators, use what is known as layouts o templates. This is normally a HTML like file that has some directives that are substituted by your content. Nevertheless this is not intended to be a tutorial on how to use Jekyll, if you are looking for more information, the documentation of Jekyll is pretty good: <https://jekyllrb.com/docs/>

## Github Integration



## Netlify CMS

Jekyll is very cool but it is perhaps a little geeky (well, that is what the blog is about, right?). Yes, we do love geeky things but I wanted to have a way to make it even simpler. So I was looking more to a Wordpress like approach and I find Netlify CMS

\[CONTAR AQUI COMO VA EL TEMA DEL CDN, QUE SE ACTUALIZA "SOLO"]

## Netlify Continuous Deployment