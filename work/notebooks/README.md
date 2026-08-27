# work/notebooks/ — All Weekly Assignments

This folder contains every notebook I built during the 8-week FlyRank ML Internship. Each week built on the previous one.

---

## Notebooks

| Week | File | What I Did |
| :--- | :--- | :--- |
| 1 | `w01_research_question.ipynb` | Framed the research question and picked my lane |
| 2 | `w02_ml_task_framing.ipynb` | Defined the ML task — ranking/scoring problem |
| 3 | `w03_data_contract.ipynb` | Built a data contract and ran the leakage trap |
| 4 | `w04_baseline_score.ipynb` | Created a baseline scoring rule and ranked queue |
| 5 | `w05_model.ipynb` | Trained a Random Forest model vs baseline |
| 6 | `w06_validation_audit.ipynb` | Ran time-aware split and leakage audit |
| 7 | `w07_action_playbook.ipynb` | Built an action playbook for content teams |
| 8 | `capstone.ipynb` | Final capstone notebook — all results pulled together |

---

## What I Found

| Metric | My Model | Baseline |
| :--- | :--- | :--- |
| RMSE | 23.32 | 10.91 |
| MAE | 19.34 | 9.58 |
| R² | -0.198 | N/A |

**The baseline won. The model didn't beat it.**

I kept this result honest and reported it in my paper.

---

## Actionable Content Found

| Action | Count |
| :--- | :--- |
| Optimize Content | 72 |
| Monitor | 71 |
| No Action | 857 |

---

## How to Run

1. Open any notebook in Colab
2. Set `HF_TOKEN` as a Colab secret
3. Request access to `FlyRank/internship-warehouse`
4. Run all cells

---

## Related

- Live paper: [SyedSaadullah999.github.io/FlyRankW1/](https://SyedSaadullah999.github.io/FlyRankW1/)
- Full repo: [github.com/SyedSaadullah999/FlyRankW1](https://github.com/SyedSaadullah999/FlyRankW1)

---

*Completed August 2026*
