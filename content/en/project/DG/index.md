---
title: Research on the Analysis and Mitigation of Voltage Sag Events
summary: Based on the previous project concerning the voltage sag monitoring, we made several improvements in the relating location and identification techniques.
tags:
- DL
- VS
- DG
date: "2019-06-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Haotian SUN
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
slides: ""
---

With the advancement and broad application of distributed power technologies such as energy storage, power grid systems undergo fundamental changes throughout their structures. One major problem caused by voltage sag is the degradation of the power supply quality,  which consists of many distributed power sources such as energy storage.

Aimed at the distribution network with distributed power sources such as energy storage, we studied the influence of distributed power sources on the voltage sag propagation mechanism. Based on this, we designed economic monitoring equipment configuration strategies and efficient identification methods for categorizing voltage sag types and accurate voltage sag source locating techniques. The project intends to understand further the influence mechanism of voltage sags in distribution networks containing distributed power sources through the above research and provide systematic analysis and solutions for the effective prevention and control of voltage sags.

[1]: featured.png

Efficient identification of the voltage sag sources is significant in the power quality studies. Most identification methods will suffer notable degradations facing input samples' insufficiency. We found the deep learning techniques crucial to rise to sag source identification challenges. By harnessing the few-shot learning concepts, we reformed phase voltages into RGB representations, fitted them into a specific siamese network, and eventually improved the method's learning ability with good performance even in the case of few samples. We have proposed a novel method for voltage sag source identification that performs automatic feature extraction and shows a superior performance regardless of the insufficient amount of training samples. In the proposed strategy, the input data are preprocessed and fetched into the feature extractor, designed based on the convolutional neural network. Then the weighted k-nearest neighbor classifier generates the identification results. In the training period, the few-shot learning technique is harnessed, and the siamese network is constructed such that the proposed model learns efficiently even with a small number of samples. The proposed scheme is implemented in Python and PyTorch frameworks. Case studies and comparisons with other methods are carried out on 700 samples of voltage sag events in Jiangsu Province, China. Experimental results show the superiority of the proposed method over other identification methods in the tested cases. In developing the identification method, we found the deep learning techniques crucial to rise to sag source identification challenges.

As for fault location, most existing approaches were not, at the same time, sufficiently effective in several requirements such as robustness to the presence of distributed resources and monitor-allocation optimality.  When implementing the precise location method, the algorithm had to maintain stability under the impacts of numerous factors like noises, fault resistance, and sampling rates. We formulated a novel fault-location method for unbalanced distribution networks in the presence of distributed generations. The faulty candidate lines are selected by utilizing the linear least square method, and the injected fault currents are derived from the sparse voltage phasor measurements. According to the fault currents' obtainability, two types of approaches are adopted for estimating the per-unit fault location. The actual faulted line and the accurate fault location are identified by taking advantage of the precise fault-location scheme. Also, to compromise between the fault-location accuracy and the allocation costs, an optimal monitor-allocation algorithm is developed for determining the Pareto-optimal set of meter placements that have the minimal number of monitors to satisfy the requirements of fault-location accuracy. The proposed optimal allocation algorithm and the two types of fault-location approaches are validated on a modified IEEE 123-node test feeder using Matlab and Simulink.

