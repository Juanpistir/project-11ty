---
title: Problema de usuario en GitHub
description: Un problema sobre las nuevas layouts de leventy
author: Juan Arce
date: 2021-07-13
tags: post
image: https://dp-cdn.codementor.io/images/projects/cm-intro-alpaca.svg
imageAlt: logo de DevProjects
---
**I'm trying to set up the new layouts directory that was released in v0.8.0 but am hitting an issue. Here's how I've set things up**:

I added layouts to my .eleventy.js file, following the new docs
I moved my layouts out of /_includes/layouts/ and into /_layouts/
I changed all references to layouts in front-matter and directory config files to layout: layouts/base to layout: base
There was no reference to number 3 in the layout docs so I assume this is correct and the layout key just carries over from how it used to be.

Anyway, with that setup, I'm I'm getting this when I run eleventy to build the site:

Problem writing Eleventy templates: (full stack in DEBUG output)

> You’re trying to use a layout that does not exist: base (undefined) (Error)
> Processed 0 files in 0.14 seconds