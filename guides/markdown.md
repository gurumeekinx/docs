# Markdown

Markdown is an easy and powerful way to format your descriptions and long text fields using simple, natural syntax.

## The basics
```
*italic* and **bold**
```

*italic* and **bold**

```
An inline link: [Kumu](http://launch.kumupowered.com)
```

An inline link: [Kumu](http://launch.kumupowered.com)

```
http://launch.kumupowered.com
```

An auto-generated link:

```
<a href="http://launch.kumupowered.com">http://launch.kumupowered.com</a>
```


## Lists

```
* Milk
* Cookies
* Marshmallows
```
Looks like:

* Milk
* Cookies
* Marshmallows

```
1. California
2. Texas
3. New York
```
Looks like:

1. California
2. Texas
3. New York


## Links within your account

We also support linking to elements, connections and loops (even other maps in your account).

<p><iframe width="560" height="315" src="https://www.youtube.com/embed/iORN_mRpkMI" frameborder="0" allowfullscreen></iframe></p>

You can use the following syntax:

**Selectors**

    [link label](= selector)
    [Ryan](= #ryanmohr)

*Note: Make sure to remove any special characters and spaces from your element, connection or loop label and lowercase all letters ("Kumu is awesome!" would become "kumuisawesome").*

**Maps**

    [link label](#map-slug)

**views**

    [link label](#map-slug/view-slug)

*Note: The best way to find the "map-slug" and "view-slug" is to activate the given map and view and look at the URL in your browser. You should be able to spot it quite easily by using the above format as a guide. Then copy and paste the applicable portion.*

## Images

```
![alt text](image-url)

![Kumu Logo](http://blog.kumu.io/content/images/2015/08/kumu-logo-cutout-full-dark.png)
```


## Videos

Look at the embed code of the video you want to embed and grab the URL within ***src=" "***

    ![I Believe I Can Fly](//player.vimeo.com/video/31240369?color=ffffff)

## Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
Looks like:

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


## Code

Simply indent lines with four spaces or wrap the code with three backticks:

    ```
    <div class="footer">
        &copy; 2013 Kumu Systems LLC
    </div>
    ```
Looks like:

```
<div class="footer">
    &copy; 2013 Kumu Systems LLC
</div>
```


## Blockquotes

    > Add quote text here

Looks like:

> Add quote text here

## Tables

```
One | Two | Three
--- | --- | ---
Blue | White | Gray
Green | Yellow | Red
```

If you are using Markdown in the Description column of an [import](/guides/import.md), you will have to use the [HTML table tag](https://www.w3schools.com/tags/tag_table.asp) rather than the usual Markdown syntax. Make sure to remove all line breaks from your HTML, or your table will render with a large white space above it.

```
<table><tr><th>One</th><th>Two</th><th>Three</th></tr><tr><td>Blue</td><td>White</td><td>Gray</td></tr><tr><td>Green</td><td>Yellow</td><td>Red</td></tr></table>
```

## Horizontal Rules

    Three or more dashes or asterisks
    ---
    ***

Looks like:

---

<br />
Now you know the basics of formatting with markdown! For more information, visit [Daring Fireball's markdown syntax documentation](http://daringfireball.net/projects/markdown/syntax#precode).


## Inline HTML

Kumu's markdown editor also recognizes a limited amount of inline HTML. Here are the tags you can use in Kumu, anywhere that accepts markdown:
```
<a>
<aside>
<b>
<blockquote>
<br>
<caption>
<code>
<del>
<dd>
<dfn>
<div>
<dl>
<dt>
<em>
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>
<hr>
<i>
<img>
<ins>
<kbd>
<li>
<ol>
<p>
<pre>
<q>
<samp>
<span>
<strike>
<strong>
<sub>
<sup>
<table>
<tbody>
<td>
<tfoot>
<th>
<thead>
<tr>
<tt>
<ul>
<var>
```

And here are the HTML attributes that use can use for each tag:

```
<a>
  href

<img>
  src

<div>
  itemscope
  itemtype

all tags
  abbr
  accept
  accept-charset
  accesskey
  action
  align
  alt
  axis
  border
  cellpadding
  cellspacing
  char
  charoff
  charset
  checked
  cite
  clear
  cols
  colspan
  color
  compact
  coords
  datetime
  dir
  disabled
  enctype
  for
  frame
  headers
  height
  hreflang
  hspace
  ismap
  label
  lang
  longdesc
  maxlength
  media
  method
  multiple
  name
  nohref
  noshade
  nowrap
  prompt
  readonly
  rel
  rev
  rows
  rowspan
  rules
  scope
  selected
  shape
  size
  span
  start
  summary
  tabindex
  target
  title
  type
  usemap
  valign
  value
  vspace
  width
  itemprop
```


<span class="edit-link"><a href="https://github.com/kumu/docs/blob/master/guides/markdown.md" target="_blank"><i class="fa fa-github"></i> edit this page</a></span>
