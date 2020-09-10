---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Using multiple data streams to estimate and forecast SARS-CoV-2 transmission
  dynamics, with application to the virus spread in Orange County, California
subtitle: ''
summary: ''
authors:
- Jonathan Fintzi
- damon
- Isaac Goldstein
- Keith Lumbard
- Emily Ricotta
- Sarah Warner
- Lindsay M. Busch
- Jeffrey R. Strich
- Daniel S. Chertow
- Daniel M. Parker
- Bernadette Boden-Albala
- Alissa Dratch
- Richard Chhuon
- Nichole Quick
- Matthew Zahn
- Vladimir N. Minin
tags:
- '"Quantitative Biology - Populations and Evolution"'
- '"Statistics - Applications"'
categories: []
date: '2020-09-01'
lastmod: 2020-09-10T16:05:33-07:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-09-10T23:05:32.861617Z'
publication_types: ["3"]
abstract: Near real-time monitoring of outbreak transmission dynamics and evaluation
  of public health interventions are critical for interrupting the spread of the novel
  coronavirus (SARS-CoV-2) and mitigating morbidity and mortality caused by coronavirus
  disease (COVID-19). Formulating a regional mechanistic model of SARS-CoV-2 transmission
  dynamics and frequently estimating parameters of this model using streaming surveillance
  data offers one way to accomplish data-driven decision making. For example, to detect
  an increase in new SARS-CoV-2 infections due to relaxation of previously implemented
  mitigation measures one can monitor estimates of the basic and effective reproductive
  numbers. However, parameter estimation can be imprecise, and sometimes even impossible,
  because surveillance data are noisy and not informative about all aspects of the
  mechanistic model, even for reasonably parsimonious epidemic models. To overcome
  this obstacle, at least partially, we propose a Bayesian modeling framework that
  integrates multiple surveillance data streams. Our model uses both COVID-19 incidence
  and mortality time series to estimate our model parameters. Importantly, our data
  generating model for incidence data takes into account changes in the total number
  of tests performed. We apply our Bayesian data integration method to COVID-19 surveillance
  data collected in Orange County, California. Our results suggest that California
  Department of Public Health stay-at-home order, issued on March 19, 2020, lowered
  the SARS-CoV-2 effective reproductive number $R_e$ in Orange County below 1.0, which
  means that the order was successful in suppressing SARS-CoV-2 infections. However,
  subsequent \"re-opening\" steps took place when thousands of infectious individuals
  remained in Orange County, so $R_e$ increased to approximately 1.0 by mid-June and
  above 1.0 by mid-July.
publication: '*arXiv:2009.02654 [q-bio, stat]*'
links:
- name: arXiv
  url: http://arxiv.org/abs/2009.02654
  icon_pack: ai
  icon: arxiv
url_pdf: http://arxiv.org/pdf/2009.02654
---
