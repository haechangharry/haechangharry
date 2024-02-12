---
title: "PyNET-QxQ: An Efficient PyNET Variant for QxQ Bayer Pattern Demosaicing in CMOS Image Sensors"
authors:
- Minhyeok Cho
- admin
- Hyunwoo Je
- Kijeong Kim
- Dongil Ryu
- Albert No
author_notes: ""
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*"
publication_short: "IEEE Access"

abstract: Deep learning-based image signal processor (ISP) models for mobile cameras can generate high-quality images that rival those of professional DSLR cameras. However, their computational demands often make them unsuitable for mobile settings. Additionally, modern mobile cameras employ non-Bayer color filter arrays (CFA) such as Quad Bayer, Nona Bayer, and Q×Q Bayer to enhance image quality, yet most existing deep learning-based ISP (or demosaicing) models focus primarily on standard Bayer CFAs. In this study, we present PyNET- Q×Q , a lightweight demosaicing model specifically designed for Q×Q Bayer CFA patterns, which is derived from the original PyNET. We also propose a knowledge distillation method called progressive distillation to train the reduced network more effectively. Consequently, PyNET- Q×Q contains less than 2.5% of the parameters of the original PyNET while preserving its performance. Experiments using Q×Q images captured by a prototype Q×Q camera sensor show that PyNET- Q×Q outperforms existing conventional algorithms in terms of texture and edge reconstruction, despite its significantly reduced parameter count. Code and partial datasets can be found at https://github.com/Minhyeok01/PyNET-QxQ.

# Summary. An optional shortened abstract.
summary:

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10114931'
url_code: 'https://github.com/Minhyeok01/PyNET-QxQ'
url_arXiv: 'https://ieeexplore.ieee.org/abstract/document/10114931'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---