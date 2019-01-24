---
title:  "GitHub Pages Project"
date:   2019-01-19 00:31:10
categories: [GitHub]
tags: [GitHub]
---
Time to take a break and reflect. I found out about GitHub Pages and decided to create a web portfolio site on the platform. I had no idea how to use Git, GitHub, Atom, or Jekyll. A crash course was in order.

There's a great book online that got the learning jumpstarted: [Pro Git][pro-git-book]. This free book has everything you need to setup Git. Chapters include Git basics, branching, distributed workflows, GitHub, and much more. I spent a few hours reading and experimenting with the commands and examples that are included.

![alt text][pro-git]

Creating a [GitHub][github-home] account was pretty straightforward. After that I wanted to have a command-line interface to use git commands (push pull, commit, etc.) so I downloaded [Git for Windows][git-for-windows]. It included a GUI, Bash, & CMD. Some configuration was required but the documentation was thorough.

![alt text][git-bash]

The next step was to create a repository on GitHub with the following naming convention: "**username**.github.io". Using Git Bash I ran:

``` php
$ git clone https://github.com/csanes/csanes.github.io
```  

This created a local copy of the project repository that I could import/open with Atom, the hackable text editor. My workflow was substantially improved at this point. Atom is integrated with Git and GitHub making it easy to push and pull from/to local/remote repos. This barebones "CMS?" also lets me edit multiple files simultaneously with language specific highlighters that make reading/writing code much easier on the eyes.  

With the backend stuff taken care of it was now time to look for a completed GitHub Page to fork/clone. Reverse-engineering a completed build is the easiest way for me to learn a new system. [Jekyll-Uno by Josh Gerdes][jekyll-uno] was a great template for this purpose.

[pro-git]: https://csanes.github.io/images/pro-git-example.jpg "Pro Git eBook"
[github-home]: https://github.com
[git-for-windows]: https://git-scm.com/downloads
[git-bash]: https://csanes.github.io/images/git-bash-ss.jpg "Git Bash for Windows"
[pro-git-book]: https://git-scm.com/book/en/v2
[jekyll-uno]: https://github.com/joshgerdes/jekyll-uno
