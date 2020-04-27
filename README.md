# Emitter
## Obfuscate, pollute and muddy up your local internet surveillance system with absolutely useless data
#### [2020 © aidswidjaja on GitHub under Apache-2.0](https://github.com/aidswidjaja)
#### Version 1.0 - 27 April 2020

**How do I use this?** Leave [this page](https://aidswidjaja.github.io/emitter) open in your browser, and it will load random webpages and web images every 7 seconds through HTTPS `port 443`. Hopefully you have unlimited broadband! Also keep in mind that this website is designed to load both generic websites, search results, and streaming services to cover all potentially surveillance categories. It will distort any statistics based on categorical data a little bit more!

**How does it work?** Simple (by simple I mean quick and dirty) JavaScript code takes an array of URIs and randomly chooses one to load into an invisible `iframe`. You won't see the webpage or the images thought, as they are hidden. The page automatically reloads every 7 seconds using `meta http-equiv="refresh"`, triggering a new URI to be chosen. I was setting up virtual machines at the age of 7 btw.

**My internet search history looks the same.** This is for internet surveillance (commonly installed on school and corporate networks, but also by parents), which monitor all connections through HTTP/HTTPS. This won't pollute your local web browser's search history, and don't expect it, because it's not supposed to.

**Why did my employer/school principal/parents find me looking at Neko-Kirito?** Um, well I'm loading anime neko images... Look look look! It'll all be fine as the URLs are pretty disguised anyway, and if you **want to change the webpages before your friends find out too much about your secret anime watching habits, [make a fork of the project on GitHub!](https://github.com/aidswidjaja/emitter)**