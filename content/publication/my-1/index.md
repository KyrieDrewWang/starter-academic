---
title: "ANN based on forgetting factor for online model updating in substructure pseudo-dynamic hybrid simulation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yanhua Wang
- Jing Lv
- Jing WU
- admin

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-05-04T00:00:00Z"
doi: "https://doi.org/10.12989/sss.2020.26.1.063"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Smart Structures and Systems*
publication_short: In *SSS*

abstract: Substructure pseudo-dynamic hybrid simulation (SPDHS) combining the advantages of physical experiments and numerical simulation has become an important testing method for evaluating the dynamic responses of structures. Various parameter identification methods have been proposed for online model updating. However, if there is large model gap between the assumed numerical models and the real models, the parameter identification methods will cause large prediction errors. This study presents an ANN (artificial neural network) method based on forgetting factor. During the SPDHS of model updating, a dynamic sample window is formed in each loading step with forgetting factor to keep balance between the new samples and historical ones. The effectiveness and anti-noise ability of this method are evaluated by numerical analysis of a six-story frame structure with BRBs (Buckling Restrained Brace). One BRB is simulated in OpenFresco as the experimental substructure, while the rest is modeled in MATLAB. The results show that ANN is able to present more hysteresis behaviors that do not exist in the initial assumed numerical models. It is demonstrated that the proposed method has good adaptability and prediction accuracy of restoring force even under different loading histories.

# Summary. An optional shortened abstract.
summary: Apply the ANN to Model updating in hybrid test.

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
  caption: 'Simulatioin Results'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- my-project-HybridTest

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

