---
layout: post
title:  "how to embed code on your blog posts"
description: changing a char to an int in Python and C++
date:   2019-11-23 21:03:36 +0530
categories: C++ Python
---
Here are some different options for embedding/highlighting code on webpages.

1) Github Gists

Create a gist or a code snippet on your Github account and copy the embed script.

If you change the gist, the update will be reflected on the website. The output looks like this:

<script src="https://gist.github.com/benmercerdev/28c49fa8baf65c0687ab954435d62d78.js"></script>

2) Pastebin.com

Has highlighting for any language you'd ever need. Output looks like this:

<script src="https://pastebin.com/embed_js/J79jhGDp"></script>

3) Triple backticks -- convention that works on many platforms (Medium, Jekyll)

If you're using Jekyll a static site generator with built-in support for GitHub Pages, you can syntax highlight your code by You can create fenced code blocks by placing triple backticks <code>```cpp</code> before and after the code block with the language identifier. The output looks like this:

```cpp
#include <iostream>
using namespace std;

int main(){
  char charNum = '9';
  intNum = charNum - '0';
  cout<< intNum;
}
```
