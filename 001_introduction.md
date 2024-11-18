---
layout: default
title: Introduction
number: 1
---
# Introduction

This is where you introduce your project to your audience. You should summarize briefly the topic you are working on. (250-350 words)

The following is sample text to show the capabilities of presenting text with various formatting (such as bold), different languages, adding footnotes, and images.[^1]

{% raw %} {% assign media = site.media_metadata | where_exp: "item", "item.name == 'Intro_Train'" %} {% include media.html pages=media %} {% endraw %}


Hello world, welcome to the greatest website of all time
[^1]: First example footnote. View other pages to see sample methods of working with Markdown.
[^2]: I copied this text from this [website](https://www.lipsum.com/feed/html) 
