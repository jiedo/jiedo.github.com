---
layout: page
title: "Hi"
description: ""
tags : [hello, jie, test, first]
---
{% include JB/setup %}


# hello

  I write this for *test* .


# Create a Post

    Create posts easily via rake task:

    $ rake post title="Hello World"
    The rake task automatically creates a file with properly formatted filename and YAML Front Matter. Make sure to specify your own title. By default, the date is the current date.

    The rake task will never overwrite existing posts unless you tell it to.

# Create a Page

    Create pages easily via rake task:

    $ rake page name="about.md"
    Create a nested page:

    $ rake page name="pages/about.md"
    Create a page with a “pretty” path:

    $ rake page name="pages/about"

    # this will create the file: ./pages/about/index.html
