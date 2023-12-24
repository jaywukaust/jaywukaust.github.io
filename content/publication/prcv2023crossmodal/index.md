+++

title = "Cross-Modal and Cross-Domain Knowledge Transfer for Label-Free 3D Segmentation"
date = 2023-09-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "__**David Jones**__"].
authors = ["Jingyu Zhang", "Huitong Yang", "__**Dai-Jie Wu**__", "Jacky Keung", "Xuesong Li", "Xinge Zhu", "Yuexin Ma"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication ="Chinese Conference on Pattern Recognition and Computer Vision (PRCV), 2023"
publication_short = "*PRCV'23*"

# Abstract and optional shortened version.
abstract = "Current state-of-the-art point cloud-based perception methods usually rely on large-scale labeled data, which requires expensive manual annotations. A natural option is to explore the unsupervised methodology for 3D perception tasks. However, such methods often face substantial performance-drop difficulties. Fortunately, we found that there exist amounts of image-based datasets and an alternative can be proposed, i.e., transferring the knowledge in the 2D images to 3D point clouds. Specifically, we propose a novel approach for the challenging cross-modal and cross-domain adaptation task by fully exploring the relationship between images and point clouds and designing effective feature alignment strategies. Without any 3D labels, our method achieves state-of-the-art performance for 3D point cloud semantic segmentation on SemanticKITTI by using the knowledge of KITTI360 and GTA5, compared to existing unsupervised and weakly-supervised baselines."

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
tags = ["LiDAR Segmentation", "Domain Adaptation", "Label-efficient"]

# Links (optional).
url_pdf = "https://link.springer.com/chapter/10.1007/978-981-99-8435-0_37"
url_preprint = "https://arxiv.org/abs/2309.10649"


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
