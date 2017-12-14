# Theme Documentation

**NOTE:** This markdown cheatsheet is a typography demo for this theme. Check out this post to learn more about this markdown usage when you want to get started with this theme. Enjoy!

## Typography Elements in One

Let's start with a informative paragraph. **This text is bolded.** But not this one! _How about italic text?_ Cool right? Ok, let's **_combine_** them together. Yeah, that's right! I have code to highlight, so `ThisIsMyCode()`. What a nice! Good people will hyperlink away, so [here we go](#) or [http://www.example.com](http://www.example.com).

<div class="divider"></div>

## Headings H1 to H6

# H1 Heading

## H2 Heading

### H3 Heading

#### H4 Heading

##### H5 Heading

###### H6 Heading

<div class="divider"></div>

## Blockquote

> Start by doing what's necessary; then do what's possible; and suddenly you are doing the impossible. --Francis of Assisi

**NOTE:** This theme does NOT support nested blockquotes.

<div class="divider"></div>

## List Items

1. First order list item
2. Second item

* Unordered list can use asterisks
- Or minuses
+ Or pluses

<div class="divider"></div>

## Code Blocks

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

<div class="divider"></div>

## Navigation
Point to `_data/nav.yml`, it's looks like:

```
- title: About
  url: /about
- title: MORE PAGE
  url: /page  
```

<div class="divider"></div>

## Table

### Table 1: With Alignment

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

### Table 2: With Typography Elements

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

<div class="divider"></div>

## Horizontal Line

The HTML `<hr>` element is for creating a "thematic break" between paragraph-level elements. In markdown, you can create a `<hr>` with any of the following:

* `___`: three consecutive underscores
* `---`: three consecutive dashes
* `***`: three consecutive asterisks

renders to:

___

---

***

<div class="divider"></div>

## Media

### Video Embedded Iframe

- Youtube
```
{% include video.html url="https://www.youtube.com/embed/UNIQUE_CODE" width="560" height="315" %}
```

- Vimeo
```
{% include video.html url="https://player.vimeo.com/video/UNIQUE_CODE" width="560" height="315" %}
```

### Image

Store images on `/assets/posts/YYYY-MM-DD-Title` folder just like post.

```
{% include image.html name="image.jpg" caption="CAPTION" %}
```

## Credit
- [Theme: The Plain v3.0](https://github.com/heiswayi/the-plain)
- [Jekyll Documentation](https://jekyllrb.com/docs/home/)
- [Easily install Jekyll on Windows with 3 command prompt entries and Chocolatey](https://davidburela.wordpress.com/2015/11/28/easily-install-jekyll-on-windows-with-3-command-prompt-entries-and-chocolatey/)
- [How to make your Jekyll site show up on social](http://aramzs.github.io/jekyll/social-media/2015/11/11/be-social-with-jekyll.html)
- [Including And Managing Images in Jekyll](https://eduardoboucas.com/blog/2014/12/07/including-and-managing-images-in-jekyll.html)
- [Dynamic navigation for Jekyll](https://codegaze.github.io/2015/08/08/how-to-create-a-dynamic-navigation-menu-in-jekyll/)
- [Creating responsive Video Embeds in Jekyll](https://eduardoboucas.com/blog/2016/12/21/responsive-video-embeds-jekyll.html)
- [Using Jekyl 2017 - Mademistakes](https://mademistakes.com/articles/using-jekyll-2017/)

