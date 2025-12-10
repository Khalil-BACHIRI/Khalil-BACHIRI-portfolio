------
title: "Multi-View Clustering Using Sparse Non-Negative Matrix Factorization for Recommendation Systems"
authors:
- Khalil BACHIRI
- Maria MALEK
- Nicoleta ROGOVSCHI
- Ali YAHYAOUY
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-12-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Machine Learning and Applications (ICMLA), 2023"
publication_short: ""

abstract: Real-world datasets often comprise multiple views or representations, such as user profiles, comments, and preferences. Integrating information from these multi-view datasets can significantly enhance recommendation performance. Consequently, several multi-view clustering (MVC) approaches have been proposed and extensively applied to exploit the compatibility of diverse data sources. Among these methods, Non-negative Matrix Factorization (NMF) has garnered significant attention due to its ability to process high-dimensional data. However, most NMF-based MVC methods suffer from two critical drawbacks the similarity matrices constructed using traditional methods fail to fully exploit neighborhood information among data points, and they are highly sensitive to noise, missing values, and outliers. Additionally, existing NMF-based clustering methods often do not generate sparse coefficient matrices, leading to suboptimal data representation based on the basis matrix. To address these challenges and enhance the accuracy and efficiency of recommendation algorithms, we propose a novel approach called Multi-View Clustering based on Sparse Non-Negative Matrix Factorization (MVC-SNMF). This method leverages the manifold structure of multi-view data and incorporates a sparsity constraint to effectively handle noise while preserving the geometric structure. Furthermore, we introduce a sparsity constraint on the rows of the coefficient matrix to enhance the visibility of clustering structures. To efficiently solve the proposed non-convex optimization problem, we devise an iterative update scheme. Our experimental results on real datasets from Last.fm and Yelp demonstrate the effectiveness of our approach in improving clustering performance, surpassing most existing clustering algorithms. The proposed method not only enhances the clustering accuracy but also exhibits robustness to noise and missing values, making it a promising solution for practical recommendation systems.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:

featured: false


# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10459923
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

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


