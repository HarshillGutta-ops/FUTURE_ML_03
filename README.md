# Resume / Candidate Screening System

---


## Dataset

Monster.com Job Postings Dataset from Kaggle

- Source: https://www.kaggle.com/datasets/PromptCloudHQ/us-jobs-on-monstercom
- Contains real job postings with titles, descriptions, locations and sectors
- Used to extract required skills and screen candidates against real job roles

---

## System Modules

- Module 1 — Setup and Configuration
- Module 2 — Load and Explore Job Postings
- Module 3 — Text Preprocessing and Skill Extraction
- Module 4 — Sample Candidate Resumes (8 candidates)
- Module 5 — Job Role Selection and Candidate Screening
- Module 6 — Skill Gap Analysis
- Module 7 — Visualizations (6 graphs)
- Module 8 — Multi-Role Screening Report
- Module 9 — Final Business Report

---

## Skills Dictionary

The system tracks 60+ skills across these categories:

- Programming: Python, Java, JavaScript, SQL, R, C++, Scala and more
- Data and ML: TensorFlow, PyTorch, scikit-learn, pandas, numpy, Spark
- Cloud and DevOps: AWS, Azure, GCP, Docker, Kubernetes, Git
- Databases: MySQL, PostgreSQL, MongoDB, Redis, Elasticsearch
- Visualization: Tableau, Power BI, Matplotlib
- Soft Skills: Communication, Leadership, Agile, Scrum, Project Management

---

## Scoring Formula

| Component | Weight | Description |
|---|---|---|
| TF-IDF Similarity | 50% | Overall text relevance between resume and job |
| Skill Match % | 50% | Percentage of required skills present in resume |
| Final Score | 0-100 | Combined weighted score for ranking |

---

## Visualizations

| Graph | What It Shows |
|---|---|
| Visualization 1 | Job market overview — top categories and skills per posting |
| Visualization 2 | Top 25 most in-demand skills across all job postings |
| Visualization 3 | Candidate ranking dashboard with gold, silver, bronze medals |
| Visualization 4 | Skill gap heatmap — required skills vs each candidate |
| Visualization 5 | Candidate skill profile — total vs job-matched skills |
| Visualization 6 | Score breakdown — similarity, skill match, final score per candidate |

---

## Sample Output

```
SCREENING RESULTS
Rank  Candidate            Similarity    Skill Match   Final Score
1     Emma Davis           45.20         80.00         62.60
2     Alice Johnson        42.10         75.00         58.55
3     David Lee            38.90         60.00         49.45
4     Henry Brown          35.20         50.00         42.60
5     Grace Kim            28.40         40.00         34.20
```

---

## Business Value

| Metric | Impact |
|---|---|
| Screening time | Reduced from hours to seconds |
| Bias | Removed from initial screening |
| Skill gaps | Clearly identified for each candidate |
| Ranking | Objective and score-based |
| Coverage | Screens unlimited candidates simultaneously |

---

## How to Run

Install dependencies:

pip install scikit-learn pandas numpy matplotlib seaborn nltk

Open resume_screening_system.ipynb in VS Code with the Jupyter extension and run all modules in order. Update the dataset path in Module 1 before running.

---

## Tech Stack

Python 3.13 · scikit-learn · NLTK · pandas · numpy · matplotlib · seaborn

---

## Author
Gutta Harshill