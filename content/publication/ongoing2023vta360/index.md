+++

title = "VTA360: 360° Head Avatar Generation from Monocular Frontal Videos"
date = 2023-12-24T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "__**David Jones**__"].
authors = ["__**Dai-Jie Wu**__", "Guocheng Qian", "Tingting Liao", "Qian Wang", "Silvio Giancola", "Peter Wonka", "Sergey Tulyakov", "Kfir Aberman", "Hao Li", "Bernard Ghanem"]
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication ="Ongoing Project with Snap and MBZUAI"
publication_short = "*Ongoing Project*"

# Abstract and optional shortened version.
abstract = "Existing video-to-avatar systems predominantly focus on reconstructing head avatars within the field of view of the input videos, which impedes the generation of complete, all-rounded 3D avatars that can render from any novel views. We introduce an innovative framework, video-to-avatar360, to reconstruct a full 360-degree implicit neural head avatar from a single monocular frontal video. We first propose to use the signed distance function extracted from the prior mesh as a condition to the canonical Neural Radiance Field, to provide a coarse clue for the geometry of the full head avatar. We then incorporate a personalized diffusion guidance, DreamBooth-SDS, to optimize the NeRF in the novel views while being identity-preserving. Video-to-Avatar360 enables the generation of photorealistic 360-degree avatars, achieving a substantial performance leap over the state-of-the-art, for both reference-view reconstruction and novel view synthesis."

# Is this a selected publication? (true/false)
selected = true
# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
# Associate this publication with one or more of your projects.
# Simply enter your project's folder or file name without extension.
# E.g. projects = ["deep-learning"] references
# content/project/deep-learning/index.md.
# Otherwise, set projects = [].
projects = []

# Slides (optional).
# Associate this publication with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. slides = "example-slides" references
# content/slides/example-slides.md.
# Otherwise, set slides = "".
slides = ""

# Tags (optional).
# Set tags = [] for no tags, or use the form tags = ["A Tag", "Another Tag"] for one or more tags.
tags = ["AIGC", "3D", "Avatar"]

# Links (optional).

# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form [{...}, {...}, {...}].
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.

[image]  
  # Caption (optional)
  # caption = "123"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
  placement = 2
  # preview_only = true

+++
