Exercises and assignments for HCDE410: Human Data Interaction. Everything here is a work in progress unless otherwise noted :)
#HCDE410
Files for HCDE410 - Assignment A2
# A2 — Exploring sources of bias in data

**Dataset:** Wikipedia Talk Labels: Toxicity dataset
**Source:** https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Toxicity/4563973 (pulled 2026-10-25)
**License / terms of use:** Public Domain

**Dataset:** Wikipedia Talk Labels: Aggression dataset
**Source:** https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Aggression/4267550 (pulled 2026-10-25)
**License / terms of use:** Public Domain

**Dataset:** Wikipedia Talk Labels: Personal attacks dataset
**Source:** https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Personal_Attacks/4054689 (pulled 2026-10-25)
**License / terms of use:** Public Domain

## Questions I asked
1. What is the gender distribution of the annotator workers?
2. What is the distribution of the annotator workers by first language?
3. What is the distribution of the annotator workers by age group?
4. What is the distribution of the annotator by education level?
5. Do any of the fields in the all_annotators dataset have missing data? If so, which fields, and what % of the rows contain missing values?
6. How do the summary statistics change when the duplicates in the datasets are not changed?
7. In general, how do the demographics of these workers compare to those of English-speaking internet users overall? Why would it matter if the worker demographics don't match the demographics of the intended end users of the Perspective API?
8. What issues might arise if the Wikipedia Talk Corpus was used to train a machine learning-driven "hostile speech detector" that could be used on any website or social media platform?
9. 

## How to re-run
Open `A2.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).
