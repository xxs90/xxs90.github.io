---
title: 'Sample Efficient Grasp Learning Using Equivariant Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xupeng Zhu
  - Dian Wang
  - Ondrej Biza
  - Guanang Su
  - Robin Walters
  - Robert Platt

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-27'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In ***Robotics Science and Systems 2022***, New York City, New York, USA & (***Workshop on Scaling Robot Learning, ICRA 2022*** & ***RLDM 2022***) 
publication_short: In **RSS 2022** (also presented in ***ICRA 2022 Workshop*** & ***RLDM 2022***)


abstract: In planar grasp detection, the goal is to learn a function from an image of a scene onto a set of feasible grasp poses in SE(2). In this paper, we recognize that the optimal grasp function is SE(2)-equivariant and can be modeled using an equivariant convolutional neural network. As a result, we are able to significantly improve the sample efficiency of grasp learning, obtaining a good approximation of the grasp function after only 600 grasp attempts. This is few enough that we can learn to grasp completely on a physical robot in about 1.5 hours. **Project page with more details at https://zxp-s-works.github.io/equivariant_grasp_site/.**

# summary: 

tags: [manipulation, learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project Page
  url: https://zxp-s-works.github.io/equivariant_grasp_site/

url_pdf: 'https://arxiv.org/pdf/2202.09468.pdf'
url_code: 'https://github.com/ZXP-S-works/SE2-equivariant-grasp-learning'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=0jaHpz3KQ7I&t=1s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: true

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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
