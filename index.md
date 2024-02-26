---
permalink: /s24
redirect_from:
 - /
---

- **Do not email the course staff. For private matters, post a private question on [edstem](https://edstem.org/us/courses/51702/discussion/) and make sure it is visible to all teaching staff.**

- ***Prerequisite:*** **Prospective students should have taken CS 182/282A Deep Neural Networks or its equivalent(s) and had some hands-on experience with deep learning.**

- Prospective students should ***first try enrolling in the course through CalCentral***. The class number of CS 194-267 (for undergraduate students) is 34188 and the class number of CS 294-267 (for graduate students) is 34187. Please join the waitlist if the course is full. ***Please fill in the [enrollment petition form](https://forms.gle/g9SJYTzCY14HVcsc9) if you are on or cannot join the waitlist***. We will reach out to you if your petition is approved.

<!-- - ***For course announcements, please join our [edstem](https://edstem.org/us/courses/41945/discussion/).*** -->
<!-- - ***<span style="color:red">Do not email the course staff or GSI. For private matters, post a private question on edstem and make sure it is visible to all teaching staff.</span>*** -->

## Course Staff

<table>
<tbody>
<tr>
<td>
Instructor
</td>
<td>
(Guest) Co-instructor
</td>
</tr>
<tr>
<td><img src="assets/dawn-berkeley.jpg" height=200/></td>
<td><img src="assets/dan1.jpg" height=200/></td>
</tr>
<tr>
<td><a href="https://people.eecs.berkeley.edu/~dawnsong/">Dawn Song</a></td>
<td><a href="https://people.eecs.berkeley.edu/~hendrycks/">Dan Hendrycks</a></td>
<tr>
<td>Professor, UC Berkeley</td>
<td>Director, Center for AI Safety</td>
</tr>
</tr>
</tbody>
</table>

GSI: Yu Gai

[edstem](https://edstem.org/us/courses/51702/discussion)

## Class Time and Location

Lecture: 3:30-5pm PT Tuesday at Soda 306

**First lecture rescheduled to Jan 19 noon-1:30pm at Soda 306**

## Course Description

Generative AI and Large Language Models (LLMs) including ChatGPT have ushered the world into a new era with rich new capabilities for wide-ranging application domains. At the same time, there is little understanding of how these new capabilities emerge, their limitations and potential risks. In this class, we will introduce foundations of LLMs, study methods for better understanding LLMs, discuss scaling laws and emergence, and explore the risks and challenges with these technologies and how we can build towards safe and beneficial AI. In particular, this class will cover a wide-ranging topics including:
- Foundations of LLMs
- Interpretability
- Scaling laws
- Adversarial robustness
- AI alignment and governance
- Trojans and unlearning
- Privacy and watermarking
- Agency and emergence
- Reasoning and mathematics
- Evaluation and benchmarking

## Syllabus (subject to change)

| Date   | Topic | Readings <br> (forms due at 2pm before the day of the lecture) |
|--------|-------|----------|
| Jan 19 | **Intro ([slides](assets/intro-cs294-267-s24.pptx.pdf)) & transformer, LLM foundations ([slides](assets/jan19.pdf))** <br> Guest speaker: Łukasz Kaiser (Member of Technical Staff, OpenAI) | - [Attention Is All You Need](https://arxiv.org/abs/1706.03762) <br> - [Chain-of-Thought Prompting](https://arxiv.org/abs/2201.11903) <br> - (Optional) [Neural GPUs](https://arxiv.org/abs/1511.08228) <br> - (Optional) [GPT becoming a Turing machine](https://arxiv.org/abs/2303.14310) <br> *Fill [this](https://forms.gle/7L32LGARW66fcYx76) out after reading the papers!* |
| Jan 23 | **AI safety primer ([slides](assets/jan23.pdf)) and representation engineering ([slides](assets/jan23_1.pdf))** <br> Guest speaker: Dan Hendrycks (Director, Center for AI Safety) | - [Unsolved Problems in ML Safety](https://arxiv.org/abs/2109.13916) <br> - [Representation Engineering](https://arxiv.org/abs/2310.01405) <br> - (Optional) [Catastrophic AI Risks](https://arxiv.org/abs/2306.12001) <br> *Fill [this](https://forms.gle/35BfFWG9Qez7A9va7) out after reading the papers!* |
| Jan 30 | **Interpretability and model editing ([slides](assets/jan30.pdf))** <br> Guest speaker: David Bau (Assistant Professor, Northeastern University) | - [Locating and Editing Factual Associations in GPT](https://arxiv.org/abs/2202.05262) <br> - [Function Vectors in LLMs](https://arxiv.org/abs/2310.15213) <br> - (Optional) [Visualizing and Understanding CNNs](https://arxiv.org/abs/1311.2901) <br> - (Optional) [Linear Classifier Probes](https://arxiv.org/abs/1610.01644) <br> - (Optional) [In-context Learning and Induction Heads](https://arxiv.org/abs/2209.11895) <br> *Fill [this](https://forms.gle/H7LaG1tmRpKj2qK96) out after reading the papers!* |
| Feb 6  | **Inside-out interpretability: training dynamics in multi-layer transformer ([slides](assets/feb6.pdf))** <br> Guest speaker: Yuandong Tian (Research Scientist and Senior Manager, Meta AI Research) | - [Scan and Snap](https://arxiv.org/abs/2305.16380) <br> - [JoMA](https://arxiv.org/abs/2310.00535) <br> - (Optional) [StreamingLLM](https://arxiv.org/abs/2309.17453) <br> - (Optional) [Deja Vu](https://proceedings.mlr.press/v202/liu23am.html) <br> - (Optional) [H<sub>2</sub>O](https://arxiv.org/abs/2306.14048) <br> *Fill [this](https://forms.gle/9mnmsnzfELhNhC2z6) out after reading the papers!* |
| Feb 13 | **Models within models: how do LLMs represent the world? [(slides)](assets/feb13.pdf)** <br> Guest speaker: Martin Wattenberg (Professor, Harvard University)| - [Emergent World Representations](https://arxiv.org/abs/2210.13382) <br> - [The System Model and the User Model](https://arxiv.org/abs/2305.02469) <br> - (Optional) [Probing Classifiers](https://arxiv.org/abs/2102.12452) <br> - (Optional) [Climbing towards NLU](https://aclanthology.org/2020.acl-main.463/) <br> - (Optional) [Can LMs Encode Perceptual Structure without Grounding?](https://aclanthology.org/2021.conll-1.9/) <br> *Fill [this](https://forms.gle/g6JLneBaa8Vd5ik36) out after reading the papers!* |
| Feb 20 | **Benchmarks and evals, safety vs. capabilities, machine ethics [(slides)](assets/feb20.pdf)** <br> Guest speakers: Dan Hendrycks (Director, Center for AI Safety) and Bo Li (Associate Professor, University of Chicago) | - [DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models](https://arxiv.org/abs/2306.11698) <br> - [Do the Rewards Justify the Means? Measuring Trade-Offs Between Rewards and Ethical Behavior in the MACHIAVELLI Benchmark](https://arxiv.org/abs/2304.03279) <br> *Fill [this](https://forms.gle/RDDuc2sZwmPj3M6q8) out after reading the papers!* |
| Feb 27 | **Memorization in language models [(slides)](assets/feb27.pdf)** <br> Guest speaker: Eric Wallace (UC Berkeley) | - (Optional) [Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805) <br> - (Optional) [Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/abs/2311.17035) |
| Mar 5  | TBA | |
| Mar 12 | TBA | |
| Mar 19 | TBA | |
| Mar 26 | Spring recess | |
| Apr 2  | TBA | |
| Apr 9  | TBA | |
| Apr 16 | Poster session | |
| Apr 23 | TBA | |

## Enrollment and Grading

- ***Prerequisite:*** **Prospective students should have taken CS 182/282A Deep Neural Networks or its equivalent(s) and had some hands-on experience with deep learning.**

Prospective students should first try enrolling in the course through CalCentral. The class number of CS 194-267 (for undergraduate students) is 34188 and the class number of CS 294-267 (for graduate students) is 34187. Please join the waitlist if the course is full. Please fill in the [enrollment petition form](https://forms.gle/g9SJYTzCY14HVcsc9) if you are on or cannot join the waitlist. We will reach out to you if your petition is approved.

This is a variable-unit course.
All enrolled students are expected to attend lectures in person and submit reading summaries and questions for Q&A before each lecture.
Students enrolling in one unit are expected to write an article that summarizes one of the lectures.
Students enrolling in more than one units are expected to complete a lab assignment and a project.
The project of students enrolling in 2 units should have a written report, which can be a survey in an area relevant to LLMs.
The project of students enrolling in 3 units should also have an implementation (coding) component that programmatically interacts with LLMs, and the project of students enrolling in 4 units should have a significant implementation component with the potential for either real world impacts or intellectual contributions.
The grade breakdowns for students enrolled in different units are the following:

|                                       | 1 unit | 2 units | 3/4 units |
|---------------------------------------|--------|---------|-----------|
| Lecture participation                 | 25%    | 10%     | 10%       |
| Reading summaries & questions for Q&A | 25%    | 10%     | 10%       |
| Article                               | 50%    |         |           |
| Lab                                   |        | 20%     | 10%       |
| Project                               |        |         |           |
| - *Proposal*                          |        | 10%     | 10%       |
| - *Milestone*                         |        | 10%     | 10%       |
| - *Presentation*                      |        | 20%     | 15%       |
| - *Report*                            |        | 20%     | 15%       |
| - *Implementation*                    |        |         | 20%       |

## Lab and Project Timeline

|                         | Released | Due    |
|-------------------------|----------|--------|
| Project group formation | Jan 19   | Jan 30 |
| Project proposal        | Jan 23   | Feb 13 |
| Lab                     | Jan 30   | Feb 27 |
| Project milestone       | Feb 13   | Mar 19 |
| Project presentation    | Mar 19   | Apr 16 |
| Project final report    | Mar 19   | Apr 30 |

## Office Hours

Yu Gai: TBA

## Example Readings

Architectures: [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

Scaling Laws: [LLMs](https://arxiv.org/abs/2001.08361), [RL](https://arxiv.org/abs/2301.13442)

Adversarial Robustness: [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083), [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)

Trojans: [Poisoning and Backdooring Contrastive Learning](https://arxiv.org/abs/2106.09667)

Privacy: [Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/abs/2311.17035)

Watermarking: [A Watermark for Large Language Models](https://arxiv.org/abs/2301.10226)

Unlearning: [Large Language Model Unlearning](https://arxiv.org/abs/2310.10683)

Interpretability: [Representation Engineering: A Top-Down Approach to AI Transparency](https://arxiv.org/abs/2310.01405), [In-context Learning and Induction Heads](https://arxiv.org/abs/2209.11895)

Output Control and Machine Ethics: [DPO](https://arxiv.org/abs/2305.18290), [RLHF](https://arxiv.org/abs/1706.03741), [MACHIAVELLI](https://arxiv.org/abs/2304.03279)

Benchmarks: [DecodingTrust](https://decodingtrust.github.io), [MMLU](https://arxiv.org/abs/2009.03300), [MATH](https://arxiv.org/abs/2103.03874), [TruthfulQA](https://arxiv.org/abs/2109.07958)
