---
title:  "CAPE: A Content-Addressable Processing Engine"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kailin Yang
- Srivatsa Srinivasa
- Akshay Krishna Ramanathan
- Khalid Al-Hawaj
- Tianshu Wu
- Vijaykrishnan Narayanan
- Christopher Batten
- José F. Martínez

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 27th IEEE International Symposium on High-Performance Computer Architecture (HPCA-27), Seoul, South Korea*
publication_short: In *HPCA 2021, Seoul, South Korea*

abstract: Processing-in-memory (PIM) architectures attempt to overcome the von Neumann bottleneck by combining computation and storage logic into a single component. The contentaddressable parallel processing paradigm (CAPP) from the seventies is an in situ PIM architecture that leverages contentaddressable memories to realize bit-serial arithmetic and logic operations, via sequences of search and update operations over multiple memory rows in parallel. In this paper, we set out to investigate whether the concepts behind classic CAPP can be used successfully to build an entirely CMOS-based, general-purpose microarchitecture that can deliver manyfold speedups while remaining highly programmable. We conduct a full-stack design of a Content-Addressable Processing Engine (CAPE), built out of dense push-rule 6T SRAM arrays. CAPE is programmable using the RISC-V ISA with standard vector extensions. Our experiments show that CAPE achieves an average speedup of 14 (up to 254) over an area-equivalent (slightly under 9mm2 at 7 nm) out-of-order processor core with three levels of caches.

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
