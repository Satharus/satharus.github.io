---
title: Test Post about C Programming 
categories: Tech
author: Ahmed Elmayyah
tags: [C, Programming, Low Level]
article_header:
    type: cover
    image: /assets/images/about/Thinkpad.jpg
cover: /assets/images/about/Thinkpad.jpg

---

This is literally just a test post about C programming to test Jekyll and stuff.

In C programming, you start writing your code in the `main()` function.

The C standard has many different signatures for `main()`, but let's just stick to `main(int argc, char* argv[])` for now;

Here is an example of a correct C program:
<!--more-->

```c
#include <stdio.h>
int main(int argc, char* argv[])
{
    if (argc > 1) printf("%s", argv[1]);
    else printf("Usage: %s <str>", argv[0]);
    return 0;
}
```
This compiles successfully on gcc.
{:.success}

This is an example of an incorrect C program:
```c
function start
{
    print("helloooo");
}
```

This doesn't compile as it isn't valid syntax.
{:.error}
