---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Sihem Belabbes
  - Salem Benferhat

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-09-24T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-031-43619-2_25'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 18th European Conference on Logics in Artificial Intelligence 2023, Dresden, Germany, September 20–22, 2023
publication_short: In JELIA 2023

abstract: Inconsistency in formal ontologies is usually addressed by computing repairs for the dataset. There are several strategies for selecting the repairs used to evaluate queries, with various levels of cautiousness and classes of computational complexity. This paper deals with inconsistent partially ordered lightweight ontologies. It introduces a new method that goes beyond the cautious strategies and that is tractable in the possibilistic setting, where uncertainty concerns only the data pieces. The proposed method, called C{\$}{\$}{\backslash}pi {\$}{\$}$\pi$-repair, proceeds as follows. It first interprets the partially ordered dataset as a family of totally ordered datasets. Then, it computes a single data repair for every totally ordered possibilistic ontology induced from the partially ordered possibilistic ontology. Next, it deductively closes each of these repairs in order to increase their productivity, without introducing conflicts or arbitrary data pieces. Finally, it intersects the closed repairs to obtain a single data repair for the initial ontology. The main contribution of this paper is an equivalent characterization that does not enumerate all the total orders, but also does not suffer from the additional computational cost naturally incurred by the deductive closure. We establish the tractability of our method by reformulating the problem using the notions of dominance and support. Intuitively, the valid conclusions are supported against conflicts by consistent inclusion-minimal subsets of the dataset that dominate all the conflicts. We also study the rationality properties of our method in terms of unconditional and conditional query-answering.

# Summary. An optional shortened abstract.
# summary: Inconsistency in formal ontologies is usually addressed by computing repairs for the dataset. There are several strategies for selecting the repairs used to evaluate queries, with various levels of cautiousness and classes of computational complexity. This paper deals with inconsistent partially ordered lightweight ontologies. It introduces a new method that goes beyond the cautious strategies and that is tractable in the possibilistic setting, where uncertainty concerns only the data pieces. The proposed method, called C{\$}{\$}{\backslash}pi {\$}{\$}$\pi$-repair, proceeds as follows. It first interprets the partially ordered dataset as a family of totally ordered datasets. Then, it computes a single data repair for every totally ordered possibilistic ontology induced from the partially ordered possibilistic ontology. Next, it deductively closes each of these repairs in order to increase their productivity, without introducing conflicts or arbitrary data pieces. Finally, it intersects the closed repairs to obtain a single data repair for the initial ontology. The main contribution of this paper is an equivalent characterization that does not enumerate all the total orders but also does not suffer from the additional computational cost naturally incurred by the deductive closure. We establish the tractability of our method by reformulating the problem using the notions of dominance and support. Intuitively, the valid conclusions are supported against conflicts by consistent inclusion-minimal subsets of the dataset that dominate all the conflicts. We also study the rationality properties of our method in terms of unconditional and conditional query-answering.

tags:
  - JELIA 2023

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://univ-artois.hal.science/hal-04270643/file/Jelia2023.pdf'
url_code: 'https://github.com/ahmedlaouar/py_reasoner'
# url_slides: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](ahmedlaouar.me)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

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

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
