---
layout: post
title: DV Quilting
categories:
  - video digital
tags:
  - Digital
  - Video
  - Quilting
  - DCT
  - Discrete Cosine Transform
  - Error
  - DV
published: true
---

## Description
In DV footage with strong horizontal and diagonal imagery, an artifact similar to stair steps can appear due to "discontinuities between adjacent DCT blocks" [Adam Wilt, 1998](https://www.adamwilt.com/pix-artifacts.html). This artifact is inherent to DCT compressors, which include JPEG and MPEG codecs. DCT compressors process images in 8 x 8 blocks, which do not reproduce smoothly transformed diagonal lines. Enhancing the aperture control on a high-resolution monitor can intensify this artifact, especially in footage with slow camera movement. Video recordings with objects arranged on an approximately 20 degree diagonal plane seem to be particularly affected by this phenomenon.

## Can it be fixed?
No, quilting cannot be remedied.

## Example(s)

<iframe src="https://archive.org/embed/AVAA.DVQuilting" width="560" height="315" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>

In this clip, notice the quilting that appears in the blinds in the lower area of the image.

<img src="https://github.com/bavc/avaa/blob/master/images/Quilting_Flat.jpg"> 

## Resources 

[DV Pix - Image Artifacts, 1998](https://www.adamwilt.com) <br>
[DV Technology for Video Computer Applications, 2008](https://people.kth.se/~eskil/DV/DV_overwiev.pdf)
