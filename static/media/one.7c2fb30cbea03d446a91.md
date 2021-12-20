---
Title : This is the tile a new title
Abstract: This is a desciption of what this post is about asd 
Date  : 29/03/1977
---


### Paragraphs are separated by a blank line.

After several releases of the internal application I’ve been building at work, it became apparent that the average user of our app would benefit from some sort of “What’s New?” page where they could read about new features and bug fixes as the app continues to evolve. Instead of hardcoding an ever lengthening static page of posts, I thought the simplest solution would be to make a folder of markdown files and a component that renders the contents of each. If I want to write up a new release, I can just drop in a new markdown file and see it appear live!

This turned out to not be as simple as hoped. There are some examples floating around the web on how to import a single .md file, but not an entire directory. Luckily, this is where the Webpack docs came in handy. More on that later.

![This is an image](./logo.svg)