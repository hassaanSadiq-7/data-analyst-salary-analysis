# data-analyst-salary-analysis
EDA on 9K+ data industry job records to uncover salary trends across experience, role, and work setting using Pandas, Matplotlib &amp; Seabor
# Data Analyst Salary Analysis

I wanted to understand what actually drives salary differences in data-related jobs, so I picked up a public dataset from Kaggle and dug into it using Python and Pandas.

## The dataset

I used the "Jobs and Salaries in Data Field" dataset from Kaggle (link below). It originally had 9,355 rows, but after checking for duplicates I found that over 4,000 of them (about 43%) were exact repeats. I dropped those, leaving 5,341 clean, unique records to work with.

Dataset source: https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data

## What I looked at

- Basic stats on salary (mean, median, spread)
- How salary changes with experience level
- How much job category (e.g. Data Analysis vs Machine Learning) affects pay
- Whether remote, hybrid, or in-person work makes a difference
- The overall shape of the salary distribution

## What I found

The average salary in the cleaned dataset came out to around $146K, but the median was lower, at $140K. That gap told me the data is right-skewed — most people cluster in a normal range, but a handful of very high earners pull the average up.

Experience level made the biggest difference. Entry-level averaged about $85K, while executives averaged close to $188K — a bit more than double.

Job category mattered too, sometimes more than I expected. Machine Learning/AI roles averaged around $170K, while Data Analysis roles (my own target field) averaged about $107K. That's roughly a $64K gap, which made me think about upskilling toward ML/AI down the line as a way to grow earnings, not just waiting on seniority.

One thing that surprised me: hybrid roles paid noticeably less on average ($89K) than both fully remote ($141K) and fully in-person ($154K) roles. I expected remote to be highest, or at least for hybrid to land somewhere in the middle, not at the bottom.

Job titles also showed a huge gap — roles like Analytics Engineering Manager averaged close to $400K, while entry-level titles like Insight Analyst or Compliance Data Analyst were closer to $45K–$50K.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, in a Jupyter notebook.

## Files

- `analysis.ipynb` – the notebook with all the code, charts, and my notes as I went
- `README.md` – this file

## Running it

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook analysis.ipynb
```

---
This is one of a few small projects I'm building as I move toward a data analytics career.
