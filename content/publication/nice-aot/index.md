---
title: "Average-Over-Time Spiking Neural Networks for Uncertainty Estimation in Regression"
authors:
  - Tao Sun
  - Sander Bohté
date: "2024-11-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract:  Uncertainty estimation is a standard tool to quantify the reliability of modern deep learning models, and crucial for many real-world applications. However, efficient uncertainty estimation methods for spiking neural networks, particularly for regression models, have been lacking. Here, we introduce two methods that adapt the Average-Over-Time Spiking Neural Network (AOT-SNN) framework to regression tasks, enhancing uncertainty estimation in event-driven models. The first method uses the heteroscedastic Gaussian approach, where SNNs predict both the mean and variance at each time step, thereby generating a conditional probability distribution of the target variable. The second method leverages the Regression-as-Classification (RAC) approach, reformulating regression as a classification problem to facilitate uncertainty estimation. We evaluate our approaches on both a toy dataset and several benchmark datasets, demonstrating that the proposed AOT-SNN models achieve performance comparable to or better than state-of-the-art deep neural network methods, particularly in uncertainty estimation. Our findings highlight the potential of SNNs for uncertainty estimation in regression tasks, providing an efficient and biologically inspired alternative for applications requiring both accuracy and energy efficiency.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

# links:
# - name: Custom Link
  # url: https://arxiv.org/abs/2304.10191
url_pdf: 'https://arxiv.org/pdf/2412.00278'
# url_code: ''
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
