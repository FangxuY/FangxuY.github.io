---
title: 'UVLens: Urban Village Boundary Identification and Population Estimation Leveraging Open Government Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Longbiao Chen
  - Chenhui Lu
  - admin
  - Zhihan Jiang
  - Leye Wang
  - Daqing Zhang
  - Ruixiang Luo
  - Xiaoliang Fan
  - Cheng Wang*

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2021-06-21T00:00:00Z'
doi: '10.1145/3463495'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-06-21T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies*"
publication_short: "*IMWUT*"

abstract: Urban villages refer to the residential areas lagging behind the rapid urbanization process in many developing countries. These areas are usually with overcrowded buildings, high population density, and low living standards, bringing potential risks of public safety and hindering the urban development. Therefore, it is crucial for urban authorities to identify the boundaries of urban villages and estimate their resident and floating populations so as to better renovate and manage these areas. Traditional approaches, such as field surveys and demographic census, are time consuming and labor intensive, lacking a comprehensive understanding of urban villages. Against this background, we propose a two-phase framework for urban village boundary identification and population estimation. Specifically, based on heterogeneous open government data, the proposed framework can not only accurately identify the boundaries of urban villages from large-scale satellite imagery by fusing road networks guided patches with bike-sharing drop-off patterns, but also accurately estimate the resident and floating populations of urban villages with a proposed multi-view neural network model. We evaluate our method leveraging real-world datasets collected from Xiamen Island. Results show that our framework can accurately identify the urban village boundaries with an IoU of 0.827, and estimate the resident population and floating population with R2 of 0.92 and 0.94 respectively, outperforming the baseline methods. We also deploy our system on the Xiamen Open Government Data Platform to provide services to both urban authorities and citizens.

# Summary. An optional shortened abstract.
summary: Urban Village Boundary Identification and population estimation

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3463495'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
