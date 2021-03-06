---
title: Hello, Cosette
date: 2014-02-27 00:00:00 +0000
quote: I've changed everything here, once and for all
image:
  url: "/media/2014-02-27-hello-cosette/cover.jpg"
video: false
comments: false
theme_color: 302F2D
layout: post
image_url: "/media/2014-01-22-thinny-2/bianca.jpg"
page_images:
- "/uploads/2017/11/06/11-dribbble-animation-iphone-app-ui.gif"
- "/assets/images/luke.png"
image.url: ''
undefined: []
---
# Thinny 2.1, codename "[Cosette](http://lesmiserables.wikia.com/wiki/Cosette)"

Cosette is an important character in the french novel _Les Misérables_, published in 1862 by _Victor Hugo_.

{% include image.html url="/media/2014-02-27-hello-cosette/cosette.jpg" width="100%" description="Amanda Seyfried as Cosette on the 2012 movie." %}

{% include image.html  url="/media/2014-02-27-hello-cosette/cosette.jpg"  width="100%" description=page.page_images %}

This new version of Thinny comes with mobile support and some bugfixes.

## Usage

### Main variables

The global variables are set on the `_config.yml`<sup id="fnref:1"><a class="footnote" href="#fn:1">1</a></sup> file.

To start, you need to change at least the variable `url` on the file.

#### Social links

To add a social link you just need to add the following code inside the variable `social`:

      - icon:   [the genericon name for the social network]
        url:    [the url to follow]
        desc:   [a small description for the link (e.g. "Follow me on twitter")]

#### Menu

To add a menu item you just need to add the following code inside the variable `menu`:

      - title:  [title of the menu item]
        url:    [the url to follow]

#### Others

You'll find a lot of other variables inside the file, e.g.:

* the site `title`, `description`, `icon` and default `cover` image.

* text of the `copyright` message.

* the number of posts per page (`paginate`).

* the `permalink`'s structure (see [the docs](http://jekyllrb.com/docs/pagination/)).

### Default YAML tags

* `layout:_post, page_` `or_fullscreen_`: defines the layout of the page.

* `title: \\\\\\\[string\\\\\\\]`: title of the post.

* `quote: \\\\\\\[string\\\\\\\]`: a small description of the post to be shown above the title.

* `dark:_true_` `or_false_`: use black font (instead of white) for the header (default value is false).

* `image: \\\\\\\[url\\\\\\\] or_false_`: a cover image for the post (default value is _false_).

* `video:_true_` `or_false_`: add a cover video for the post (default value is _false_).

* `video_mp4: \\\\\\\[url\\\\\\\]`: the URL for the mp4 video.

* `video_webm: \\\\\\\[url\\\\\\\]`: the URL for the webm video.

* `video_ogv: \\\\\\\[url\\\\\\\]`: the URL for the ogv video.

## Versions

Here is a table with all Thinny's versions:

| Version | Codename | Platform | Release date |
| --- | --- | --- | --- |
| 0.3 | Alexandra | Ghost 0.3.x | November 2013 |
| 2.0 | Bianca | Jekyll | January 2014 |
| 2.1 | Cosette | Jekyll | February 2014 |
| 2.2 | Dolores | Jekyll | Soon…<sup id="fnref:2"><a class="footnote" href="#fn:2">2</a></sup> |

## Download

> Thinny 2.1 is already [available for download on GitHub](https://github.com/camporez/Thinny/releases).

---

Want to see something else added or report a bug? [Open an issue](https://github.com/camporez/camporez.github.io/issues/new).

<div class="footnotes"><ol><li id="fn:1"><p>This file is placed in your root directory. It's the main file of configuration. For more information, read <a href="http://jekyllrb.com/docs/configuration/">the docs</a>. <a class="reversefootnote" href="#fnref:1">↩</a></p></li><li id="fn:2"><p>See the <a href="https://github.com/camporez/camporez.github.io/issues?milestone=3">issues list</a>. <a class="reversefootnote" href="#fnref:2">↩</a></p></li></ol></div>