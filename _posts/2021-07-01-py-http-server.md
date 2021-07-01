---
layout: post
title: Setting up a local server on my chromebook tablet
tags: python http server
---

I was relieved when I could successfully setup a local server on my Lenovo Chromebook Duet tablet. Its arm-based Linux is short of packages compared to Intel-based Chromebook, such as Android Studio. This had limited the learning opportunities for me. 

With Python3, I can start a local server for testing purposes, at localhost:8000.

```python
python3 -m http.server
```