---
title: 'Boosting the intelligibility of waveform speech enhancement networks through self-supervised representations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tao Sun
  - Shuyu Gong
  - Zhewei Wang
  - Charles D Smith 
  - Xianhui Wang
  - Li Xu
  - Jundong Liu

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In ICMAL 2021
publication_short: In ICMAL 2021

abstract: The ultimate goal of speech enhancement is to improve speech quality and intelligibility. Integrating human speech elements into waveform denoising neural networks has proven to be a simple yet effective strategy for this purpose. Such integration, however, has mostly been carried out within supervised learning settings, without taking advantage of the power of the latest self-supervised learning models, which have demonstrated remarkable capability of extracting knowledge from large training sets. In this paper, we present K-SENet, a knowledge-assisted waveform framework for speech enhancement. Wave-U-Net is utilized as the baseline model and the foundation to build our framework. To achieve enhanced intelligibility, we propose a perceptual loss function that relies on self-supervised speech representations pretrained on large datasets, to provide guidance for the baseline network. Wav2vec and PASE are the choices of self-supervised models in this work. Our proposed perceptual loss is calculated upon the perceptual similarities captured by the speech representations. Minimizing this loss would ensure the denoised network outputs sound like clean human speeches. Experiments on the Noisy VCTK and modified TIMIT datasets demonstrate that our K-SENet can significantly improve the perceptual quality of network outputs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/publication/357355747_Boosting_the_Intelligibility_of_Waveform_Speech_Enhancement_Networks_through_Self-supervised_Representations#fullTextFileContent'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
