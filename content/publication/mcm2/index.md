---
title: "Research on the Development of Wordle based on LSTM and XGBoost"
authors:
- Chen, D.
- Ni, S.
- Deng, D.
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2023-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference"]

# Publication name and optional abbreviated publication name.
publication: "In 2023 *2nd International Conference on Data Analytics, Computing and Artificial Intelligence (ICDACAI)*, p. 2171. IEEE"
publication_short: ""

abstract: 'In order to predict the number of results reported on March 1, 2023, this study first selects the LSTM algorithm for model training according to the number of reports per day. LSTM is an improved recurrent neural network, which can solve the problem of long-distance dependence which can not be handled by other neural networks. In this study, the processing data of the reported scores of the model were trained and the number was predicted by iterative method until March 1 (2023). After 150 times of independent model training, the prediction interval is [20745.72 22914.74]. In addition, from the linear regression of the proportion of hard patterns and lexical attributes, this study also found that there was no correlation between the proportion of hard patterns and target words. Model II: in order to obtain the percentage distribution of specific words with a given date, seven independent XGBoost models were trained in this study. The R2 of the model is 0.68, which can be predicted accurately and the uncertainty is low. In this paper, "weird" is applied to the model, and a predicted percentage distribution is obtained, indicating that Errie should be regarded as a problematic word.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
