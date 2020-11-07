---
layout: post
title: The Simplest Way to Build a Github Page with Jekyll
date: 2020-05-13
author: Dongyuan Wu
tags: [website, Jekyll, learning]
comments: true
---

To be honest, I am only a beginner and have just built this personal homepage. I would like to record what I have done and maybe it can provide references for someone also interested in developing a Github page with Jekyll.

I just copy-pasted the following sentences from Wikipedia: 

> Jekyll is a simple, blog-aware, static site generator for personal, project, or organization sites. Written in Ruby by Tom Preston-Werner, GitHub's co-founder, it is distributed under the open-source MIT license.

However, we can build our GitHub page most easily without learning Ruby or even installing Jekyll. Let's start!

**Step1: Find a Jekyll theme you like**

You can find Jekyll themes by searching `Jekyll` on Github or using some websites, like <a href="http://jekyllthemes.org/" target="_blank">this one</a>. It provides lots of free themes. 

After choosing your preferred theme, find its Github repository and fork it to your account. Then go to `Settings`, scroll down to `Github Pages`, select source as `master branch`. Notice: It is better to rename this repository as `USERNAME.github.io` on the top of the `Settings` page. But renaming is not a necessary part. If you do so, the address of your website will directly be `USERNAME.github.io`. Otherwise, the address will be `USERNAME.github.io/REPOSITORY_NAME`.

**Step2: Modify website information**

In your Github repository, there is a file named `_config.yml`. Click on it and then edit it (a pencil icon on the right-top of the content). Usually, there are some comment lines, so just replace the content (eg: *title*, *description*) with your information according to those instructions.

Similarly, if the theme contains other parts, such as *about*, you can find a file named `about` and just edit it. If there are some images you would like to change, then just replace those files with what you like, as long as the *file names* keep the same as before.

**Step3: New Post**

All your posts for the blog will be saved in the `_posts` fold. You just need to upload a new `.md` file, whose name is something like:
```
2020-01-01-an-example.md
2020-05-13-more-examples.md
```
And this `.md` file needs to contain a header like:

```
---
layout: post
title: your post title
date: 2020-05-13
Author: your name
tags: [tag1, tag2]
comments: true
---
```

Then a new post can be found on your website!