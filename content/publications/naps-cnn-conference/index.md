---
title: 'Convolutional neural network-based inertia estimation using local frequency measurements'
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

date: '2021-06-21T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-28T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2020 52nd North American Power Symposium (NAPS)
# publication_short: In *ICW*

abstract: Increasing installation of renewable energy resources makes the power system inertia a time-varying quantity. Furthermore, converter-dominated grids have different dynamics compared to conventional grids and therefore estimates of the inertia constant using existing dynamic power system models are unsuitable. In this paper, a novel inertia estimation technique based on convolutional neural networks that use local frequency measurements is proposed. The model uses a non-intrusive excitation signal to perturb the system and measure frequency using a phase-locked loop. The estimated inertia constants, within 10% of actual values, have an accuracy of 97.35% and root mean square error of 0.2309. Furthermore, the model evaluated on unknown frequency measurements during the testing phase estimated the inertia constant with a root mean square error of 0.1763. The proposed model-free approach can estimate the inertia constant with just local frequency measurements and can be applied over traditional inertia estimation methods that do not incorporate the dynamic impact of renewable energy sources.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Renewable energy sources
  - Power system dynamics
  - Parameter Estimation
  - Transfer functions
  - Frequency measurement
  - Convolutional neural networks

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/NAPS50074.2021.9449814

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
  #   url: https://ieeexplore.ieee.org/document/9449814
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