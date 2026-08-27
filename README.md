# FlyRank ML Internship — My Capstone

**Author:** Syed Saadullah  
**Live Paper:** [SyedSaadullah999.github.io/FlyRankW1/](https://SyedSaadullah999.github.io/FlyRankW1/)

---

## What This Is

My completed capstone for the FlyRank ML Internship. I spent 8 weeks analyzing search data to understand ranking signals and build a system that prioritizes content for review.

**The honest result:** A simple rule-based baseline (RMSE: 10.91) beat my Random Forest model (RMSE: 23.32) across every validation test I ran. The model didn't win, and I'm reporting it that way.

---

## The Paper

The full research paper is live here:

**[https://SyedSaadullah999.github.io/FlyRankW1/](https://SyedSaadullah999.github.io/FlyRankW1/)**

It covers:
- What I was trying to figure out
- The data I used (78.8M rows)
- How I built the baseline and the model
- Why the baseline won
- What I'd recommend doing with the results

---

## What's in This Repo
FlyRankW1/
├── index.html # The deployed paper
├── assets/ # Charts from the paper
├── work/notebooks/ # All my weekly notebooks
│ ├── w01_research_question.ipynb
│ ├── w02_ml_task_framing.ipynb
│ ├── w03_data_contract.ipynb
│ ├── w04_baseline_score.ipynb
│ ├── w05_model.ipynb
│ ├── w06_validation_audit.ipynb
│ ├── w07_action_playbook.ipynb
│ └── capstone.ipynb
├── submission/
│ └── paper_url.txt # Points to the live paper
└── notebooks/ # Week 1-2 starter work
├── 01_first_look_and_discovery.ipynb
└── 02_your_first_readable_model.ipynb

text

---

## Weekly Notebooks

| Week | What I Did |
| :--- | :--- |
| 1 | Picked my lane and framed the research question |
| 2 | Framed the ML task — ranking/scoring problem |
| 3 | Built a data contract, defined features and label |
| 4 | Created a baseline scoring rule |
| 5 | Trained a Random Forest model |
| 6 | Audited validation and leakage |
| 7 | Built an action playbook for content teams |
| 8 | Final capstone notebook |

---

## Key Numbers

| Metric | My Model | Baseline |
| :--- | :--- | :--- |
| RMSE | 23.32 | 10.91 |
| MAE | 19.34 | 9.58 |
| R² | -0.198 | N/A |

**What this means:** The baseline was better. The model didn't beat it.

---

## How I Did It

- **Lane:** Ranking Signal Analysis
- **Data:** 78.8M rows from FlyRank's warehouse (sampled 1,000 rows)
- **Features:** impressions_log, ctr, days_in_data
- **Label:** gsc_avg_position
- **Model:** Random Forest (100 trees, max_depth=10)
- **Validation:** Random split, time-aware split, leakage audit

---

## Reproducibility

If you want to run this yourself:

1. Clone this repo
2. Open any notebook in Colab
3. Add `HF_TOKEN` as a Colab secret
4. Request access to `FlyRank/internship-warehouse`
5. Run all cells

---

## Resources

- [FlyRank ML Internship Dataset](https://huggingface.co/datasets/FlyRank/internship-warehouse)
- [FlyRank](https://flyrank.ai)
- [My Paper](https://SyedSaadullah999.github.io/FlyRankW1/)

---

## Acknowledgments

Built on the FlyRank ML Internship dataset — data provided by FlyRank.

---

## Author

Syed Saadullah  
August 2026

---

[Back to top](#flyrank-ml-internship--my-capstone)
