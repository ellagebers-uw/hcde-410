# A3 — Watching the Machine

HCDE 410 Assignment 3, in which **AI is the subject of study, not the author.** I investigated the reliability and reproducibility of large language models (LLMs) through a small mixed-methods study, then reflected on what it means for trustworthy research.

## What this notebook is

`A3_watching_the_machine_starter.ipynb` has five parts:

1. **Prior practice** — a short written reflection on how I currently use LLMs and what I assume about their reliability.
2. **Reproducibility probe**

   The prompt:
    
   “What is the percentage of families who speak a language other than English at home in Wenatchee, WA. What language is
   most spoken outside of English, and what percentage of homes speak that language? What is the median income for families
   in Wenatchee, and how does it differ from the median income of households across the State?” 
    
   Was run three times in Claude and one time in ChatGPT. Each run was logged verbatim in a spreadsheet (prompt, model,
   version, timestamp, output, verified, notes), exported as `a3_runs.csv` and loaded into a pandas DataFrame. A short helper
   cell summarizes the log (run count, distinct outputs, verification tally).
    
    **Prompt Answer Key (held as ground truth):**
    - Languages other than English spoken at home in Wenatchee, Washington: 29.0% ± 3.2%.
    - Second highest type of language spoken at home in Wenatchee, Washington: Spanish at 27.6% 
    - Median Income for Families in Wenatchee, WA: $92,619.
    - Median Household Income in Wenatchee, WA: $73,040 ± $5,455
    - Median Household Income in Washington state: $101,946 ± $719
    - Difference in Median Househole Income: $28,906 or 33.04% 
    
    **Data Sources for Answer Key**
    Wenatchee city, Washington Cencus Bureau Profile:
    - https://data.census.gov/profile/Wenatchee_city,_Washington?g=160XX00US5377105#populations-and-people
    - https://data.census.gov/profile/Wenatchee_city,_Washington?g=160XX00US5377105#income-and-poverty

4. **Observation** — watched a user use the same prompt with an LLM of their choosing (Gemini) (with permission, no audio/video, nothing personal or sensitive), took timestamped field notes, and grouped them into themes in a second spreadsheet, exported as `a3_codes.csv`.
   
5. **Synthesis & reflection** — brought the probe and observation together into one account about trustworthy, reproducible research and what I will change in my own AI use.


6. **Competency declaration & AI use** — stated which course competencies the work demonstrates (*qualitative & mixed-methods inquiry*, *reproducible analysis*, *ethical & societal reasoning*) and disclosed any AI use per course policy.

## How to run

Open `A3_watching_the_machine_starter.ipynb` and run the cells. The only dependency is:

- `pandas`

The notebook does not fetch external data. It loads two CSV files you create from your own runs and field notes: `a3_runs.csv` and `a3_codes.csv`. Header-only templates of both are included in this folder; open them in Google Sheets or Excel, fill them in, download as CSV, and upload them here with the same names.

## License

Released under the MIT License — see [`LICENSE`](./LICENSE).
