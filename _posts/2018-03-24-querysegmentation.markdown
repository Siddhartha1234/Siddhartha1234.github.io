---
layout: post
title:  "Query Segmentation using LSTMs"
date:   2018-03-24 18:08:39 +00:00
image: /images/querysegimg.png
categories: research 
course: "Information Retrieval"
author: "Siddhartha Mishra"
slides: pdfs/querysegmentation-slides.pdf
report: pdfs/querysegmentation-report.pdf

subtitle: "Segmenting queries effectively into phrases using bi directional LSTMs"
---

Mapped the problem to that of a sequence tagging problem with binary labels to create/not create a new segment.
Used Bidirectional LSTMs with/without CRF layer to obtain better performance than existing methods.

