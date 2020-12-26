---
title: "Docker; Τι είναι και τι κάνει!"
author: Alex M
date: '2020-12-23'
linkTitle: "Docker για Αρχάριους"
description: >
  Πως μπορούμε να δημιουργήσουμε και να διανέμουμε εύκολα τις εφαρμογές μας στο cloud, με το Docker
resources:
  src: '**.{png,jpg,svg}'
  title: 'Εικόνα #:counter'
  params:
    byline: 'Το επίσημο logo του docker'
images:
- docker-logo.png
---

![](docker.svg)

**This is a typical blog post that includes images.**

The front matter specifies the date of the blog post, its title, a short description that will be displayed on the blog landing page, and its author.



## Including images

Here's an image (`featured-sunset-get.png`) that includes a byline and a caption.

{{< imgproc space1 Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}

The front matter of this post specifies properties to be assigned to all image resources:

```
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
```

To include the image in a page, specify its details like this:

```
{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}
```

The image will be rendered at the size and byline specified in the front matter.


