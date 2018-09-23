
+++
title = "Distributed model predictive control for consensus of sampled-data multi-agent systems with double-integrator dynamics"
date = 2017-01-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Lifeng Zhou", "Shaoyuan Li"]`.
authors = ["[*Journal*] <b>Lifeng Zhou</b>", "Shaoyuan Li"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *International Journal of Robust and Nonlinear Control*"
publication_short = "In *IJRNC*"

# Abstract and optional shortened version.
abstract = "This study presents a distributed model predictive control (MPC) strategy to achieve flocking of multi‐agent systems. Based on the relative motion between each pair of neighboring agents, we introduce a neighbor screening protocol, by which each agent only focuses on its neighbors, which have the relative motion that violates the formation of flocks. Then, a truly distributed MPC flocking algorithm (Algorithm 1) is designed with consideration of neighbor screening mechanism. Specifically, at each sampling instant, each agent monitors the information in the networked system, finds its neighbors to form its subsystem, determines the screened neighbor set, and optimizes its plan by collecting the position states within the screened subsystem. And geometric properties of the optimal path are used to guarantee the formation of the flock without inter‐agent collision. Finally, the performance and advantage of the proposed distributed MPC flocking strategy are vividly verified by the simulation results."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://onlinelibrary.wiley.com/doi/epdf/10.1002/rnc.3606"
# url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
# url_code = "#"
# url_dataset = "#"
# url_project = "#"
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
