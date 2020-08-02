---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Joint Patch and Instance Discrimination Learning for Unsupervised Person Re-identiﬁcation"
authors: [Yu Zhao, Keren Fu, Qiaoyuan Shu, Pengcheng Wei, Jian Zhan]
date: 2020-08-02T06:39:51+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-02T06:39:51+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Image and Vision Computing"
publication_short: "IVC"

abstract: "The unsupervised person re-identification (re-ID) has become increasingly significant in the community because it is more scalable than the supervised method when dealing with the large-scale person re-ID. However, it is difficult to learn discriminative enough features from across-camera images without labelling information. To address this problem, we propose a joint patch and instance discrimination learning (JPIL) framework for the unsupervised person re-ID. The JPIL framework exploits a patch feature extraction model to generate patch-wise features for each input image. Then the patch discrimination learning (PDL) loss is designed to guide the model to mine the patch-wise discriminative information from unlabelled person image patches. On the other hand, we introduce the instance discrimination learning (IDL) loss to provide instance-wise supervision. The IDL loss aims to pull features of the same instance under different transformations closer and push features belonging to different instances away. Finally, we combine the PDL and IDL loss to apply the joint training. Extensive experiments on Market-1501 and DukeMTMC-reID datasets demonstrate the effectiveness of the proposed method for unsupervised person re-ID."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
