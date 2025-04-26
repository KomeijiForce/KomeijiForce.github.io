---
permalink: /
title: "Letian's Academic Homepage ~ Here begins my voyage!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 3rd year Ph.D. student at UC San Diego, advised by Professor [Jingbo Shang](https://shangjingbo1226.github.io/). I got my B.S. degree in Computer Science at SJTU, advised by Professor [Hai Zhao](https://bcmi.sjtu.edu.cn/home/zhaohai/). 

**2023-2024:** I worked on building NLP systems with extremely weak signals from humans with collaboration from LLMs (Knowledge Discovery).

**2025:** I am working on unveiling the mechanisms behind LLM's memorization, diversity, generalization, and hallucination (Knowledge Parameterization).

Research Interest
------

My research interests are knowledge discovery, parameterization, and generation of large language models. I aim to build **knowledgeable** LLMs (especially as experts in unique domains) with **Diversity**, **Generalizability**, and **Fine-granularity**.


### Discovery: Mining useful knowledge (texts/spans) with minimal supervision

1. Text Mining: ([CoTAM@ACL2024F](https://aclanthology.org/2024.findings-acl.1/), [Incubator@EMNLP2024](https://aclanthology.org/2024.emnlp-main.220/), [TextGraft@EMNLP2024](https://aclanthology.org/2024.emnlp-main.219/))
2. Span Extraction: ([NDD@ACL2023F](https://aclanthology.org/2023.findings-acl.694/), [X-NER@EMNLP2023F](https://aclanthology.org/2023.findings-emnlp.908/), [MetaIE](https://arxiv.org/abs/2404.00457), [Cuckoo](https://arxiv.org/abs/2502.11275))
3. Text Representation: ([InBedder@ACL2024](https://aclanthology.org/2024.acl-long.27/))

### Parameterization (2025 Focus): Understanding LLM's mechanism in knowledge memorization/generalization. 

1. The diversity issue caused by unembedding parameters in LLMs ([ICN@ICLR2025](https://arxiv.org/abs/2410.02284))
2. The rule of next token prediction generalization ([LinCorr](https://arxiv.org/abs/2502.04520))

### Generation: Learn LLMs to perform diverse open-ended generation following massive constraints.

1. Fine-granularize role-playing faithfulness under massive constraints ([APC@NeurIPS2024](https://neurips.cc/virtual/2024/poster/94451))
2. Extremely Fine-grained control (like 100 attributes) for text generation. ([UltraGen](https://arxiv.org/abs/2502.12375))

### Paradigm: Efficient learning objectives to structure knowledge inside models for specific usage.

1. Convert next token prediction to extraction for IE pre-training ([Cuckoo](https://arxiv.org/abs/2502.11275))

Overlapped Fields
------

**Discovery:** Text Mining, Information Extraction, Information Retrieval, Text Clustering, Data Augmentation, Data Synthesis, Tool Use

**Parameterization:** Representation Interpretation, Knowledge Composition, Knowledge Editing, Catastrophic Forgetting, Model Unlearning

**Generation:** Diverse Decoding, Controllable Generation, Multiple Objective Alignment, Evaluation Metric, Long Context Understanding

Specific Questions (Keep Updating)
------
The following lists the specific questions I want to answer in the future years:
- **\[Diversity\]** How can we extract as much knowledge (might be as simple as "List all the mammals") as possible from LMs? How can we know we have enumerated all the knowledge known by the LMs? Also, LMs have a bias ([ICN@ICLR2025](https://arxiv.org/abs/2410.02284)) caused by their representative nature, how can we overcome this?
- **\[Generalization\]** How do the magical abilities emerge inside the LMs? Is it a sudden comprehension or accumulation of seen input contexts? ([LinCorr](https://arxiv.org/abs/2502.04520)) LMs are known to struggle with composing knowledge, why this seems not to be an issue for its application? Is most daily usage covered by the LM's memorization so generalization is not necessary for its deployment? Can we systemically design a pipeline based on all learned data to generate questions that an LLM will never be able to answer?
- **\[Memorization\]** LMs are proud of their memorization ability of seen data, which is found to be limited in the multiple-answer case ([ICN@ICLR2025](https://arxiv.org/abs/2410.02284)). Also, it cannot be denied that LMs can make mistakes on seen questions. Can this be all attributed to forgetting? Or is this an architectural issue in LM's memorization of knowledge?
- **\[Fine-granularity\]** LMs in deployment require following lots of constraints, such as system prompt and personal preference. Are current LMs able to follow millions of constraints assigned to them? If not, how can we improve this through data, model architecture, or learning paradigm?

Specific Applications (Keep Updating)
------
While LMs are blamed for having so many issues, no one can deny their automation of knowledge discovery, the following lists some applications of LMs:
- **\[Automatic Knowledge Mining\]** There are generally three ways for LMs to mine knowledge. (1) Directly fine-tuned the knowledge base and take questions from the users. (2) Iterate the knowledge base and summarize the potential knowledge inside each instance. (3) Distill itself into smaller models to more efficiently interact with large-scale data ([Incubator@EMNLP2024](https://aclanthology.org/2024.emnlp-main.220/)). From my viewpoint, (3) is inevitable for efficient knowledge mining as we don't want to ask LMs "Is this instance a positive movie review" for each instance. The distilled models can be viewed as tools for LMs to use for knowledge mining, which requires the tool-using skills of LMs. Can we automate such an automatic knowledge mining system based on a single LM/collaboration of LMs?

Talks
------
- SJTU AAA alumni talk@Shanghai Jiaotong University, Apr. 2025

MISC
------
![image](https://github.com/user-attachments/assets/b94ac6b9-4ae4-433b-b090-0d7eb6c8166b)
[My Huggingface Repo](https://huggingface.co/KomeijiForce)

Collaboration
------
I am open to any type of collaboration! As long as you have the passion, I would not mind supporting you from the very beginning! Please feel free to contact me via email! :-) I offer 3 levels of collaboration:
1. **Implementation-driven.** You will be given a promising but not so impactful idea, which generally derives from the massive experiments in my previous exploration. Your task is to implement and systematically verify this idea and extend it to some degree. I will hand on to guide you with the experiment details.
2. **Exploration-driven.** You will be given an intuitively promising (but maybe not) idea on important topics, which is my hypothesis derived from the conclusion of my previous works. Your task is to further develop this insight to reach the true answer under the surface results. There is no promise that we can make it a publication with directly the original idea but I am confident we will have some interesting results to publish. I will assume you to be proficient in basic research skills if you select this level. I will devote more time to discussing with you the explanation of the results and potential next steps to move to.
3. **High-level.** I will share my high-level insight into the questions mentioned on this page and let you lead the project. There is no guarantee of an immediate solution and my role is only as a collaborator in comparison with the guiding responsibility in the upper two levels.

- For communication efficiency, I only accept **in-person** collaboration, so make sure that you will be in San Diego.
- Generally, you will lead a project rather than being a co-author.
- We will only submit to the 6 top NLP/ML conferences. **(ACL/EMNLP/NAACL/NeurIPS/ICLR/ICML)**
- Level 1 is good for beginners. No professional publication experience is required but you are encouraged to have background knowledge, coding ability, and most importantly, the love to explore the **truly unknown**.
- Level 2 requires a leading project experience resulting in a top conference publication-level paper. Make sure you include the link to your paper in the email and I will check its relevance to the collaboration topic. Generally, the conclusion will be built based on the **real results** rather than the initial intuition.
- Level 3 has no hard requirements. But such collaboration can hardly be built only by an email in common sense.

Please email ```lepeng@ucsd.edu``` if you are interested in a collaboration with your CV and supplemental resources mentioned above

Visitor Flow
------
<div style="width: 300px; height: 200px; border: 1px solid #ccc;">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=mn_UJ37oAc-Rp1wrfDbwW3-tEq2pnMNgtE-hbbNFsy4&cl=ffffff&w=a"></script>
</div>
