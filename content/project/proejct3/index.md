---
title: Preliminary Detection of Pulmonary Diseases 
summary: Silver Medal in Inter IIT Techmeet
tags:
- Healthcare
- Machine Learning
- Pitching
- Start-up
date: "2019-12-03T00:00:00Z"

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
url_code: "https://github.com/jaihonikhil/Preliminary-Detection-of-Pulmonary-Diseases"
url_pdf: ""
url_slides: "https://github.com/jaihonikhil/Preliminary-Detection-of-Pulmonary-Diseases/blob/master/TFC%20Presentation.pptx"
url_video: 
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Early detection of Pulmonary diseases like Aastma, Tuberculosis, COPD ,Bronchiolitis etc through non-invasive method. This project was done keeping in mind a competition "Tech For Change" in Inter IIT Techmeet 2019 in IIT Rorkee.The slides presented are attached as well.

Most of the fatalities caused by pulmonary disorders such as COPD, asthma, bronchiolitis etc. could be prevented by timely diagnosis of the patients. Combined with the extreme lack of medical practitioners and infrastructure in rural areas, the lack of screening programs, which would provide such timely diagnosis, has made pulmonary diseases the second most deadliest kind in India. To make such screening programs more practical and feasible, we propose an automated procedure for the screening of the rural populations, using an easy-to-use device that can be operated even by a community worker. As a proof of concept, we have developed a novel device to record auscultation sounds and the breathing rate of the patient. On this data, a machine learning model with Keras framework and Tensorflow backend is implemented to detect abnormalities.

 A 3 dense layer and a dropout layer convolutional neural network is used to identify Wheezes and Crackles in an audio file which is fed as Mel-Spectrograms as inputs. Data augmentation was employed in the form of audio stretching as well as Vocal Tract Length Perturbation, especially for the scarcer 'wheeze' and 'wheeze and crackles' classes. Overall validation accuracy currently stands at roughly 80 percent. On the user interface side, the mobile application displays an immediate report of the patient displaying the diseases which are suggested by the symptoms observed. Such automation using an inexpensive device removes the dependency on doctors and expensive equipment, which makes the screening programs impractical for large scale implementation today. 

We were awarded silver medal in this competition !