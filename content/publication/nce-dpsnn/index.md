---
title: "DPSNN: Spiking neural network for low-latency streaming speech enhancement"
authors:
- Tao Sun
- Sander Bohté
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-11-18T00:00:00Z"
doi: "10.1088/2634-4386/ad93f9"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Neuromorphic Computing and Engineering, 4*(4)"
# publication_short: "NCE"

abstract: Speech enhancement improves communication in noisy environments, affecting areas such as automatic speech recognition, hearing aids, and telecommunications. With these domains typically being power-constrained and event-based, and often requiring low latency, neuromorphic algorithms -- particularly spiking neural networks (SNNs) -- hold significant potential. However, current effective SNN solutions require a long temporal window to calculate Short Time Fourier Transforms (STFTs) and thus impose substantial latency, typically around 32 ms, which is too long for applications such as hearing aids. Inspired by the Dual-path Recurrent Neural Networks (DPRNN) in deep neural networks (DNNs), we develop a two-phase time-domain streaming SNN framework for speech enhancement, named Dual-Path Spiking Neural Network (DPSNN). DPSNNs achieve low latency by replacing the STFT and inverse STFT (iSTFT) in traditional frequency-domain models with a learned convolutional encoder and decoder. In the DPSNN, the first phase uses Spiking Convolutional Neural Networks (SCNNs) to capture temporal contextual information, while the second phase uses Spiking Recurrent Neural Networks (SRNNs) to focus on frequency-related features. In addition, threshold-based activation suppression, along with L_1 regularization loss, is applied to specific non-spiking layers in DPSNNs to further improve their energy efficiency. Evaluating on the VCTK Corpus and Intel N-DNS Challenge dataset, our approach demonstrates excellent performance in speech objective metrics, along with the very low latency (approximately 5 ms) required for applications like hearing aids.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://iopscience.iop.org/article/10.1088/2634-4386/ad93f9/pdf
url_code: 'https://github.com/tao-sun/dpsnn'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
