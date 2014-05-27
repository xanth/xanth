# Welcome to Jr!

A static, static content generator that moves the "generator" part to the browser.
This site is pure text files with a single Javascript included on each page that renders
the theme and assets as needed.

Each page is written in markdown with a single `<script>` tag that includes Jr.js. Once you have created your pages then simply upload the system to your website and enjoy.

## [Visit the Demo](http://xeoncross.github.io/jr)

## Getting Started

1. [Download](http://github.com/Xeoncross/Jr) `Jr`
2. Create an `[article-name].html` file
3. Paste the following code at the bottom of the page:  
	<code>&lt;script src=&quot;jr.js&quot;&gt;&lt;/script&gt;</code>  
4. `git commit` the new article or (sad face) SFTP it up to your web host

...and you're done! Rinse and repeat.

## Degrading gracefully in the absence of JavaScript

If you want the MarkDown content to appear as human-readable MarkDown text in browsers without JavaScript (instead of as an undelimited blob), add a line like this at the top of your documents:

\[enable JavaScript to render MarkDown\]: \<pre\>

This is a MarkDown comment that will not be rendered, but HTML renderers will see the \<pre\> tag and act accordingly.

MIT License with ♡ from [David Pennington](http://davidpennington.me)
