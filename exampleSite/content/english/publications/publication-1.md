---
title: A Few Thousand Translations Go a Long Way! Leveraging Pre-trained Models for
  African News Translation
date: 2023-02-08T11:05:24+00:00
image: "/images/using-machine-learning-to-enable-the-translation-of-local-african-languages.png"
author: Derguene Mbaye
description: This is meta description
links:
- label: Paper
  link: https://aclanthology.org/2022.naacl-main.223/
- label: Github repo
  link: https://github.com/masakhane-io/lafand-mt

---
Recent advances in the pre-training of language models leverage large-scale datasets to create multilingual models. However, **low-resource languages are mostly left out in these datasets**. This is primarily because many widely spoken languages are not well represented on the web and therefore excluded from the large-scale crawls used to create datasets. Furthermore, **downstream users of these models are restricted to the selection of languages originally chosen for pre-training**.

This work investigates **how to optimally leverage existing pre-trained models to create low-resource translation systems** for 16 African languages. We focus on two questions:

1. How can pre-trained models be used for languages not included in the initial pre-training?
2. How can the resulting translation models effectively transfer to new domains?

To answer these questions, **we create a new African news corpus covering 16 languages, of which eight languages are not part of any existing evaluation dataset.** We demonstrate that the most effective strategy for transferring both to additional languages and to additional domains is to fine-tune large pre-trained models on small quantities of high-quality translation data.