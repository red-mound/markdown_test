## Headers

```
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

```

# H1

## H2

### H3

#### H4

##### H5

###### H6

Alternatively, for H1 and H2, an underline-ish style:

# Alt-H1

## Alt-H2

## Emphasis

```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

```

Emphasis, aka italics, with *asterisks* or *underscores*.

Strong emphasis, aka bold, with **asterisks** or **underscores**.

Combined emphasis with **asterisks and underscores**.

Strikethrough uses two tildes. ~~Scratch this.~~

## Lists

```
1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses

```

1. First ordered list item
2. Another item

- Unordered sub-list.

1. Actual numbers don't matter, just that it's a number

2. Ordered sub-list

3. And another item.

   Some text that should be aligned with the above item.

- Unordered list can use asterisks


- Or minuses


- Or pluses

## Links

There are two ways to create links.

```
[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

```

[I'm an inline-style link](https://www.google.com/)

[I'm a reference-style link](https://www.mozilla.org/)

[You can use numbers for reference-style link definitions](http://slashdot.org/)

Or leave it empty and use the [link text itself](http://www.reddit.com/)

URLs and URLs in angle brackets will automatically get turned into links.[http://www.example.com](http://www.example.com/) or [http://www.example.com](http://www.example.com/) and sometimes example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

## Images

```
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

```

Here's our logo (hover to see the title text):

Inline-style: ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

Reference-style: ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

## Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers -- like Github's and *Markdown Here* -- support syntax highlighting. *Markdown Here* supports highlighting for dozens of languages (and not-really-languages, like diffs and HTTP headers); to see the complete list, and how to write the language names, see the [highlight.js demo page](http://softwaremaniacs.org/media/soft/highlight/test.html).

```
Inline `code` has `back-ticks around` it.

```

Inline `code` has `back-ticks around` it.

Blocks of code are either fenced by lines with three back-ticks `````, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.

```
​```javascript
var s = "JavaScript syntax highlighting";
alert(s);
​```
 
​```python
s = "Python syntax highlighting"
print s
​```
 
​```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
​```

```

```
var s = "JavaScript syntax highlighting";
alert(s);
```

```
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
But let's throw in a <b>tag</b>.

```

Again, to see what languages are available for highlighting, and how to write those language names, see the [highlight.js demo page](http://softwaremaniacs.org/media/soft/highlight/test.html).

## Tables

Tables aren't part of the core Markdown spec, but they are part of GFM and *Markdown Here*supports them. They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting from another application.

```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

```

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- | ------------- | ----- |
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      | $12   |
| zebra stripes | are neat      | $1    |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| *Still*  | `renders` | **nicely** |
| 1        | 2         | 3          |

## Blockquotes

```
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

```

> Blockquotes are very handy in email to emulate reply text. This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put***Markdown** into a blockquote.

## Inline HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

```

- Definition list

  Is something people use sometimes.

- Markdown in HTML

  Does *not* work **very** well. Use HTML *tags*.

## Horizontal Rule

```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores

```

Three or more...

------

Hyphens

------

Asterisks

------

Underscores

## Line Breaks

My basic recommendation for learning how line breaks work is to experiment and discover -- hit <Enter> once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend.

Here are some things to try out:

```
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

```

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also begins a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

(Technical note: *Markdown Here* uses GFM line breaks, so there's no need to use MD's two-space line breaks.)

## LINE Material Design

| elements | class  | MD sample                                | HTML sample                              | rendered sample                          |
| -------- | ------ | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| a        | color  | `[link text](# "blue-text")`             | `<a class="blue-text" href="#">link text</a>` | http://materializecss.com/color.html     |
|          | button | `[link text](# "waves-effect waves-light btn")` | `<a class="waves-effect waves-light btn" href="#">link text</a>` | <http://materializecss.com/buttons.html> |
|          | Pulse  | `[link text](# "btn btn-floating pulse")` | `<a class="btn btn-floating pulse"></a>` | <http://materializecss.com/pulse.html>   |
| img      |        | `![alt text](images/yuna.jpg"circle responsive-img")` | `<img src="images/yuna.jpg" alt="" class="circle responsive-img">` | <http://materializecss.com/media-css.html> |
| download |        | `[link text](# "downlaod")`              | `<a class="download">link text</a>`      |                                          |
| i        | icon   | `**<i class="material-icons">add</i>**버튼을 눌러 새 문서를 **추가**한다.` | `<p>**<i class="material-icons">add</i>** 버튼을 눌러 새 문서를 <strong>추가</strong>한다.</p>` | <http://materializecss.com/icons.html>   |
| span     | color  | `버튼을 눌러 새 문서를 **<span class="blue-text">추가</span>**한다.` | `<p><i class="material-icons">add</i> 버튼을 눌러 새 문서를 **<span class="blue-color">추가</span>**한다.</p>` | <http://materializecss.com/color.html>   |
