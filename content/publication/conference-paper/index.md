---
title: 'Fully Quantized Always-on Face Detector Considering Mobile Image Sensors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wongi Jeong
  - Dongil Ryu
  - Hyunwoo Je
  - Albert No
  - Kijeong Kim
  - Se Young Chun

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: ''
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*IEEE/CVF International Conference on Computer Vision 2023 Workshop on Low-Bit Quantized Neural Networks (LBQNN)*"
publication_short: "ICCVW 2023"

abstract: Despite significant research on lightweight deep neural networks (DNNs) designed for edge devices, the current face detectors do not fully meet the requirements for "intelligent" CMOS image sensors (iCISs) integrated with embedded DNNs. These sensors are essential in various practical applications, such as energy-efficient mobile phones and surveillance systems with always-on capabilities. One noteworthy limitation is the absence of suitable face detectors for the always-on scenario, a crucial aspect of image sensor-level applications. These detectors must operate directly with sensor RAW data before the image signal processor (ISP) takes over. This gap poses a significant challenge in achieving optimal performance in such scenarios. Further research and development are necessary to bridge this gap and fully leverage the potential of iCIS applications. In this study, we aim to bridge the gap by exploring extremely low-bit lightweight face detectors, focusing on the always-on face detection scenario for mobile image sensor applications. To achieve this, our proposed model utilizes sensor-aware synthetic RAW inputs, simulating always-on face detection processed "before" the ISP chain. Our approach employs ternary (-1, 0, 1) weights for potential implementations in image sensors, resulting in a relatively simple network architecture with shallow layers and extremely low-bitwidth. Our method demonstrates reasonable face detection performance and excellent efficiency in simulation studies, offering promising possibilities for practical always-on face detectors in real-world applications.

# Summary. An optional shortened abstract.
summary:

tags:
- Source Themes
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: ''
url_arXiv: 'https://arxiv.org/abs/2311.01001'
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://sites.google.com/view/lbqnn-iccv-23/home?authuser=0'
url_video: 'https://drive.google.com/file/d/1q9DdqWg0T1Q4HBML2w3lYSyGZ3e8c23o/view'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
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
