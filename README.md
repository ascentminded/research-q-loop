# research-q-loop
Learning to ask good research Qs and follow them up | Exploring open-source biomed datasets
---
*This repo is for the following loop: Take a dataset > Come up with a hypothesis > Conduct experiments > Interpret the results > Conduct followups... in small, bite-sized chunks*
*The end goal is to hone my research thinking capabilities through deliberate practice*
*As a bonus, I use the opportunity to explore a technique or method that's well suited, and I want to learn*

[NOTE:] I'll be cleaning up and updating the results in the corresponding ppt under `presentations/`.

## ACTG-175
---
The first project is the ACTG-175 dataset. A pre-cleaned clinical trial dataset on AIDS patients, it's ideally suited for both survival analysis and causal inference.
- In `actg_explore_206_11_1.ipynb`, I chose a subset of the full dataset to study the effect of Didanosine *(ddl)* treatment on top of the basic Zidovudine (ZDV) drug treatment.
- Using this as the treatment effect, I taught myself the fundamentals of HTE analysis, a subset of Causal Forest modelling, to see if there was a subgroup that responded better to treatment ('high-benefit')


