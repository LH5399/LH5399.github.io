---
layout: post
title: "Some thoughts for the 2nd day"
author: "LH"
tags: Streak
excerpt_separator: <!--more-->
---

Hi this is the second post. There wont be too much detail, but i want to keep up with this website and "force" myself to write something to document this learning.<!--more-->
Today im showcasing one project i did with a university club. 

# Headers
{% highlight markdown %}
# H1
## H2
### H3
#### H4
##### H5
###### H6
{% endhighlight %}

# H1
## H2
### H3
#### H4
##### H5
###### H6

# Text formatting
{% highlight markdown %}
- **Bold**
- _Italics_
- ~~Strikethrough~~
- <ins>Underline</ins>
- <sup>Superscript</sup>
- <sub>Subscript</sub>
- Abbreviation: <abbr title="HyperText Markup Language">HTML</abbr>
- Citation: <cite>&mdash; Chester How</cite>
{% endhighlight %}

- **Bold**
- _Italics_
- ~~Strikethrough~~
- <ins>Underline</ins>
- <sup>Superscript</sup>
- <sub>Subscript</sub>
- Abbreviation: <abbr title="HyperText Markup Language">HTML</abbr>
- Citation: <cite>&mdash; Chester How</cite>

# Lists
{% highlight markdown %}
1. Ordered list item 1
2. Ordered list item 2
3. Ordered list item 3

* Unordered list item 1
* Unordered list item 2
* Unordered list item 3
{% endhighlight %}

1. Ordered list item 1
2. Ordered list item 2
3. Ordered list item 3

* Unordered list item 1
* Unordered list item 2
* Unordered list item 3

# Links
{% highlight markdown %}
Check out tale on [GitHub](https://github.com/chesterhow/tale).
{% endhighlight %}

Check out tale on [GitHub](https://github.com/chesterhow/tale).

# Images
{% highlight markdown %}
![Placeholder image](https://drive.google.com/file/d/1rStXBfknnNzcImB99oBXWXy7sJI0Gaft/view?usp=drive_link "Placeholder image")

![Image with caption](https://placehold.it/700x400 "Image with caption")
_This is an image with a caption_
{% endhighlight %}

![Placeholder image](https://raw.githubusercontent.com/LH5399/LH5399.github.io/b3326b4a36b8b69c155aa8221b3c54dc8e777744/images/TechClub_Linkedin_Profilbild_1000x1000px.jpg "Tech Club Logo")
_Tech Club Logo_

![Image with caption](images/TechClub_Linkedin_Profilbild_1000x1000px.jpg "Image with caption")
_This is an image with a caption_

# Code and Syntax Highlighting
Use back-ticks for `inline code`. Multi-line code snippets are supported too through Pygments.

{% highlight js %}
// Sample javascript code
var s = "JavaScript syntax highlighting";
alert(s);
{% endhighlight %}

{% highlight python %}
# Sample python code
s = "Python syntax highlighting"
print s
{% endhighlight %}

Adding `linenos` to the highlight tag enables line numbers.

{% highlight js  linenos %}
// Sample javascript code
var s = "JavaScript syntax highlighting";
alert(s);
{% endhighlight %}

# Blockquotes
{% highlight markdown %}
> Curabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.

{% endhighlight %}

> Curabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.

# Horizontal Rule & Line Break
{% highlight markdown %}
Use `<hr>` for horizontal rules

<hr>

and `<br>` for line breaks.

<br>
{% endhighlight %}

Use `<hr>` for horizontal rules

<hr>

and `<br>` for line breaks.

<br>

_The end_
