+++
title = "NEAT for Large-Scale Reinforcement Learning through Evolutionary Feature Learning and Policy Gradient Search"
date = 2018-01-17T15:30:31+13:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors =  ["Yiming Peng", "Gang Chen", "Harman Singh", "Mengjie Zhang"]

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
publication = ""
publication_short = "GECCO"

# Abstract and optional shortened version.
abstract = "NeuroEvolution of Augmenting Topology (NEAT) is one of the most successful algorithms for solving traditional reinforcement learning (RL) tasks such as pole-balancing. However, the algorithm faces serious challenges while tackling problems with large state spaces, particularly the Atari game playing tasks. This is due to the major flaw that NEAT aims at evolving a single neural network (NN) that must be able to simultaneously extract high-level state features and select action outputs. However such complicated NNs cannot be easily evolved directly through NEAT. To address this issue, we propose a new reinforcement learning scheme based on NEAT with two key technical advancements: (1) a new three-stage learning scheme is introduced to clearly separate feature learning and policy learning to allow effective knowledge sharing and learning across multiple agents; (2) various policy gradient search algorithms can be seamlessly integrated with NEAT for training policy networks with deep structures to achieve effective and sample efficient RL. Experiments on several Atari games confirm that our new learning scheme can be more effective and has higher sample efficiency than NEAT and three state-of-the-art algorithms from the most recent RL literature."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["Deep Learning", "Reinforcement Learning", "Feature Learning"]

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "c-paper-6.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "https://doi.org/10.1145/3205455.3205536"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
