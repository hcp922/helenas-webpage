---
title:  "Using Arm’s Scalable Vector Extension on Stencil Codes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Adrià Armejach
- admin
- Juan M. Cebrian
- Rubén Langarita
- Rekai González-Alberquilla
- Chris Adeniyi-Jones
- Mateo Valero
- Marc Casas
- Miquel Moretó

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *The Journal of Supercomputing (March 2020)*
publication_short: In *The Journal of Supercomputing (March 2020)*

abstract: Data-level parallelism is frequently ignored or underutilized. Achieved through vector/SIMD capabilities, it can provide substantial performance improve- ments on top of widely used techniques such as thread-level parallelism. However, manual vectorization is a tedious and costly process that needs to be repeated for each specific instruction set or register size. In addition, automatic compiler vectorization is susceptible to code complexity, and usually limited due to data and control dependencies. To address some of these issues, Arm recently released a new vector ISA, the Scalable Vector Extension (SVE), which is Vector-Length Agnostic (VLA). VLA enables the generation of binary files that run regardless of the physical vector register length. In this paper we leverage the main characteristics of SVE to implement and optimize stencil computations, ubiquitous in scientific computing. We show that SVE enables easy deployment of textbook optimizations like loop unrolling, loop fusion, load trading or data reuse. Our detailed simulations using vector lengths ranging from 128 to 2,048 bits show that these optimizations can lead to performance improvements over straight-forward vectorized code of up to 1.57x. In addition, we show that certain optimizations can hurt performance due to reduced arithmetic intensity and instruction overheads, and provide insight useful for com- piler optimizers.


# Summary. An optional shortened abstract.
summary: []

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
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
slides: []
---
