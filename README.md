# Zero-GCCD
This is a code implementation for **Zero-GCCD** (Zero-shot Generalized Continual Category Discovery using Foundational Models) paper, presented in [INES 2025](http://www.ines-conf.org/ines-conf/2025final.html) conference. <br>

## Abstract
Generalized category discovery (GCD) aims to classify instances into both known and previously unseen categories, posing a challenge for traditional classification systems constrained by fixed label sets. In this work, we explore the potential of foundational models (FMs) to address this problem through zero-shot prompting. We showed that a stand-alone LM-based visual question answering (LVQA) model can perform GCD task with acceptable performance, even without training or labeled data for feature extraction. To enhance GCD performance, we introduced two lightweight, continual learning (CL)-based approaches: similarity-driven and prompt-driven. Our proposed methods operate in generalized continual category discovery (GCCD) framework. The similarity-driven refines predictions by computing cosine similarity between the predicted class and previously identified categories, while the prompt-driven dynamically updates the prompt with newly discovered categories, allowing the LVQA model to make informed judgments. Both methods require minimal to no computational overhead. Experimental results confirmed the effectiveness of our proposed approaches, highlighting the superior robustness of the prompt-driven method compared to both the similarity-driven approach and the benchmark, even in scenarios with and without human-assisted label refinement. <br>

## Cite
Please refer to this repository and cite our publication when using this work. <br>
```
@Citation will be added soon.
```
