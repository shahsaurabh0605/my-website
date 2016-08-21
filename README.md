# Jekyll Theme

A Simple, Bootstrap Based Theme. Especially for bloggers and developers who like to show their projects on website and love to write. There are also some magical features to discover. 

## [Live Demo](http://shahsaurabh.me)

Open issues if you find bugs or even have trouble installing jekyll or dependencies. :D

> Strongly suggest to fork and change project name to create your GitHub Pages instead of downloading it directly. Because in the future, I will develop many funny modules like 'footprint' to show your world wide trip. Could be easier to merge new features in the future.

## Notable Features

* Compatible with Jekyll 3.x and GitHub Pages
* Based on Bootstrap
* [Github Module](http://shahsaurabh.me/open-source) to show your popular projects in a single page and on sidebar automatically. (Datas are retreived by github metadata instead of by api calls, so no delay) 
* [Post Module](http://shahsaurabh.me/blog) to show all your posts with timeline

Features in future:
* A Footprint module to show all your travel around the world
* Feature to share. (Facebook, twitter, evernote and so on)
* (Not sure) A embeded todo list. (Not sure) to travel, to complete, to do for your parents, etc. To do in life!
* Creative ideas to discuss with you :P

## Install and setup

Before using it, you may need [Bower](http://bower.io/) and [Bundler](http://bundler.io/) on your local to install dependencies.

1. Fork code and clone
2. Run `bower install` to install all dependencies in [bower.json](https://github.com/DONGChuan/DONGChuan.github.io/blob/master/bower.json)
3. Run `bundle install` to install all dependencies in [Gemfile](https://github.com/DONGChuan/DONGChuan.github.io/blob/master/Gemfile)
4. Update `_config.yml` with your own settings.
5. Add posts in `/_posts`
6. Commit to your own Username.github.io repository.
7. Then come back to star this theme!

> When install dependencies by bundler or gem, you may have some errors depending on your environment.

> For the moment, when you test on your local, you need to keep internet connection to fetch information from github.

## How to use

#### Create a new post

Create a `.md` file inside `_posts` folder.

Name the file according to the standard jekyll format.

```
2016-01-19-i-love-yummy.md
```

Write the Front Matter and content in the file.

```
---
layout: post
title: Post title
category: Category
tags: [tag1, tag2]
---
```

When writing post, please always follow this format:

```
Description about the post, blablabla

## Title A

### Title A-1

### Title A-2

## Title B

### Title B-1

```

So, Title A, A-1, A-2, Title B, B-1 will be detected and created as a directory


#### [Github Module](http://shahsaurabh.me/open-source)

This module will get automatically all your repository information from github. But to test on your local, you must keep internet connection. 
In the future, it will also show the repositories you contributed a lot and the ones of your organization.

#### [Customize About Page](http://shahsaurabh.me/about)

Feel free to customize about.me page to show yourself. You only need to modify [about.md](https://github.com/shahsaurabh0605/my-website/blob/master/about.md) and [about.html](https://github.com/shahsaurabh0605/my-website/blob/master/includes/about.html)

## ToDo

- [ ] List posts by a specified tag
- [ ] New module FootPrint to show your world around trips
- [ ] Show projects from your orgnization on github. (Siderbar, in open-source page)
- [ ] To fix bug - could only test on local with internet connected.
