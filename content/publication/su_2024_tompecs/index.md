---
title: "Learning-Augmented Energy-Aware List Scheduling of Precedence-Constrained Tasks"
authors:
- Yu Su
- Vivek Anand
- Jannie Yu
- Jian Tan
- Adam Wierman
date: "2022-01-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We study the problem of scheduling precedence-constrained tasks to balance between performance and energy consumption. We consider a system with multiple servers capable of speed scaling and seek to schedule precedence-constrained tasks to minimize a linear combination of performance and energy consumption. Inspired by the single-server setting, we propose the concept of pseudo-size for individual tasks, which is a measure of the externalities of a task in the precedence graph and is learned from historical workload data.We then propose a two-stage scheduling framework that uses a learned pseudo-size approximation and achieves a provable approximation bound on the linear combination of performance and energy consumption for both makespan and total weighted completion time, where the quality of the bound depends on the approximation quality of pseudo-sizes. We show experimentally that learning-based approaches consistently perform near optimally.

publication: '*ACM Transactions on Modeling and Performance Evaluation of Computing Systems*'
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: Custom Link
url: "https://dl.acm.org/doi/pdf/10.1145/3680278"
url_pdf: "https://dl.acm.org/doi/pdf/10.1145/3680278"
# url_code: ''
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
