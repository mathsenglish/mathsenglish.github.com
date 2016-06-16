# Mou

![Mou icon](http://25.io/mou/Mou_128.png)

GitHub supports emoji! :+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat: 

## Overview

**Mou**, the missing Markdown editor for _web developers_.

### Syntax

#### Strong and Emphasize

**strong** or **strong** ( Cmd + B )

_emphasize_ or _emphasize_ ( Cmd + I )

**Sometimes I want a lot of text to be bold.
Like, seriously, a _LOT_ of text**

#### Blockquotes

> Right angle brackets &gt; are used for block quotes.

#### Links and Email

An email [example@example.com](mailto:example@example.com) link.

Simple inline link [http://chenluois.com](http://chenluois.com), another inline link [Smaller](http://25.io/smaller/), one more inline link with title [Resize](http://resizesafari.com "a Safari extension").

A [reference style](http://25.io/mou/ "Markdown editor on Mac OS X") link. Input id, then anywhere in the doc, define the link with corresponding id:

Titles ( or called tool tips ) in the links are optional.

#### Images

An inline image ![Smaller icon](http://25.io/smaller/favicon.ico "Title here"), title is optional.

A ![Resize icon](http://resizesafari.com/favicon.ico "Title") reference style image.

#### Inline code and Block code

Inline code are surround by `backtick` key. To create a block code:

    Indent <span <span class="hljs-keyword">class</span>=<span class="hljs-string">"hljs-keyword"</span>>each</span> <span <span class="hljs-keyword">class</span>=<span class="hljs-string">"hljs-built_in"</span>>line</span> <span <span class="hljs-keyword">class</span>=<span class="hljs-string">"hljs-keyword"</span>>by</span> <span <span class="hljs-keyword">class</span>=<span class="hljs-string">"hljs-keyword"</span>>at</span> least <span <span class="hljs-keyword">class</span>=<span class="hljs-string">"hljs-number"</span>><span class="hljs-number">1</span></span> <span <span class="hljs-keyword">class</span>=<span class="hljs-string">"hljs-constant"</span>>tab</span>, <span <span class="hljs-keyword">class</span>=<span class="hljs-string">"hljs-operator"</span>>or</span> <span <span class="hljs-keyword">class</span>=<span class="hljs-string">"hljs-number"</span>><span class="hljs-number">4</span></span> spaces.
    <span class="hljs-keyword">var</span> Mou = exactlyTheAppIwant; 
    `</pre>

    <span class="hljs-preprocessor">#### Ordered Lists</span>

    Ordered lists are created <span class="hljs-keyword">using</span> <span class="hljs-string">"1."</span> + Space:

1.  Ordered list item
2.  Ordered list item
3.  Ordered list item

    #### Unordered Lists

    Unordered list are created using "*" + Space:

*   Unordered list item
*   Unordered list item
*   Unordered list item

    Or using "-" + Space:

*   Unordered list item

*   Unordered list item
*   Unordered list item

    #### Hard Linebreak

    End a line with two or more spaces will create a hard linebreak, called `<br />` in HTML. ( Control + Return )
Above line ended with 2 spaces.
Hello

    #### Horizontal Rules

    Three or more asterisks or dashes:

        * * *

        * * *

        * * *

    #### Headers

    Setext-style:

    # This is H1

    ## This is H2

    atx-style:

    # This is H1

    ## This is H2

    ### This is H3

    #### This is H4

    ##### This is H5

    ###### This is H6

    ### Extra Syntax

    #### Footnotes

    Footnotes work mostly like reference-style links. A footnote is made of two things: a marker in the text that will become a superscript number; a footnote definition that will be placed in a list of footnotes at the end of the document. A footnote looks like this:

    That's some text with a footnote.[^1]

    [^1]: And that's the footnote.

    #### Strikethrough

    Wrap with 2 tilde characters:

    &lt;del&gt;Strikethrough&lt;/del&gt;

    #### Fenced Code Blocks

    Start with a line containing 3 or more backticks, and ends with the first line with the same number of backticks:

    &lt;pre&gt;`Fenced code blocks are like Stardard Markdown’s regular code
blocks, except &lt;span class="hljs-keyword"&gt;that&lt;/span&gt; they’re &lt;span class="hljs-keyword"&gt;not&lt;/span&gt; indented &lt;span class="hljs-keyword"&gt;and&lt;/span&gt; instead rely &lt;span class="hljs-function_start"&gt;&lt;span class="hljs-keyword"&gt;on&lt;/span&gt;&lt;/span&gt;
a start &lt;span class="hljs-keyword"&gt;and&lt;/span&gt; &lt;span class="hljs-keyword"&gt;end&lt;/span&gt; fence lines &lt;span class="hljs-keyword"&gt;to&lt;/span&gt; delimit &lt;span class="hljs-keyword"&gt;the&lt;/span&gt; code block.

#### Tables

A simple table looks like this:

&lt;table&gt;
&lt;thead&gt;
&lt;tr&gt;
&lt;th&gt;First Header&lt;/th&gt;
&lt;th&gt;Second Header&lt;/th&gt;
&lt;th&gt;Third Header&lt;/th&gt;
&lt;/tr&gt;
&lt;/thead&gt;
&lt;tbody&gt;
&lt;tr&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;/tr&gt;
&lt;/tbody&gt;
&lt;/table&gt;

If you wish, you can add a leading and tailing pipe to each line of the table:

&lt;table&gt;
&lt;thead&gt;
&lt;tr&gt;
&lt;th&gt;First Header&lt;/th&gt;
&lt;th&gt;Second Header&lt;/th&gt;
&lt;th&gt;Third Header&lt;/th&gt;
&lt;/tr&gt;
&lt;/thead&gt;
&lt;tbody&gt;
&lt;tr&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;td&gt;Content Cell&lt;/td&gt;
&lt;/tr&gt;
&lt;/tbody&gt;
&lt;/table&gt;

Specify alignment for each column by adding colons to separator lines:

&lt;table&gt;
&lt;thead&gt;
&lt;tr&gt;
&lt;th style="text-align:left"&gt;First Header&lt;/th&gt;
&lt;th style="text-align:center"&gt;Second Header&lt;/th&gt;
&lt;th style="text-align:right"&gt;Third Header&lt;/th&gt;
&lt;/tr&gt;
&lt;/thead&gt;
&lt;tbody&gt;
&lt;tr&gt;
&lt;td style="text-align:left"&gt;Left&lt;/td&gt;
&lt;td style="text-align:center"&gt;Center&lt;/td&gt;
&lt;td style="text-align:right"&gt;Right&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;td style="text-align:left"&gt;Left&lt;/td&gt;
&lt;td style="text-align:center"&gt;Center&lt;/td&gt;
&lt;td style="text-align:right"&gt;Right&lt;/td&gt;
&lt;/tr&gt;
&lt;/tbody&gt;
&lt;/table&gt;

### Shortcuts

#### View

*   Toggle live preview: Shift + Cmd + I
*   Toggle Words Counter: Shift + Cmd + W
*   Toggle Transparent: Shift + Cmd + T
*   Toggle Floating: Shift + Cmd + F
*   Left/Right = 1/1: Cmd + 0
*   Left/Right = 3/1: Cmd + +
*   Left/Right = 1/3: Cmd + -
*   Toggle Writing orientation: Cmd + L
*   Toggle fullscreen: Control + Cmd + F

#### Actions

*   Copy HTML: Option + Cmd + C
*   Strong: Select text, Cmd + B
*   Emphasize: Select text, Cmd + I
*   Inline Code: Select text, Cmd + K
*   Strikethrough: Select text, Cmd + U
*   Link: Select text, Control + Shift + L
*   Image: Select text, Control + Shift + I
*   Select Word: Control + Option + W
*   Select Line: Shift + Cmd + L
*   Select All: Cmd + A
*   Deselect All: Cmd + D
*   Convert to Uppercase: Select text, Control + U
*   Convert to Lowercase: Select text, Control + Shift + U
*   Convert to Titlecase: Select text, Control + Option + U
*   Convert to List: Select lines, Control + L
*   Convert to Blockquote: Select lines, Control + Q
*   Convert to H1: Cmd + 1
*   Convert to H2: Cmd + 2
*   Convert to H3: Cmd + 3
*   Convert to H4: Cmd + 4
*   Convert to H5: Cmd + 5
*   Convert to H6: Cmd + 6
*   Convert Spaces to Tabs: Control + [
*   Convert Tabs to Spaces: Control + ]
*   Insert Current Date: Control + Shift + 1
*   Insert Current Time: Control + Shift + 2
*   Insert entity &lt;: Control + Shift + ,
*   Insert entity &gt;: Control + Shift + .
*   Insert entity &amp;: Control + Shift + 7
*   Insert entity Space: Control + Shift + Space
*   Insert Scriptogr.am Header: Control + Shift + G
*   Shift Line Left: Select lines, Cmd + [
*   Shift Line Right: Select lines, Cmd + ]
*   New Line: Cmd + Return
*   Comment: Cmd + /
*   Hard Linebreak: Control + Return

#### Edit

*   Auto complete current word: Esc
*   Find: Cmd + F
*   Close find bar: Esc

#### Post

*   Post on Scriptogr.am: Control + Shift + S
*   Post on Tumblr: Control + Shift + T

#### Export

*   Export HTML: Option + Cmd + E
*   Export PDF:  Option + Cmd + P

### And more?

Don't forget to check Preferences, lots of useful options are there.

Follow [@Mou](https://twitter.com/mou) on Twitter for the latest news.

For feedback, use the menu `Help` - `Send Feedback`