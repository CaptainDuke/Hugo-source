+++
title = "Image-based action recognition using hint-enhanced deep neural networks"
date = 2017-06-27T19:54:24+08:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Tangquan Q.", "Yong X.", "Yuhui Q.", "Yaodong W.", "Haibin L."]

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
publication = "In Sci. Journal *Neurocomputing*"
publication_short = ""

# Abstract and optional shortened version.
abstract = "While human action recognition from still images finds wide applications in computer vision, it remains a very challenging problem. Compared with video-based ones, image-based action representation and recognition are impossible to access the motion cues of action, which largely increases the difficulties in dealing with pose variances and cluttered backgrounds. Motivated by the recent success of convolutional neural networks (CNN) in learning discriminative features from objects in the presence of variations and backgrounds, we investigate the potentials of CNN in image-based action recognition. "
abstract_short = " Image-based action recognition task, using CNN networks"

# Featured image thumbnail (optional)
image_preview = "headers/image-based-preview.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "files/Image-based_paper.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = "https://www.sciencedirect.com/science/article/pii/S0925231217311694"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
url_custom = [{name = "Haibin Ling", url = "http://www.dabi.temple.edu/~hbling/"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]

image = "headers/image-based-preview.png"
caption = "Overview of our proposed method. Left: data augmentation strategy. Top-right: auxiliary feature extraction for the pose hint task. Bottomright: the proposed deep neural network."

+++

# Detials
The new action recognition method is proposed by implicitly integrating pose hints into the CNN framework, i.e., we use a CNN originally learned for object recognition as a base network and then transfer it to action recognition by training the base network jointly with inference of poses. Such a joint training scheme can guide the network towards pose inference and meanwhile prevent the unrelated knowledge inherited from the base network. For further performance improvement, the training data is augmented by enriching the pose-related samples. The experimental results on three benchmark datasets have demonstrated the effectiveness of our method.

Notes:   &nbsp; *Dr. Tangquan Q.* and I took charge of main parts of the codes implemention and model deployment. *Prof. Yong X.* and *Associate Prof. Yuhui Q.* are both supervisors of Dr. Tangquan, giving macroscopic instructions.  *Associate Prof. Haibin Ling* as visiting professor of SCUT, mainly provided remote instruction from USA.
