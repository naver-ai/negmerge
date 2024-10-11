## [NegMerge: Consensual Weight Negation for Strong Machine Unlearning](https://arxiv.org/abs/2410.05583)

> [Hyoseo Kim<sup>1,2*](https://sites.google.com/view/hyoseokim), [Dongyoon Han<sup>1</sup>&dagger;](https://dongyoonhan.github.io/), [Junsuk Choe<sup>2</sup>&dagger;](https://sites.google.com/site/junsukchoe/) <br>
> <sup> * Work done during an internship at NAVER AI Lab, &dagger; corresponding authors </sup> <br>
> <sup>1</sup>[NAVER AI LAB](https://naver-career.gitbook.io/en/teams/clova-cic/ai-lab), <sup>2</sup>[Sogang University](https://www.sogang.ac.kr/ko/home)

[![paper](https://img.shields.io/badge/arXiv-Paper-red.svg)](https://arxiv.org/abs/2410.05583)

### Abstract
>Machine unlearning aims to selectively remove specific knowledge from a model. Current methods, such as task arithmetic, rely on fine-tuning models on the forget set, generating a task vector, and subtracting it from the original model. However, we argue the effectiveness of this approach is highly sensitive to hyperparameter selection, necessitating careful validation to identify the best model among many fine-tuned candidates. In this paper, we propose a novel method that leverages all given fine-tuned models rather than selecting a single one. By constructing task vectors from models trained with varied hyperparameters and merging only the components of the task vectors with consistent signs, we perform unlearning by negating the merged task vector from the original model. Given that existing methods also utilize multiple fine-tuned models, our approach delivers more effective unlearning without incurring additional computational costs. We demonstrate the effectiveness of our method on both vision-language models and standard image classification models, showing improved unlearning performance with minimal degradation on the retain set, outperforming state-of-the-art techniques.


### Our Motivation: Hyperparameter Sensitivity in Fine-Tuned Models for Unlearning
- (a) shows performance comparisons with competing methods (+ fine-tuned models alone) in task negation;
- (b, c) illustrates detailed parameter sensitivity across various datasets (b), (c):

  <img width="786" alt="image" src="https://github.com/user-attachments/assets/5a1dc63c-214b-4d8f-8f52-0f5758ad35f7">




### Updates
* (2024/10/09): Our paper has been accepted at [NeurIPS 2024 Workshop on Adaptive Foundation Models](https://adaptive-foundation-models.org/)🎉🎉🎉🎉
* (2024/10/03): Code is under internal review.
* (2024/10/03): [Preprint](https://arxiv.org/abs/2410.05583) has been uploaded.
