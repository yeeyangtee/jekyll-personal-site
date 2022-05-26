---
title: How this site was born 👶
date: 2022-05-26 08:39:54 +8:00
modified: 2022-05-26 11:28:45 +8:00
tags: [blog, linode, jekyll, github]
description: 
---

## General Aims
- Everything is free (or has a free alternative)
- Full control of content
- Static and fast sites


## Site Creation
The website was made using Jekyll.
It's an open source static sites generator (SSG) and themed with [klisé](https://github.com/piharpi/klise).

<hr>

## Hosting
There are free options for hosting:
- [Github Pages](https://pages.github.com/)
- Cloud services
- 
<hr>

## Docker
- No dependencies on your local computer, just need text editor.
- don't want to install anything on my own machines, full remote.
- Bundle up prerequisites and software such as jekyll, ruby, etc


## Installation
- launch cloud instance (linode, AWS-EC2, GCP)
- install docker on cloud instance (link to script)
- Run following commands to pull jekyll image
- Clone jekyll template directory, push to your own git repo
- 

```bash
$ bundle install jekyll # installing jekyll in your machine
$ jekyll new my-site && cd my-site # create new jekyll project
$ jekyll s # run jekyll server
```

#### Adding remote repository

Before we adding remote repository, you must have [github](https://github.com/new) repository, if already have repository, just add github remote address to your local folder, with the following commands

```bash
$ git init # initializing project folder
$ git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git # change UPPERCASE with your own!
$ git add -A && git commit -m "Initialize" && git push -u origin master # push code to github
```

Now check your github repository, make sure the files is uploaded correctly.
