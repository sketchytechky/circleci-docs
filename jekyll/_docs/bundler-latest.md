---
layout: classic-docs
title: "Do you need the latest version of Bundler?"
description: Latest versions of bundler
---

CircleCI typically tracks the latest stable version of bundler.
Your project may occasionally need to use a pre-release version, which is easy to add to your build.
Just add the following to your [circle.yml]({{ site.baseurl }}/configuration/) file.

```
dependencies:
  pre:
    - gem install bundler --pre
```
