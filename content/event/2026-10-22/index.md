---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Seminar: \"Invisibilization as a Source of Probability Bias in Language Models\""
# event:
# event_url:
location: Abacws
# address:
#   street:
#   city:
#   region:
#   postcode:
#   country:
summary: Talk by [Christian Arnold](https://www.birmingham.ac.uk/staff/profiles/gov/arnold-christian)
abstract: "Language models are aligned to avoid using protected attributes such as race, ethnicity, and gender to inform their responses. Therefore, they increasingly refuse or hedge when such attributes appear in a prompt. However, if a system must decide how much to learn from what people tell it, it is costly to refuse valuable information because of its source. In this article, we measure the cost of declining information in a two-urn game with an exact Bayesian answer. We present leading LLM models from two developers (OpenAI and Anthropic) with a prompt that requires them to decide how far to trust an unverifiable report from a participant whose description we randomize across ten configurations (6,600 sessions). We show that leading models often decline to assess the reporter, treating information as worthless at rates set by the description rather than by the evidence. At its widest, models decline a Black-described reporter 46% of the time and a white-described reporter 9%; yet, when they do assess the information, the Black-described reporter receives slightly more trust. The bias is invisible to audits that compare average trust or look only at assessed cases. It grows with reasoning effort, follows words rather than categories (models invoke race for “Black” but not for its Spanish translation “negro”, and never for “Indigenous”), and worsens under warning instructions a practitioner would try first. We also present a scoring option that reduces the refusal rate bias. When a model's trust is scored against revealed truth over repeated rounds, it credits identical records equally. In four of five configurations from Anthropic and OpenAI, the racial gap in trust falls below 0.02 by the last rounds."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2026-10-22T13:00:00Z
date_end: 2026-10-22T14:00:00Z
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2026-10-19T00:00:00Z

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

**Speaker:** [Christian Arnold](https://www.birmingham.ac.uk/staff/profiles/gov/arnold-christian)

**Authors:** Christian Arnold, Ernesto Calvo, Guadalupe Gonzalez, Sebastián Vallejo Vera, Tiago Ventura
