---
title:  "Semi-automatic validation of cycle-accurate simulation infrastructures: The case for gem5-x86"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Juan M. Cebrian
- Adrián Barredo
- admin
- Miquel Moretó
- Marc Casas
- Mateo Valero

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Future Generation Computer Systems (November 2020)*
publication_short: In *Future Generation Computer Systems (November 2020)*

abstract: Since the early 70s, simulation infrastructures have been a keystone in computer architecture research, providing a fast and reliable way to prototype and evaluate ideas for future computing systems. There are different types of simulators, from most detailed (cycle-accurate) to time-based/functional and analytical modeling. Increasing accuracy translates into several orders of magnitude in terms of simulation speed. Yet, a question remains open: are the results derived from the simulation infrastructure representative of a real machine? Validation of these infrastructures is complex and costly, usually performed upon release. However, most simulators do not provide the appropriate means to verify or validate new architectural models. In this paper, we introduce a semi-automatic validation framework based on real-hardware performance counter information. The framework provides two levels of abstraction: (a) a high level definition of the processor behavior (Top-Down model) and (b) detailed per-structure and per-pipeline-stage usage breakdown to pinpoint simulator issues. We used this framework to validate the latest available gem5-x86 simulation environment, and found several sources of error that alter the expected behavior of the simulated processor, which we were later to document and correct.


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
