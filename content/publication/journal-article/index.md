---
title: "How to tractably compute a productive repair for possibilistic partially ordered DL-Lite_R ontologies?"
authors:
- admin
- Sihem Belabbes
- Salem Benferhat

author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2025-06-15T00:00:00Z"
doi: "https://doi.org/10.1016/j.fss.2025.109361"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Fuzzy Sets and Systems"
publication_short: "In FSS"

abstract: The lightweight description logic dialect DL-LiteR offers a framework for specifying and reasoning with formal inconsistent ontologies. Basically, an ontology is a knowledge base composed of a TBox, modelling conceptual knowledge of some domain of interest, and an ABox, asserting factual knowledge about specific entities of the domain. Inconsistency in an ontology is usually handled by evaluating queries over maximal conflict-free subsets of the ABox, called data repairs. Several inconsistency-tolerant semantics, with different levels of cautiousness and computational cost, propose strategies for selecting the repairs to consider when deriving new conclusions from an inconsistent ontology. In this paper, we focus on partially ordered ontologies where a partial order relation captures the reliability levels of the ABox elements. We propose a new tractable method, called “Cπ-repair”, which leverages possibility theory in repairing a partially ordered ABox. It proceeds in four steps as follows. First, the partial order relation is extended into a family of total orders, thus inducing as many compatible totally ordered ABoxes. Second, a single repair is computed for each compatible ABox. Third, these repairs are closed deductively in order to improve their productivity, i.e., to derive more facts. Finally, the closed repairs are intersected to produce a single repair for the initial partially ordered ABox. The main contribution of this paper is an equivalent characterization that determines the validity of the conclusions drawn with the “Cπ-repair” method, but without eliciting the compatible ABoxes or computing their repairs. This allows us to establish the tractability of the method by reformulating the problem using the notions of support for an assertion and dominance over the conflicts that arise between the ABox elements. Essentially, the valid conclusions are those derived from the supports that dominate all conflicts. In the last part of the paper, we explore the rationality properties of our method. We show that increasing repair productivity does not alter the satisfaction of the rationality properties. We also discuss the applicability of our proposed method to languages richer than DL-LiteR and to other inconsistency-tolerant semantics.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- FSS 2025
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://doi.org/10.1016/j.fss.2025.109361"
url_code: ''
#url_source: ''

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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
