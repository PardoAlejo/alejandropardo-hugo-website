---
title: "BAOD: Budget-Aware Object Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- MengMeng Xu
- Ali Thabet
- Pablo Arbeláez
- Bernard Ghanem

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-06-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Best Paper Award at *LatinX in AI Workshop at Computer Vision and Pattern Recognition 2021*
publication_short: Best Paper Award at *LatinX in AI Workshop at CVPR 2021*

abstract: We study the problem of object detection from a novel perspective in which annotation budget constraints are taken into consideration, appropriately coined Budget Aware Object Detection (BAOD). When provided with a fixed budget, we propose a strategy for building a diverse and informative dataset that can be used to optimally train a robust detector. We investigate both optimization and learning-based methods to sample which images to annotate and what type of annotation (strongly or weakly supervised) to annotate them with. We adopt a hybrid supervised learning framework to train the object detector from both these types of annotation. We conduct a comprehensive empirical study showing that a handcrafted optimization method outperforms other selection techniques including random sampling, uncertainty sampling and active learning. By combining an optimal image/annotation selection scheme with hybrid supervised learning to solve the BAOD problem, we show that one can achieve the performance of a strongly supervised detector on PASCAL-VOC 2007 while saving 12.8% of its original annotation budget. Furthermore, when 100% of the budget is used, it surpasses this performance by 2.0 mAP percentage points.

# Summary. An optional shortened abstract.
summary: We study the problem of object detection from a novel perspective in which annotation budget constraints are taken into consideration, appropriately coined Budget Aware Object Detection (BAOD). When provided with a fixed budget, we propose a strategy for building a diverse and informative dataset that can be used to optimally train a hybrid-supervised (weakly and fully supervision combined) detector. We show that one can achieve the performance of a strongly supervised detector on PASCAL-VOC 2007 while saving 12.8% of its original annotation budget.

tags: [Best Paper Award]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# 
# - name: Custom Link
#   url: http://example.org

links:
- name: Publication
  url: https://openaccess.thecvf.com/content/CVPR2021W/LXCV/html/Pardo_BAOD_Budget-Aware_Object_Detection_CVPRW_2021_paper.html
- name: Preprint
  url: https://arxiv.org/abs/1904.05443
- name: Supplementary 
  url: https://openaccess.thecvf.com/content/CVPR2021W/LXCV/supplemental/Pardo_BAOD_Budget-Aware_Object_CVPRW_2021_supplemental.pdf
url_pdf: https://openaccess.thecvf.com/content/CVPR2021W/LXCV/papers/Pardo_BAOD_Budget-Aware_Object_Detection_CVPRW_2021_paper.pdf

# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

