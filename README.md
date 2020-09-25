# Roy Athletics

This is a platform where we share our workouts. Browse through [here](https://royathletics.com).

## Features
- Bootstrap card layout
- Pre-built pages using jekyll
- SEO
- Google Analytics

## Coming soon
- Pagination
- Search

## Add/Edit Workouts

All metcons are under `_posts`. The filenames follow the convention `YYYY-MM-DD-name-of-the-post.md` and the contents follow this format
~~~
---
layout: post
title: ""
categories: 
---
Metcon
~~~

## Develop

royathletics was build with [Jekyll](https://jekyllrb.com) and [Bootstrap](https://getbootstrap.com)

Install the dependencies with [Bundler](https://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~
