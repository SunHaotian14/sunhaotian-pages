---
title: Development and Application of 10kV-level Voltage Sag Compensation Device
summary: In this project, we designed the 10kV voltage sag compensation device. The prototype device was verified by two hardware-in-loop (HIL) machine:: one dSpace represents the control circuits and one RT Box for the power circuits.
tags:
- VS
date: "2019-04-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Haotian
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
Among the various power quality problems, voltage sag has become one of the most significant factors degrading power supply quality. Voltage sags usually have a short duration ad yield severe impacts on the sensitive loads. In recent years, the demand has risen to prevent voltage sags in the 10kV sensitive load group. However, attractive solutions are absent. This project develops 10kV voltage sag compensation equipment with good performance and low cost in response to this actual demand. The project decided to create a prototype of a 10kV voltage sag compensation device with energy storage through preliminary investigation and comparison. On this basis, a 10kV/2MW prototype is trial-produced, and then field application verification is carried out to form a complete solution and technical data.

<img src="overview.png" width="90%">

The prototype device was verified by two hardware-in-loop (HIL) machine:: one dSpace represents the control circuits and one RT Box for the power circuits. The intermediate circuit interconnecting the dSpace device and the PLECS RTBox represents as follows:

<img src="interconnection.png" width="90%">
