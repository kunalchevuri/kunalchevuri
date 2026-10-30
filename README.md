## Kunal Chevuri

High-school researcher in Prosper, Texas. I work on machine learning that has
to survive contact with messy real data — degraded imagery, heterogeneous
health records, inconsistently disclosed financial filings — and on releasing
the code and data that let someone else check the result.

[ORCID 0009-0006-6322-8143](https://orcid.org/0009-0006-6322-8143) ·
[LinkedIn](https://www.linkedin.com/in/kunal-chevuri-19b74a287/)

### Research code

| Repository | What it is |
|---|---|
| [flood-vlm-degradation-robustness](https://github.com/kunalchevuri/flood-vlm-degradation-robustness) | Under combined blur, darkness and noise a fine-tuned vision-language model missed every severe flood, while a frozen I-JEPA encoder held steady under noise. IEEE MIT URTC 2026. |
| [roadway-flood-synthetic-to-real](https://github.com/kunalchevuri/roadway-flood-synthetic-to-real) | The synthetic-to-real gap in small VLMs for flood monitoring, with a 1,005-image generated dataset ([Zenodo, CC BY 4.0](https://doi.org/10.5281/zenodo.23251071)). IEEE CogMI 2026. |
| [african-agrifood-investment-dataset](https://github.com/kunalchevuri/african-agrifood-investment-dataset) | Open deal-level dataset of African agrifood investment, 2015–2025 — 1,060 records, 389 deals, 30 countries, 121 named sources — plus the pipeline that rebuilds it. IEEE BigData 2026 High School Symposium. |
| [federated-learning-composite-masking](https://github.com/kunalchevuri/federated-learning-composite-masking) | The Masking Gap: how far a single combined wellness score hides a person's worst individual health problem, across 8,353 NHANES records. IEEE BIBM 2026 (ARRL-Health). |
| [federated-learning-health-robustness](https://github.com/kunalchevuri/federated-learning-health-robustness) | 624 experiments on 382,709 CDC health records showing plain averaging recovers 79–98% of the advantage claimed by far more complex federated aggregation methods. |
| [question-evasion-detection-LLM-framework_research](https://github.com/kunalchevuri/question-evasion-detection-LLM-framework_research) | Training-free LLM-as-judge scoring of how evasively executives answer analyst questions, over 3,350 earnings-call exchanges at $0.0038 each. |

### How these repos are built

Each research repository ships its own verification script that re-derives
every number in the corresponding paper from the raw results and reports any
disagreement — including the null results. Datasets are released under CC BY
4.0 with permanent DOIs where the data is ours to publish; code is MIT.
