---
permalink: /
title: "Letian's Academic Homepage ~ Be of good cheer!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 3rd year Ph.D. student at UCSD, advised by Professor [Jingbo Shang](https://shangjingbo1226.github.io/). I got my B.S. degree in Computer Science at SJTU, advised by Professor [Hai Zhao](https://bcmi.sjtu.edu.cn/home/zhaohai/). 

Research Interest
------

My research interests are knowledge discovery, parameterization, and generation of large language models. I aim to build **knowledgeable** LLMs (especially as experts in unique domains) with **Diversity**, **Generalizability**, and **Fine-granularity**.


### Discovery: Mining useful knowledge (texts/spans) with minimal supervision

1. Text Mining: ([CoTAM@ACL2024F](https://aclanthology.org/2024.findings-acl.1/), [Incubator@EMNLP2024](https://arxiv.org/abs/2404.10877), [TextGraft@EMNLP2024](https://arxiv.org/abs/2406.11115))
2. Span Extraction: ([NDD@ACL2023F](https://aclanthology.org/2023.findings-acl.694/), [X-NER@EMNLP2023F](https://aclanthology.org/2023.findings-emnlp.908/), [MetaIE](https://arxiv.org/abs/2404.00457))
3. Text Representation: ([InBedder@ACL2024](https://aclanthology.org/2024.acl-long.27/))

### Parameterization: Understanding the limitation of LLMs in knowledge memorization/generalization.

1. The diversity issue caused by unembedding parameters in LLMs ([ICN](https://arxiv.org/abs/2410.02284))

### Generation: Learn LLMs to perform diverse open-ended generation following massive constraints.

1. Fine-granularize role-playing faithfulness under massive constraints ([APC@NeurIPS2024](https://arxiv.org/abs/2405.07726))

Specific Questions (Keep Updating)
------
The following lists the specific small questions I want to answer in the future years:
- \[Diversity\] How can we extract as much knowledge (might be as simple as "List all the mammals") as possible from LMs? How can we know we have enumerated all the knowledge known by the LMs? Also, LMs have a bias ([ICN](https://arxiv.org/abs/2410.02284)) caused by their representative nature, how can we overcome this?
- \[Generalization\] How do the magical abilities emerge inside the LMs? Is it a sudden comprehension or accumulation of seen input contexts? LMs are known to struggle with composing knowledge, why this seems not to be an issue for its application? Is most daily usage covered by the LM's memorization so generalization is not necessary for its deployment? Can we systemically design a pipeline based on all learned data to generate questions that an LLM will never be able to answer?
- \[Memorization\] LMs are proud of their memorization ability of seen data, which is found to be limited in the multiple-answer case ([ICN](https://arxiv.org/abs/2410.02284)). Also, it cannot be denied that LMs can make mistakes on seen questions. Can this be all attributed to forgetting? Or is this an architectural issue in LM's memorization of knowledge?
- \[Fine-granularity\] LMs in deployment require following lots of constraints, such as system prompt and personal preference. Are current LMs able to follow millions of constraints assigned to them? If not, how can we improve this through data, model architecture, or learning paradigm?

MISC
------
![image](https://github.com/user-attachments/assets/b94ac6b9-4ae4-433b-b090-0d7eb6c8166b)
[My Huggingface Repo](https://huggingface.co/KomeijiForce)

Collaboration
------
I am open to any type of collaboration! As long as you have the passion, I would not mind to support you from the very beginning! Please feel free to contact me via email! :-) **(Out of Bandwidth until 2025 March)**
