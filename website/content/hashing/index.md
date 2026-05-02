---
title: "Hashing"
# https://vitepress.dev/reference/default-theme-home-page
layout: home
prev: false
next: false
footer: true

hero:
  name: "Hashing Algorithms"
  tagline: Open-source algorithms for turning content into anonymous digital fingerprints called "hashes".

features:
  - title: PDQ
    details: |
      A perceptual hasher: it tries to match images which people perceive as similar. It is a spectral hashing algorithm, namely, it uses a Discrete Cosine Transform (DCT). One of its outputs is a quality metric, enabling systems to filter junky/featureless images out of processing.
    link: /hashing/pdq
  - title: vPDQ
    details: vPDQ (Video PDQ) is a video-similarity-detection algorithm, which uses the PDQ image similarity algorithm on video frames to measure the similarity of videos.
    link: /hashing/vpdq
  - title: TMK
    details: Temporal Match Kernel is a video-similarity-detection algorithm produced in conjunction with Facebook AI Research ('FAIR')
    link: /hashing/tmk
---

