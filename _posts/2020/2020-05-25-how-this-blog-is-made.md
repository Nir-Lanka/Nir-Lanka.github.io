---
published: true
layout: post
title: How this blog is made
tags: jekyll javascript css github
---
This blog is made with Jekyll, JS and CSS from grounds up, and hosted on GitHub.

<!--more-->

I have been redesigning this blog for quite some time, and other blogs before this. I started with Jekyll on GitHub Pages, tried out Medium for a couple of years, and used Dev.to (which I still use).

I love designing minimalist, yet beautiful and feature-full websites. But I was never able to gain the "design zen" I expected with any of the designs. I spent a long time not wanting to update my blogs because it was too much work, and I didn't like how my writing looked on them.

So I took a different approach with this redesign. Instead of designing an intricate layout and appearance, or going with someone else's design, I went with the bare minimum, as well as hoping to get easier accessibility to publishing ideas:

## New.css, SCSS, theme stored in sessionStorage

I used [New.css](https://newcss.net/){:target="_blank"} in its default colors and appearance (mostly). New.css is a CSS file that aims to make a simple CSS-less website look appealing by having better looking defaults than browser defaults. This concept and result is very appealing to me.

The only major design change I did on top of it was to add some overrding CSS code to change the `<a></a>` underlines. I used `background-image` styling to get the current link underlining effect that I'm very satisfied with.

New.css also comes with an automatic dark mode through CSS variables, if the browser says it's preferred. I added a little bit of JavaScript to enable flipping it on user demand, and store it in `sessionStorage`.

## Jekyll, GitHub Pages, Prose.io

I used my computer do finish the design and test. But I didn't want to have to mess around with terminal and desktop code editors all the time. So I went in the path of minimal resistance on GitHub, and also use [Prose.io](http://prose.io/){:target="_blank"} as the editor. 

I love Prose.io. It's a free service that lets you access your GitHub repos and edit them like you'd do in any other CMS editor like Wordpress or even Dev.to.

## Syntax highlighting

I add code snippets with the 3-backtick notation with the language id label added next to the starting backticks.

I have added a Monokai CSS theme for the default syntax highlighter in Jekyll by simply including a `monokai.css` which just overrides syntax highlighting styles.

That's about it! If there's any questions, fire me a message on my [Gitter](https://gitter.im/nirlanka/community){:target="_blank"} "chatroom". :D
