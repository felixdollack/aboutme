---
title: "Facial movement synergies and Action Unit detection from distal wearable Electromyography and Computer Vision"
date: 2021-04-30T00:00:00

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01T00:00:00Z'

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
 - M. Perusquia-Hernandez
 - C. K. Tan
 - F. Dollack
 - S. Ayabe-Kanamura
 - K. Suzuki

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types: ["1"]

# Publication name and optional abbreviated version.
publication: "In *Proceedings of 22nd ACM International Conference on Multimodal Interaction*."
publication_short: "In *ICMI*"

# Abstract.
abstract: "Distal facial Electromyography (EMG) can be used to detect smiles and frowns with reasonable accuracy, by capitalizing on volume conduction to detect relevant muscle activity, even when the electrodes are not placed directly on the source muscle. The main advantage of this method is to prevent occlusion and obstruction of the facial expression production, whilst allowing EMG measurements. However, measuring EMG distally entails that the exact source of the facial movement is unknown. We propose a novel method to estimate specific Facial Action Units (AUs) from distal facial EMG and Computer Vision (CV). This method is based on Independent Component Analysis (ICA), Non-Negative Matrix Factorization (NNMF), and sorting of the resulting components to determine which is the most likely to correspond to each CV-labeled action unit (AU). Performance on the detection of AU06 (Orbicularis Oculi, (^-^) and AU12 (Zygomaticus Major, :) ) was estimated by calculating the agreement with Human Coders. The results showed an accuracy of 83%, and a Cohen's Kappa of 0.42 for AU6 and 0.43 for AU12. This demonstrates the potential of distal EMG to detect individual facial movements. Using this multimodal method, several AU synergies were identified. Finally, we also quantified the co-occurrence and timing of AU6 and AU12 in posed and spontaneous smiles."

# Summary. An optional shortened abstract.
summary: ""

# Digital Object Identifier (DOI)
doi: ""

# Is this a featured publication? (true/false)
featured: false

# Tags (optional).
#   Set `tags: []` for no tags, or use the form `tags: ["A Tag", "Another Tag"]` for one or more tags.
tags: ['facial emg', 'action units', 'ICA', 'computer vision', 'NNMF']

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Links (optional).
url_pdf: ""
url_preprint: ""
url_code: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: ""
url_source: ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links: [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # Caption (optional)
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: ""

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
slides: ''
---
