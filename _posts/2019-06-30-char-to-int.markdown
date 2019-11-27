---
layout: post
title:  "char to int (Python v. C++)"
description: changing a char to an int in Python and C++
date:   2019-11-23 21:03:36 +0530
categories: C++ Python
---

In C++, subtract the ASCII value of '0' to any char from '0' to '9' to get the int equivalent:

<script src="https://gist.github.com/benmercerdev/28bb08e4998be18068586ee7c3f2c3cb.js"></script>

In Python, simply cast the char with an int(), or if you want the ASCII value use ord() function:

<script src="https://gist.github.com/benmercerdev/f13a8e30d5b8dee22fb2fdb3726c1162.js"></script>
