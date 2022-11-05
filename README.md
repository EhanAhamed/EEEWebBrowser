# EEEWebBrowser

> ***E***han's ***E***xtensible ***E***lectron-based ***Web Browser***

Warning: This project is a work in progress, its created and maintained by me, Ehan, *a literal 13 year old*, and as of right now this project doesn't even exist. Nothing is finished or even started, I'll add more to it when I have the time. If you're reading this, then theres nothing to see here for now.

## The Idea

### The Context

I'm a *die-hard linux user*, open source enthusiast, tiled window manager user, and ***average vim enjoyer***.

My whole setup is fully keyboard-operated, fancy, and vim-like. I use Debain (Linux), bspwm (& sxhkd), kitty, ranger, and neovim. (And I use my own colorscheme, [purpurite](https://purpurite.ehan.dev))

However, theres one thing I haven't yet *riced* to full *vim-ness* and *fancy-ness*: my web browser.

### The Problem

The problem is Chrome is difficult to *rice* or *modify*, yet it's the most common and most supported web browser. Although Chromium is open source and its source code can be edited and recompiled, doing such is very difficult.

There are a variety of vim-like, open source, browsers. However, many websites and webapps do not support them since they use less popular chromium derratives such as QtWebKit and others.

### The Solution

What if, instead of making millions of different web browsers based on different frameworks that all have different styles, there was one really extensible and configurable web browser based on chromium. Almost like a rice-able chrome.

Thats exactly what EEEWebBrowser aims to do.

I want a web browser that looks like vim, someone else wants a web browser that ___, you want a web browser that ___. The idea is that you can simply configure EEEWebBrowser to behave and look however you want!

## The Plan

### ElectronJS

As I said before, chromium is one of the most widley supported browser frameworks. However, chrome and chromium browser are not very configurable. The solution: ***Electron***.

Electron often gets hate from *midwits* because Electron consumes ram in order to render web pages. (***How else would it render web pages???***) Although it is true that Electron should't be used in some types of apps, Electron's entire purpose is to be a custom web browser that runs HTML JS and CSS for web-based desktop apps. What else is a desktop app, and renders HTML JS and CSS? ***A WEB BROWSER!!!***

Since Electron is based on chromium, 90% of whats possible in chrome is possible in Electron. Electron is also open source, and is proven to be production-ready, for apps such as Discord, Visual Studio Code, Slack, Figma, and millions more use Electron in their desktop apps.

Another convinence of Electron is that if one were to make a web browser in it, the UI of the web browser itself would also be in HTML CSS and JS, like the opened websites. Since HTML and CSS are really really really easy, it would be simple to modify the UI of the browser, and my making a web browser dedicated to customizability, it can be made even simplier. 
