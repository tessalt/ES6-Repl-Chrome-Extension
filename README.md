## ES6 REPL Chrome Extension

### What is it?
It's a Chrome DevTools extension ([available here](https://chrome.google.com/webstore/detail/es6-repl/alploljligeomonipppgaahpkenfnfkn)) that allows you to execute ES6/ESNext/ES2015 code in the context of the page you're viewing, as though it were the standard DevTools console.

[Also available for Opera](https://addons.opera.com/en/extensions/details/es6-repl/?display=en)

### How do I use it?
Once you familiarize yourself with some of the concepts and features of ES6, [install](https://chrome.google.com/webstore/detail/es6-repl/alploljligeomonipppgaahpkenfnfkn) the extension. You'll then notice the `ES6 REPL` tab inside DevTools (⌘-⌥-i on a Mac, ctrl-⇧-i on a PC). You can toggle console visibility with `esc`, and code can be executed either by clicking the _Run it_ button, or using ⌘-↩ on a Mac, ctrl-↩ on a PC.

### How does it work?
It uses one of two engines to transpile ES6 to good-old-fashioned ES5: Google's [Traceur](https://github.com/google/traceur-compiler) and [6to5](https://github.com/6to5/6to5/). Select which one you want to use from the Settings panel. If there's a feature you want to use that isn't working, check the [compatibility table](http://kangax.github.io/compat-table/es6/) under those 2 columns to see if it's been implemented yet. 

### Buy why?
Both [Traceur](https://google.github.io/traceur-compiler/demo/repl.html#) and [6to5](https://6to5.org/repl/) already have their own REPLs. Why make a Chrome extension? For me it was just the convenience of being able to read a blog about a new feature or syntax and try it right there while I'm reading the article. Pop open the DevTools on the side of the page and give'r.

![](https://s3.amazonaws.com/f.cl.ly/items/2v3n38193y2L372c3o3a/Image%202015-02-08%20at%2011.36.26%20AM.png)

=========================

Traceur is released under an [Apache 2.0 license](https://github.com/google/traceur-compiler/blob/master/LICENSE) and 6to5 is released under [MIT](https://github.com/6to5/6to5/blob/master/LICENSE). They belong to their respective owners. 
Everything else here is [MIT](https://github.com/richgilbank/ES6-Repl-Chrome-Extension/blob/master/LICENSE.md).
