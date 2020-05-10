---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep multiple instance learning for automatic detection of diabetic retinopathy in retinal images"
authors: [Lei Zhou, Yu Zhao, Jie Yang, Qi Yu, Xun Xu]
date: 2018-03-22T13:45:54+08:00
doi: "10.1049/iet-ipr.2017.0636"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-05-10T13:45:54+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IET Image Processing"
publication_short: ""

abstract: "As a weakly supervised learning technique, multiple instance learning (MIL) has shown an advantage over supervised learning methods for automatic detection of diabetic retinopathy (DR): only the image-level annotation is needed to achieve both detection of DR images and DR lesions, making more graded and de-identified retinal images available for learning. However, the performance of existing studies on this technique is limited by the use of handcrafted features. The authors propose a deep MIL method for DR detection, which jointly learns features and classifiers from data and achieves a significant improvement on detecting DR images and their inside lesions. Specifically, a pre-trained convolutional neural network is adapted to achieve the patch-level DR estimation, and then global aggregation is used to make the classification of DR images. Further, the authors propose an end-to-end multi-scale scheme to better deal with the irregular DR lesions. For detection of DR images, they achieve an area under the ROC curve of 0.925 on a subset of a Kaggle dataset, and 0.960 on Messidor. For detection of DR lesions, they achieve an F1-score of 0.924 with sensitivity 0.995 and precision 0.863 on DIARETDB1 using the connected component-level validation."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

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
