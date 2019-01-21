---
title:  "Markdown Cheat Sheet"
date:   2019-01-21 17:02:12
categories: [Markdown]
tags: [Markdown]
---
Sometimes you have to take the long way to your goal. This project so far has forced me to spend excess time learning and researching answers to problems related to Git, Github, Jekyll, and my new friend [Markdown][markdown-spec].  

This is my second or third encounter with a language that is intended to output another language in the interest of promoting less code and more readability. It didn't take long to figure out the syntax from the linked spec. Building in a new language from the ground up is difficult so I copy and pasted examples of Markdown in use, then changed what I wanted to use.   

**The following is the render from the Markdown source:**

This is a paragraph, it's surrounded by whitespace. Next up are some headers, they're heavily influenced by GitHub's markdown style.

## Header 2

### Header 3

#### Header 4  

A link to [GitHub](http://github.com/). A literal link <http://github.com/csanes/csanes.github.io/>

An image, located within /images

![an image alt text]({{ site.baseurl }}/images/git-bash-ss.jpg "Git Bash Example")


* A bulletted list
- alternative syntax 1
+ alternative syntax 2
  - an indented list item

1. An
2. ordered
3. list

Inline markup styles:

- _italics_
- **bold**
- `code()`

> Blockquote
>> Nested Blockquote

Syntax highlighting can be used by wrapping your code in a liquid tag like so:

{{ "{% highlight javascript " }}%}  
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{{ "{% endhighlight " }}%}  

creates...

{% highlight javascript %}
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{% endhighlight %}

Use two trailing spaces  
on the right  
to create linebreak tags  

Finally, horizontal lines

----
****

[markdown-spec]: https://spec.commonmark.org/0.28/
[git-bash]: https://csanes.github.io/images/git-bash-ss.jpg
