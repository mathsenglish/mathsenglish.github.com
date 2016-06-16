# About

MDwiki is a CMS/Wiki **completely built in HTML5/Javascript and runs 100% on the client**. No special software installation or server side processing is required. Just upload the `mdwiki.html` shipped with MDwiki into the same directory as your markdown files and you are good to go!

Note: The website you are currently viewing is realized with MDwiki and hosted on [GitHub pages](http://pages.github.com/). [http://mdwiki.info](http://mdwiki.info) redirects here.

[gimmick:twitterfollow](timodoerr)

## Features

*   Built completely in Javascript/HTML5 and **does not require any local or remote installations**
*   Uses [Markdown](http://daringfireball.net/projects/markdown/) as its input markup language
*   Build on top of [jQuery](http://www.jquery.org) and [Bootstrap3](http://www.getbootstrap.com) to work cross-browser, with responsive layout
*   Extends Markdown with special [_Gimmicks_](gimmicks.md) that add rich client functions, like syntax highlighting via [hightlight.js](https://highlightjs.org/), [GitHub Gists](https://gist.github.com/), or [Google Maps](http://maps.google.com/) for geo data
*   Themeable through Bootstrap compatibility, supports all themes from [bootswatch](http://www.bootswatch.com)

## Requirements

*   Webspace (or a web server that can serve static files)
*   Any modern Webbrowser
*   [mdwiki.html](download.md) file

## How does it work?

Just drop the `mdwiki.html` available from [the download page](download.md) along with your markdown files on a webspace somewhere. You can pass any url (relative to the `mdwiki.html` file) to mdwiki after the hashbang `#!`:

    <span class=<span class="hljs-string">"hljs-label"</span>><span class="hljs-keyword">http</span>:</span<span class="hljs-comment">>//www.example.com/mdwiki.html<span class="hljs-preprocessor">#!myfile.md</span></span>
    `</pre>

    If you <span class="hljs-built_in">rename</span> <span class="hljs-operator">the</span> `mdwiki.html` <span class="hljs-keyword">into</span> `index.html`, you can omit <span class="hljs-operator">the</span> filename <span class="hljs-command"><span class="hljs-keyword">on</span> <span class="hljs-title">most</span> <span class="hljs-title">webservers</span>:</span>

    <pre>`<span class=<span class="hljs-string">"hljs-label"</span>><span class="hljs-keyword">http</span>:</span<span class="hljs-comment">>//www.example.com/<span class="hljs-preprocessor">#!myfile.md</span></span>
    `</pre>

    MDwiki will <span class="hljs-built_in">load</span> <span class="hljs-operator">a</span> <span class="hljs-built_in">file</span> called `index.md` <span class="hljs-built_in">from</span> <span class="hljs-operator">the</span> same <span class="hljs-built_in">directory</span> <span class="hljs-keyword">as</span> <span class="hljs-operator">the</span> index.html <span class="hljs-keyword">by</span> default, so <span class="hljs-keyword">if</span> you use <span class="hljs-operator">an</span> `index.md` <span class="hljs-built_in">file</span> <span class="hljs-keyword">as</span> entry point, all you have <span class="hljs-built_in">to</span> <span class="hljs-built_in">do</span> is enter your domain name:

    <pre>`<span class=<span class="hljs-string">"hljs-string"</span>><span class="hljs-keyword">http</span>:</span><span class=<span class="hljs-string">"hljs-comment"</span><span class="hljs-comment">>//example.com/</span></span>

Note: There are lots more features over regular Markdown, check out the [quickstart tutorial](quickstart.md).

* * *

## Credits / Technologies

MDwiki would not exist if it weren't for those great pieces of software:

*   [marked](https://github.com/chjj/marked)
*   [jQuery](http://www.jquery.org)
*   [Bootstrap](http://www.getbootstrap.com)
*   [Bootswatch](http://www.bootswatch.com)
*   [colorbox](http://www.jacklmoore.com/colorbox/)
*   [highlightjs](https://highlightjs.org/)

MDwiki is created by Timo Dörr. Follow me to get updates on MDwiki! [Follow @timodoerr](http://www.twitter.com/timodoerr).

Cute kitten images provided by the great [placekitten.com](http://www.placekitten.com/) service.

## License

MDwiki is licensed under [GNU GPLv3 with additional terms applied](https://github.com/Dynalon/mdwiki/blob/master/LICENSE.txt).