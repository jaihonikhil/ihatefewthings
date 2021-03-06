---
title: Statement Verification and Evidence Finding using Tables
summary: SemEval Task 9
tags:
- Natural Language Processing
date: "2021-03-03T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: 
  focal_point: Smart

links:
- icon: linkedin
  icon_pack: fab
  name: Follow
  url: https://linkedin
url_code: "https://github.com/jaihonikhil/Rocinante-at-Semeval-Task9"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Tables are ubiquitous in documents and presentations for conveying important information in a concise manner. This is true in many domains, stretching from scientific to government documents.  In fact,  surrounding text in these articles are often statements summarizing or highlighting some information derived from the primary source data in tables. Describing all the information provided in a table in a readable manner would be lengthy and considerably more difficult to understand. 

Recently, there has been an interest in factual verification and prediction over structured data like tables and graphs. To circumvent any false news incident, it is necessary to not only model and predict over structured data efficiently but also to explain those predictions. In this paper, as part of the SemEval-2021 Task 9,  we tackle the problem of fact verification and evidence finding over tabular data.

 There are two subtasks. Given a table and a statement/fact, subtask A determines whether the statement is inferred from the tabular data, and subtask B determines which cells in the table provide evidence for the former subtask. We make a comparison of the baselines and state-of-the-art approaches over the given SemTabFact dataset. We also propose a novel approach CellBERT to solve evidence finding as a form of the Natural Language Inference task. We obtain a **3-way F1 score of 0.69 on subtask A** and an **F1 score of 0.65 on subtask B**. We were **5th in Subtask A** and **1st in Subtask B**

