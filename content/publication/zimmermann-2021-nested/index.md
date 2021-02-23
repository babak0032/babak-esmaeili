---
title: "Nested Variational Inference"
authors:
- Heiko Zimmermann
- Hao Wu
- Babak Esmaeili
- Sam Stites
- Jan-Willem van de Meent
date: "2021-01-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "3rd Symposium on Advances in Approximate Bayesian Inference"
publication_short: In *3rd AABI*

abstract: 'We develop nested variational inference (NVI), a family of methods that learn proposals for nested importance samplers by minimizing an inclusive or exclusive KL divergence at each
level of nesting. NVI is applicable to many commonly-used importance sampling strategies and additionally provides a mechanism for learning intermediate densities, which can serve as heuristics to guide the sampler. Our experiments apply NVI to learn samplers targeting (a) an unnormalized density using annealing and (b) the posterior of a hidden Markov model. We observe improved sample quality in terms of log average weight and effective sample size'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
tags:
- AABI
featured: false


url_pdf: https://openreview.net/pdf/f8e2518b938638cb5c219e19438ac815f02a7554.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://www.youtube.com/watch?v=2pEkWk-LHmU&ab_channel=JordanBoyd-Graber

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  placement: 1
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
