---
title: "Comparing machine learning algorithms in predicting thermal sensation with ASHRAE Comfort Database II"
authors:
- Maohui Luo
- admin
- Yichen Yan
- ..
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Energy Buildings "
publication_short: ""

abstract: Predicting building occupants’ thermal comfort via machine learning (ML) is a hot research topic. Many algorithms and data processing methods have been applied to predict thermal comfort indices in different contexts. But few studies have systematically investigated how different algorithms and data processing methods can influence the prediction accuracy. In this study, we first summarized the recent literature from perspectives of predicted comfort indices, algorithms applied, input features, data sources, sample size, training proportion, predicting accuracy, etc. Then, we applied nine ML algorithms and three data sampling methods to predict the 3-point and 7-point thermal sensation vote (TSV) in ASHRAE Comfort Database II. The results show that with an accuracy of 66.3% and 61.1% for 3-point and 7-point TSV respectively, Random Forest (RF) has the best performance among the tested algorithms. Compared to the Predicted Mean Vote (PMV) model, ML TSV models generally have higher accuracy in TSV prediction. Based on feature importance analysis, the air temperature, humidity, clothing, air velocity, age, and metabolic rate are the top six important features for TSV prediction. The RF algorithm can achieve 63.6% overall accuracy in TSV prediction with the top three features, which is only 2.6% lower than involving 12 input features. Further, this paper addressed other common considerations in ML comfort model establishment such as tuning hyperparameters, splitting of training and testing data, and encoding methods. We also provided Python and R programming codes and packages as appendixes, which can be a good reference for future studies.


# Summary. An optional shortened abstract.
summary: Supervised machine learning algorithms for predicting human thermal comfort

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.researchgate.net/publication/338538653_Comparing_machine_learning_algorithms_in_predicting_thermal_sensation_with_ASHRAE_Comfort_Database_II
url_code: https://github.com/JIAQING-XIE/UCB-summer-research-2019-at-CBE
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
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
