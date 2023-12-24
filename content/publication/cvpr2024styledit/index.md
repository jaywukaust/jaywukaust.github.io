+++

title = "StyleDiT: A Unified Framework for Diverse Kinship Faces Synthesis with Style Latent Diffusion Transformer"
date = 2023-12-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "__**David Jones**__"].
authors = ["Pin-Yen Chiu*", "__**Dai-Jie Wu***__", "Chia-Hsuan Hsu", "Hsiang-Chen Chiu", "Chih-Yu Wang", "Jun-Cheng Chen"]

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
publication = "IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2024), Under Review"
publication_short = "*CVPR'2024 Under Review*"

# Abstract and optional shortened version.
abstract = "Kinship face synthesis is a challenging and ill-posed problem due to a scarce amount of available kinship data and low quality. To address these issues, we propose the Style Latent Diffusion Transformer (StyleDiT), a novel framework to integrate the strengths of StyleGAN with the diffusion model to generate high-fidelity and diverse kinship faces, where StyleGAN is responsible for final face generation and our conditional diffusion model is used to sample a StyleGAN latent adhering to the characteristics of condition images. Another key innovation of our work is the Relational Trait Guidance (RTG) mechanism, a Classifier-Free Guidance approach for our diffusion transformer. RTG enables independent control of influencing conditions, such as each parent's facial image, allowing for a fine-grained control between diversity and fidelity in the synthesized faces. This flexibility is crucial for applications requiring specific attribute emphasis. Furthermore, this research extends its application to an unexplored domain: predicting a partner's facial features by synthesizing the combined imagery of a child and one parent. Finally, through extensive quantitative, qualitative, and subject evaluations, StyleDiT demonstrates superior performance in synthesizing diverse and high-fidelity kinship faces compared to existing methods."

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
tags = ["Kinship Face Generation", "Transformer", "Diffusion", "StyleGAN"]

# Links (optional).


# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form [{...}, {...}, {...}].
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

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
