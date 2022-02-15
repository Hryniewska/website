---
layout: post
title: "LIMEcraft: Handcrafted superpixel selection and inspection for Visual eXplanations"
date: 2021-11-15 20:00:00 +00:00
image: /images/limecraft.png
categories: research
venue: "arxiv"
authors: "<strong>Weronika Hryniewska</strong>, Adrianna Grudzień, Przemysław Biecek"
arxiv: https://arxiv.org/abs/2111.08094
code: https://github.com/MI2DataLab/LIMEcraft
---
The increased interest in deep learning applications, and their hard-to-detect biases result in the need to validate and explain complex models. However, current explanation methods are limited as far as both the explanation of the reasoning process and prediction results are concerned. They usually only show the location in the image that was important for model prediction. The lack of possibility to interact with explanations makes it difficult to verify and understand exactly how the model works. This creates a significant risk when using the model. It is compounded by the fact that explanations do not take into account the semantic meaning of the explained objects. To escape from the trap of static explanations, we propose an approach called LIMEcraft that allows a user to interactively select semantically consistent areas and thoroughly examine the prediction for the image instance in case of many image features. Experiments on several models showed that our method improves model safety by inspecting model fairness for image pieces that may indicate model bias.
