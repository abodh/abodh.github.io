---
title: 'Multiarea inertia estimation using convolutional neural networks and federated learning'
# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
- me
- ujjwol
- rodrigo
- robert
- reinaldo
- tim

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-12-29T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-28T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Systems Journal
# publication_short: In *ICW*

abstract: With the increase in penetration of renewable energy sources (RES), traditional inertia estimation techniques based purely on the number of online synchronous generators are increasingly unsuitable, ultimately leading towards suboptimal frequency control in the electric power grid. The stochastic nature of RES additionally makes the system inertia a time-varying quantity. Furthermore, the frequency and inertial response of power systems change drastically in multiarea power systems with interconnected tie-lines. Hence, it is important for state/parameter estimation (e.g., inertia) in multiarea systems, while ensuring communication between each of the areas. In this article, a client–server-based federated learning framework is used to estimate power system inertia in a multiarea system. Federated learning is a machine learning technique where multiple decentralized devices are trained with local data, and a global model is updated and redistributed by a central server by aggregating the trained weights of the decentralized devices, without exchanging the local data. Using local frequency measurements, obtained from the phase-locked loop of an energy storage system, the inertia at each of the areas can be estimated locally via offline training using convolutional neural networks (CNNs), whereas the CNN weights update in an online fashion. The framework, tested on a two-area power system, accurately estimated the inertia constant for both independent and identically distributed (IID) and non-IID data. Furthermore, the CNN-based method outperformed conventional neural network-based estimation techniques in terms of number of communication rounds and estimation accuracy.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Convolutional neural networks (CNNs)
  - federated learning (FL)
  - low-inertia grids
  - multiarea power system
  - power system inertia estimation

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/JSYST.2021.3134599

# Custom links
links:
  # - type: pdf
  #   url: https://ieeexplore.ieee.org/abstract/document/9449814
  - type: code
    url: https://github.com/abodh/Neural_Network_Inertia_Estimation
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://ieeexplore.ieee.org/abstract/document/9665387
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""

---