---
title: "RefineLoc: Iterative Refinement for Weakly-Supervised Action Localization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Humam Alwassel
- Fabian Caba Heilbron
- Juan León Alcázar
- Ali Thabet
- Bernard Ghanem

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-01-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: At *Winter Conference on Applications of Computer Vision 2021*
publication_short: At *WACV 2021*

abstract: Video action detectors are usually trained using datasets with fully-supervised temporal annotations. Building such datasets is an expensive task. To alleviate this problem, recent methods have tried to leverage weak labeling, where videos are untrimmed and only a video-level label is available. In this paper, we propose RefineLoc, a novel weakly-supervised temporal action localization method. RefineLoc uses an iterative refinement approach by estimating and training on snippet-level pseudo ground truth at every iteration. We show the benefit of this iterative approach and present an extensive analysis of five different pseudo ground truth generators. We show the effectiveness of our model on two standard action datasets, ActivityNet v1.2 and THUMOS14. RefineLoc shows competitive results with the state-of-the-art in weakly-supervised temporal localization. Additionally, our iterative refinement process significantly improves the performance of two state-of-the-art methods, setting a new state-of-the-art on THUMOS14.

# Summary. An optional shortened abstract.
summary: RefineLoc is a weakly-supervised temporal action localization method. RefineLoc uses an iterative refinement approach by estimating and training on snippet-level pseudo ground truth at every iteration. Our method shows competitive results with the state-of-the-art in weakly-supervised temporal localization. Additionally, our iterative refinement process significantly improves the performance of two state-of-the-art methods, setting a new state-of-the-art on THUMOS14.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# - name: Custom Link
#   url: http://example.org
links:
- name: Publication
  url: https://openaccess.thecvf.com/content/CVPR2021W/LXCV/html/Pardo_BAOD_Budget-Aware_Object_Detection_CVPRW_2021_paper.html
- name: Preprint
  url: https://arxiv.org/abs/1904.00227
- name: Supplementary 
  url: https://openaccess.thecvf.com/content/WACV2021/supplemental/Pardo_RefineLoc_Iterative_Refinement_WACV_2021_supplemental.pdf

url_pdf: https://openaccess.thecvf.com/content/WACV2021/papers/Pardo_RefineLoc_Iterative_Refinement_for_Weakly-Supervised_Action_Localization_WACV_2021_paper.pdf
url_code: https://github.com/HumamAlwassel/RefineLoc

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
