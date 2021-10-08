---
title: "Rate-Regularization and Generalization in VAEs"
authors:
- Alican Bozkurt*
- Babak Esmaeili*
- Jean-Baptiste Tristan
- Dana H. Brooks
- Jennifer G. Dy
- Jan-Willem van de Meent
date: "2021-03-25"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 24th International Conference on Artificial Intelligence and Statistics"
publication_short: In *24th AISTATS*

abstract: 'Variational autoencoders (VAEs) optimize an objective that comprises a reconstruction loss (the distortion) and a KL term (the rate). The rate is an upper bound on the mutual information, which is often interpreted as a regularizer that controls the degree of compression. We here examine whether inclusion of the rate term also improves generalization. We perform rate-distortion analyses in which we control the strength of the rate term, the network capacity, and the difficulty of the generalization problem. Lowering the strength of the rate term paradoxically improves generalization in most settings, and reducing the mutual information typically leads to underfitting. Moreover, we show that generalization performance continues to improve even after the mutual information saturates, indicating that the gap on the bound (i.e. the KL divergence relative to the inference marginal) affects generalization. This suggests that the standard spherical Gaussian prior is not an inductive bias that typically improves generalization, prompting further work to understand what choices of priors improve generalization in VAEs.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
tags:
- AISTATS
featured: false


url_pdf: https://arxiv.org/pdf/1911.04594.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://virtual.aistats.org/virtual/2021/poster/1982

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
