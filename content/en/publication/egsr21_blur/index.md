---
title: "Fast Polygonal Splatting using Directional Kernel Difference"
authors:
- moroto
- Toshiya Hachisuka
- admin
date: "2021-06-26T00:00:00Z"
doi: ""

# Link authors to their profile page? (true/false)
link_authors: true

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of Eurographics Symposium on Rendering 2021
publication_short: EGSR 2021

abstract: Depth-of-field (DoF) filtering is an important image-processing task for producing blurred images similar to those obtained with a large aperture camera lens. DoF filtering applies an image convolution with a spatially varying kernel and is thus computationally expensive, even on modern computational hardware. In this paper, we introduce an approach for fast and accurate DoF filtering for polygonal kernels, where the value is constant inside the kernel. Our approach is an extension of the existing approach based on discrete differenced kernels. The performance gain here hinges upon the fact that kernels typically become sparse (i.e., mostly zero) when taking the difference. We extended the existing approach to conventional axis-aligned differences to non-axis-aligned differences. The key insight is that taking such differences along the directions of the edges makes polygonal kernels significantly sparser than just taking the difference along the axis-aligned directions, as in existing studies. Compared to a naive image convolution, we achieve an order of magnitude speedup, allowing a real-time application of polygonal kernels even on high-resolution images.

# Summary. An optional shortened abstract.
summary: Proceedings of EGSR 2021

tags:
- Image Processing
featured: false

links:
- name: Supplemental Material
  url: https://drive.google.com/drive/folders/1xofVIxNZZG3eti7dFWIW1jv8N0wu68OR
- name: YouTube Video
  url: https://www.youtube.com/watch?v=F5sRzwi_Q5E
url_pdf: https://www.dropbox.com/s/7aoeykgjjbjrbff/2021_egsr_blur.pdf?dl=0



youtubeid: F5sRzwi_Q5E

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

### Filtered Images
- [Google Drive](https://drive.google.com/drive/folders/1xofVIxNZZG3eti7dFWIW1jv8N0wu68OR) ([Download All](https://drive.google.com/file/d/1yEaI9trRX-nx3-cQ15vqOY7eA7xoYah3/view?usp=sharing))

### Presentation Video
- [YouTube](https://www.youtube.com/watch?v=F5sRzwi_Q5E)

### Products using This Technology
- [Fast Camera Lens Blur](https://aescripts.com/fast-camera-lens-blur/)
-- A high-speed camera lens blur plug-in that works with Adobe After Effects/Premiere Pro.