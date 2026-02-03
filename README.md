# Git Practice

## Article
[How Git Works Internally](https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain)

## Why I found this interesting
This article helped me understand that Git does not track changes line by line, but instead
stores snapshots of the entire project. That design choice explains why branching and merging
are fast and reliable, even in large projects.

Learning how Git stores objects and commits internally made the distributed workflow feel
less abstract and more predictable, which is important when collaborating on real software
engineering projects.

## Ethan's edit
The distinction between Git's "plumbing" commands and "porcelain" commands is especially interesting. It makes sense that there would be a lower-level class of commands and a higher-level, more user-friendly class of commands, but I never thought about it this way. The names are also cute. 