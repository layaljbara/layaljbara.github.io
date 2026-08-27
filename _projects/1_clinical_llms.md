---
layout: project
title: Clinical language models for liver transplant care
description: Domain-adapted open models on post-transplant clinic letters, with next-visit labs, immunosuppression, and SOP-cited Assessment & Plan as the clinical targets.
img: assets/img/projects/clinical_llms.png
importance: 1
category: healthcare
---

At UHN’s Ajmera Transplant Centre I am adapting an open 20B language model to **post-liver-transplant clinic letters**. The Assessment & Plan is held out of the input so the model cannot copy the plan and then “predict” it. The question is whether the letter still contains residual information about the **next graft / kidney / tacrolimus panel** and the **next immunosuppression change** after last structured labs are known - in the spirit of [NYUTron](https://www.nature.com/articles/s41586-023-06160-y), at the clinic-time decision rather than at mortality.

A second track is generation: write an Assessment & Plan a hepatologist would consider signing, and **cite the local immunosuppression SOP or a transplant guideline** when it does so.

This work sits in Dr. Mamatha Bhat’s lab and the Transplant AI Initiative. Methods and unpublished numbers stay off this page until they are in a preprint.

### Code & data availability

- **Status:** Active research codebase (private).
- **Code:** Available **upon request** for collaboration, subject to institutional agreements.
- **Data:** UHN clinical notes and derived artifacts are **not** publicly shareable.
- **Public overview:** [transplant-ai-projects](https://github.com/layaljbara/transplant-ai-projects) (structure and description only).
