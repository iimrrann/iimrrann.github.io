---
title: "Beyond Binary: Multimodal Fusion for Fine-Grained Fake News Classification and Benchmarking"
authors:
-  Md. Imran Khan
-  Dr. Ahmed wasif Reza
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: " "

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Artificial Intelligence Research* (Under Review)"
publication_short: "JAIR (Under Review)"

abstract: The rapid proliferation of fake news across digital platforms threatens public trust, social stability, and democratic pro-
 cesses, causing billions of dollars in political, economic, and societal damage each year. Traditional detection methods,
 reliant on manual fact-checking or unimodal (text-only or image-only) models, fail to capture the nuanced, multimodal
 nature of modern misinformation. This study addresses that gap by developing a robust multimodal fake news detection
 framework that fuses textual, visual, and metadata signals for holistic analysis. Leveraging the large-scale Fakeddit
 dataset and a curated balanced subset (EquiFakeddit83 ), we systematically evaluate diverse fusion strategies, including
 early fusion, late fusion (logit-level, cross-attention, dual cross-attention), tensor-based fusion, mixture-of-experts, hierar-
 chical fusion, and a novel Dynamic Tensor Fusion mechanism. Pre-trained encoders—CLIP for text and ViT/CLIP
 for images—serve as modality backbones, while fusion modules integrate their representations for fine-grained 6-way
 classification covering satire, false connection, manipulated, misleading, imposter content, and true news. Experimental
 results demonstrate that Dynamic Tensor Fusion achieves the strongest performance (Accuracy: 87.92%, Macro F1:
 87.79%), surpassing the widely used BERT + ResNet-50 benchmark on Fakeddit by +2% absolute accuracy. Cross-
 dataset validation on our curated FakeThroughPrism benchmark further confirms the robustness of cross-attention and
 tensor-based models, though challenges remain in transferability. The findings highlight that carefully designed fusion
 strategies are crucial for capturing cross-modal inconsistencies and advancing beyond binary fake vs. real detection. This
 work not only establishes a new state-of-the-art for multimodal misinformation detection but also provides a practical
 foundation for real-world systems supporting journalists, fact-checkers, and social media platforms in combating online
 disinformation.

# Summary. An optional shortened abstract.
summary: Advanced multimodal fusion framework integrating text and image modalities for fake news detection, achieving 88% accuracy through comprehensive benchmarking of fusion strategies.


tags:
  - Multimodal AI
  - Fake News Detection
  - Transformer Models
  - Computer Vision
  - Natural Language Processing
  - Multimodal Fusion
featured: true

hugoblox:
  ids:
    arxiv: 1512.04133v1

links:
  - type: pdf
    url: http://arxiv.org/pdf/1512.04133v1
  - type: code
    url: https://github.com/HugoBlox/hugo-blox-builder
  - type: dataset
    url: ""
  - type: poster
    url: ""
  - type: project
    url: ""
  - type: slides
    url: https://www.slideshare.net/
  - type: source
    url: ""
  - type: video
    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

> [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
