---
title: "Towards Automated Infographic Design: Deep Learning-based Auto-Extraction of Extensible Timeline"
authors: 
  - zhutianchen
  - yunwang
  - qianwenwang
  - yongwang
  - huaminqu
date: "2019-08-20"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Visualization and Computer Graphics (InfoVis)"
publication_short: ""

abstract: "Designers need to consider not only perceptual effectiveness but also visual styles when creating an infographic. This process can be difficult and time consuming for professional designers, not to mention non-expert users, leading to the demand for automated infographics design. As a first step, we focus on timeline infographics, which have been widely used for centuries. We contribute an end-to-end approach that automatically extracts an extensible timeline template from a bitmap image. Our approach adopts a deconstruction and reconstruction paradigm. At the deconstruction stage, we propose a multi-task deep neural network that simultaneously parses two kinds of information from a bitmap timeline: 1) the global information, i.e., the representation, scale, layout, and orientation of the timeline, and 2) the local information, i.e., the location, category, and pixels of each visual element on the timeline. At the reconstruction stage, we propose a pipeline with three techniques, i.e., Non-Maximum Merging, Redundancy Recover, and DL GrabCut, to extract an extensible template from the infographic, by utilizing the deconstruction results. To evaluate the effectiveness of our approach, we synthesize a timeline dataset (4296 images) and collect a real-world timeline dataset (393 images) from the Internet. We first report quantitative evaluation results of our approach over the two datasets. Then, we present examples of automatically extracted templates and timelines automatically generated based on these templates to qualitatively demonstrate the performance. The results confirm that our approach can effectively extract extensible templates from real-world timeline infographics."

# Summary. An optional shortened abstract.
# summary: 

tags:
featured: false

links:
- name: Project Page
  url: https://chenzhutian.org/auto-infog-timeline/
- name: Supplementary
  url: https://chenzhutian.org/projects/2019_autotimeline/supplement.pdf
url_pdf: https://chenzhutian.org/projects/2019_autotimeline/paper.pdf
url_code: https://github.com/chenzhutian/auto-infog-timeline
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
slides:
---