---
title:  "Rouge Code Highlighter"
date:   2019-01-19 15:34:11
categories: [Rouge]
tags: [Rouge]
---
Jekyll uses Rouge, a code snippet highlighter, to make code look nice. This is a test with Javascript, HTML, and PHP:

#### Javascript
``` javascript
<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>
```

#### HTML
``` html
<ul class="list-style-none mb-0  border-top pt-3">
```

#### PHP
``` php
<?php echo "Hello World!";?>
```

Seems to work. There's a list of supported languages and lexers at the [Github repo][github-repo-rouge] for Rouge.

[github-repo-rouge]: https://github.com/jneen/rouge/wiki/List-of-supported-languages-and-lexers
