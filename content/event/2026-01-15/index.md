---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Seminar: \"Reframing Content Moderation: Guideline-Driven and Explainable Hate Speech Detection\""
# event:
# event_url:
location: Abacws
# address:
#   street:
#   city:
#   region:
#   postcode:
#   country:
summary: Talk by [Agostina Calabrese](https://ago3.github.io/) (University of Edinburgh)
abstract: "Ensuring safe online spaces requires systems that can reliably identify harmful content such as hate speech. While human moderators follow detailed policy guidelines, most automated systems are trained under an example-driven paradigm, learning what constitutes hate speech from labelled examples alone. This approach encourages models to rely on superficial cues, such as group identifiers, rather than on the underlying concept of hate speech itself. This work proposes a shift toward guideline-driven moderation, where models are trained to reason in terms of the same policy elements that guide human moderators. To expose the weaknesses of existing systems, we first introduce Adversarial Attacks against Abuse (AAA), an evaluation strategy that dynamically generates adversarial examples from standard datasets, revealing when models achieve high accuracy for the wrong reasons. We then present PLEAD, a dataset of social media posts annotated with fine-grained elements derived from moderation policies: intents describing user purpose and slots identifying relevant textual spans. This representation enables structured, policy-aligned explanations of model decisions. In a study with professional moderators, such explanations improved engagement and reduced decision-making time. Experiments with large language models show that guideline-driven fine-tuning achieves performance comparable to traditional approaches while offering greater transparency and robustness. Finally, we show that training on a balanced synthetic dataset, where all combinations of targets and abusive expressions occur equally often, improves models’ ability to adapt to changes in moderation guidelines and emerging real-world events."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2026-01-15T13:00:00Z
date_end: 2026-01-15T14:00:00Z
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2026-01-12T00:00:00Z

authors: [ousidhoumn]
tags: []

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

**Invited Speaker:** [Agostina Calabrese](https://ago3.github.io/)(University of Edinburgh)

**Short Bio:**
Agostina Calabrese is a final-year Ph.D. student at the UKRI Centre for Doctoral Training in NLP at The University of Edinburgh, where she works on policy-aware explainable abuse detection under the supervision of Björn Ross and Mirella Lapata. Her research focuses on developing models that align with platform-specific moderation policies while remaining transparent and explainable, demonstrating how this approach can significantly reduce costs in real-world moderation pipelines. She is a member of the EdinburghNLP group based at the Institute for Language, Cognition and Computation (ILCC). She has worked as a Research Intern in the Computational Social Science team at Snap Inc. (Fall 2023) and in the Assistant AI team at Meta Reality Labs (Fall 2022). Previously, she was a Research Fellow at Sapienza NLP (Sapienza University of Rome), where she worked on multimodal systems for language–vision tasks and on the development of BabelPic. She holds a Bachelor’s degree (2017) and a Master’s degree (2019) in Computer Science from Sapienza University of Rome, both awarded with full marks and honors (110/110 cum laude).
She is also actively involved in the NLP community around online safety. She co-organised the 8th and 9th Workshop on Online Abuse and Harms (2024, 2025), and in 2022, she created a Slack community for researchers and practitioners working on hate speech and related topics. As of June 2025, the community includes over 250 members from academia and industry.
