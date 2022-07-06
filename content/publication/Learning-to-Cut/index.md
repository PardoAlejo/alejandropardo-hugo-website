---
title: "Learning to Cut by Watching Movies"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Fabian Caba Heilbron
- Juan León Alcázar
- Ali Thabet
- Bernard Ghanem

# Author notes (optional)
author_notes:
- ""
# - "Equal contribution"

date: "2021-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Presented at *Internation Conference of Computer Vision 2021*
publication_short: Presented at *ICCV 2021*

abstract: Video content creation keeps growing at an incredible pace; yet, creating engaging stories remains challenging and requires non-trivial video editing expertise. Many video editing components are astonishingly hard to automate primarily due to the lack of raw video materials. This paper focuses on a new task for computational video editing, namely the task of raking cut plausibility. Our key idea is to leverage content that has already been edited to learn fine-grained audiovisual patterns that trigger cuts. To do this, we first collected a data source of more than 10K videos, from which we extract more than 260K cuts. We devise a model that learns to discriminate between real and artificial cuts via contrastive learning. We set up a new task and a set of baselines to benchmark video cut generation. We observe that our proposed model outperforms the baselines by large margins. To demonstrate our model in real-world applications, we conduct human studies in a collection of unedited videos. The results show that our model does a better job at cutting than random and alternative baselines.

# Summary. An optional shortened abstract.
summary: We propose a new method and pipeline to create video rditing cuts recommendations. Our method utilizes the information of already edited content (movies) to learn patterns between plausible and not plausible cuts via contrastive learning. We set up a new task and a set of baselines to benchmark video cut generation. To demonstrate our model in real-world applications, we conduct human studies in a collection of unedited videos. The results show that our model does a better job at cutting than random and alternative baselines.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

links:
- name: Publication
  url: https://openaccess.thecvf.com/content/ICCV2021/html/Pardo_Learning_To_Cut_by_Watching_Movies_ICCV_2021_paper.html
- name: Supp
  url: https://drive.google.com/file/d/1Wkm77Fdu11yxEb3rbpk5J583zA2UcOJF/view?usp=sharing
- name: Preprint
  url: https://arxiv.org/abs/2108.04294
url_pdf: https://arxiv.org/pdf/2108.04294.pdf
url_code: https://github.com/PardoAlejo/LearningToCut.git
# url_dataset: ''
# url_poster: ''
# url_project: ''
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
