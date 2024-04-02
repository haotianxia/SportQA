# SportQA: A Benchmark for Sports Understanding in Large Language Models
Haotian Xia<sup>1</sup>, Zhengbang Yang<sup>1</sup>, Yuqing Wang<sup>2</sup>, Rhys Tracy<sup>3</sup>, Yun Zhao<sup>4</sup>, Dongdong Huang<sup>5</sup>, Zezhi Chen<sup>1</sup>, Yan Zhu<sup>5*</sup>, Yuan-fang Wang<sup>3</sup>, Weining Shen<sup>1*</sup>

<sup>1</sup> University of California, Irvine, <sup>2</sup>Stanford University, <sup>3</sup>University of California, Santa Barbara, <sup>4</sup>Meta Platforms, Inc., <sup>5</sup>Beijing Normal University

## Abstract

A deep understanding of sports, a field rich in strategic and dynamic content, is crucial for advancing Natural Language Processing (NLP). This holds particular significance in the context of evaluating and advancing Large Language Models (LLMs), given the existing gap in specialized benchmarks. To bridge this gap, we introduce SportQA, a novel benchmark specifically designed for evaluating LLMs in the context of sports understanding. SportQA encompasses over 70,000 multiple-choice questions across three distinct difficulty levels, each targeting different aspects of sports knowledge from basic historical facts to intricate, scenario-based reasoning tasks. We conducted a thorough evaluation of prevalent LLMs, mainly utilizing few-shot learning paradigms supplemented by chain-of-thought (CoT) prompting. Our results reveal that while LLMs exhibit competent performance in basic sports knowledge, they struggle with more complex, scenario-based sports reasoning, lagging behind human expertise. The introduction of SportQA marks a significant step forward in NLP, offering a tool for assessing and enhancing sports understanding in LLMs.

## Dataset

Each level includes three files: data, dev, and test. The test folder includes questions that we tested in the paper, while the dev folder is used to generate 5-shot and 5-shot CoT experiments. The data folder contains all questions that were not tested but can be further used as training data. All tasks are split into these three parts and distributed in the corresponding folders. For level 3, all questions are formatted in data and test files by using labels to distinguish different tasks.

## Citation

If you find our dataset useful in your research, please consider giving a star and citation.

<tab>@article{xia2024sportqa,
  title={SportQA: A Benchmark for Sports Understanding in Large Language Models},
  author={Xia, Haotian and Yang, Zhengbang and Wang, Yuqing and Tracy, Rhys and Zhao, Yun and Huang, Dongdong and Chen, Zezhi and Zhu, Yan and Wang, Yuan-fang and Shen, Weining},
  journal={arXiv preprint arXiv:2402.15862},
  year={2024}<tab>
