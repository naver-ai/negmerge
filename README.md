## [NegMerge: Sign-Consensual Weight Merging for Machine Unlearning](https://arxiv.org/abs/2410.05583)

> [Hyoseo Kim<sup>1,2*](https://sites.google.com/view/hyoseokim), [Dongyoon Han<sup>1</sup>&dagger;](https://dongyoonhan.github.io/), [Junsuk Choe<sup>2</sup>&dagger;](https://sites.google.com/site/junsukchoe/) <br>
> <sup> * Work done during an internship at NAVER AI Lab, &dagger; corresponding authors </sup> <br>
> <sup>1</sup>[NAVER AI LAB](https://naver-career.gitbook.io/en/teams/clova-cic/ai-lab), <sup>2</sup>[Sogang University](https://www.sogang.ac.kr/ko/home)

[![paper](https://img.shields.io/badge/arXiv-Paper-red.svg)](https://arxiv.org/abs/2410.05583)

### Abstract
>Machine unlearning aims to selectively remove specific knowledge from a trained model. Existing approaches, such as task arithmetic, fine-tune the model on the forget set to create a task vector (i.e., a direction in weight space) for subtraction from the original weight. However, their effectiveness is highly sensitive to hyperparameter selection, requiring extensive validation to identify the optimal vector from many fine-tuned candidates. In this paper, we propose a novel method that utilizes all fine-tuned models trained with varying hyperparameters instead of a single selection. Specifically, we aggregate the computed task vectors by retaining only the elements with consistent shared signs. The merged task vector is then negated to induce unlearning on the original model. Evaluations on zero-shot and standard image recognition tasks across ten datasets and three backbone architectures show that our approach achieves superior unlearning performance. It outperforms state-of-the-art methods while requiring similar or fewer computational resources.


### Our Motivation: Hyperparameter Sensitivity in Negation Methods
- (a) shows performance comparisons with competing methods (+ fine-tuned models alone) in task negation;
- (b) illustrates detailed parameter sensitivity across various datasets:

  <img width="600" alt="image" src="https://github.com/user-attachments/assets/c193ba98-3927-4e03-bc73-a53df6db3e63">
  
### Updates
* (2025/05/01): Our paper has been accepted at [ICML 2025](https://icml.cc/)🎉🎉🎉🎉
* (2024/10/09): Our paper has been accepted at [NeurIPS 2024 Workshop on Adaptive Foundation Models](https://adaptive-foundation-models.org/)🎉🎉🎉🎉
* (2024/10/03): Code is under internal review.
* (2024/10/03): [Preprint](https://arxiv.org/abs/2410.05583) has been uploaded.
