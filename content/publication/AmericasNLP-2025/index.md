---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A hybrid Approach to low-resource machine translation for Ojibwe verbs"
authors: ["Minh Nguyen", admin, silfverberg]
date: 2025-04-01T16:02:51-04:00
doi: "https://aclanthology.org/2025.americasnlp-1.3/"

# Schedule page publish date (NOT publication's date).
publishDate: 2025-04-01T16:02:51-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACL Anthology"
publication_short: ""

abstract: "Machine translation is a tool that can help teachers, learners, and users of low-resourced languages. However, there are significant challenges in developing these tools, such as the lack of large-scale parallel corpora and complex morphology. We propose a novel hybrid system that combines LLM and rule-based methods in two distinct stages to translate inflected Ojibwe verbs into English. We use an LLM to automatically annotate dictionary data to build translation templates. Then, our rulebased module performs translation using inflection and slot-filling processes built on top of an FST-based analyzer. We test the system with a set of automated tests. Thanks to the ahead-of-time nature of the template-building process and the light-weight rule-based translation module, the end-to-end translation process has an average translation speed of 70 milliseconds per word. The system achieved an average ChrF score of 0.82 and a semantic similarity score of 0.93 among the successfully translated verbs in a test set. The approach has the potential to be extended to other low-resource Indigenous languages with dictionary data."

# Summary. An optional shortened abstract.
summary: ""

tags: ["translation", "Ojibwe", "Algonquian", "language revitalization"]
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
