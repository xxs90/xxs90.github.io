---
title: 'On Robot Grasp Learning Using Equivariant Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xupeng Zhu
  - Dian Wang
  - Guanang Su
  - Ondrej Biza
  - Robin Walters
  - Robert Platt

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-07-04'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In ***Autonomous Robots***, 04 July 2023
publication_short: In **Autonomous Robots 2023** 


abstract: Real-world grasp detection is challenging due to the stochasticity in grasp dynamics and the noise in hardware. Ideally, the system would adapt to the real world by training directly on physical systems. However, this is generally difficult due to the large amount of training data required by most grasp learning models. In this paper, we note that the planar grasp function is SE(2)-equivariant and demonstrate that this structure can be used to constrain the neural network used during learning. This creates an inductive bias that can significantly improve the sample efficiency of grasp learning and enable end-to-end training from scratch on a physical robot with as few as 600 grasp attempts. We call this method Symmetric Grasp learning (SymGrasp) and show that it can learn to grasp “from scratch” in less that 1.5 h of physical robot time. This paper represents an expanded and revised version of the conference paper Zhu et al. (2022).

# summary: 

tags: [manipulation, learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project Page
  url: https://zxp-s-works.github.io/equivariant_grasp_site/

url_pdf: 'https://arxiv.org/pdf/2306.06489.pdf'
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
