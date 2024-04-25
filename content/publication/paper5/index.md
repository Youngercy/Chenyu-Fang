---
title: "HDCBC: A Robust Clustering Algorithm for data with Noise, Heterogeneous Densities, and Weak Connectivity. (Under Review)"
authors:
- Fang, C.*
- Zhou, L.
- Liu, S.
- Chen, R.
- Liu, X.
- Werner, M
date: "2023-04-07T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Submission to *International Journal of Geographical Information Science* **(Under Review)**"
publication_short: ""

abstract: This study introduces the Hierarchy Direction Centrality Based Clustering (HDCBC), a novel algorithm that integrates core point identiﬁcation and hierarchical clustering to address challenges of weak connectivity and heterogeneous density in spatial data analysis. HDCBC utilizes a Gaussian Mixture Model (GMM) for isolating edge points and noise, ensuring stability even under weak connectivity and heterogeneous densities. A unique feature of HDCBC is the Directional Connectivity Measure (DCM), which distinguishes internal from peripheral points, focusing on internal points to minimize the impact of weak connections, unlike conventional CDC methods that emphasize boundary creation. This approach is complemented by the use of k-nearest neighbors (KNNs) to mitigate the eﬀects of varying densities. HDCBC’s eﬀectiveness was validated against baseline methods across 16 synthetic datasets, including noise-enhanced versions, and further applied to ﬁve real-world datasets to demonstrate its adaptability in handling high-dimensional data. This paper details HDCBC’s operational aspects, presents comparative analyses, discusses hyperparameter inﬂuences, and explores future applications and limitations. The ﬁndings oﬀer signiﬁcant contributions to spatial data analysis, highlighting HDCBC’s robustness in noise management and its potential in various applications.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Topic3
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

