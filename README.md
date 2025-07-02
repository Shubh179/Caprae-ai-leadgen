# Caprae Capital – AI Lead Recommendation Tool

This repository contains my submission for Caprae Capital's AI Challenge. It presents a practical AI-enabled tool to help founder-led businesses identify companies that are operationally and financially aligned for acquisition, partnerships, or strategic outreach.

## What's Inside

| File                                  | Description                              |
|---------------------------------------|------------------------------------------|
| Caprae_Leadgen_Notebook.ipynb         | Full implementation in a Jupyter notebook |
| ML_Leadgen_Companies_1000.csv         | Synthetic dataset used for demo purposes |
| Caprae_Implementation_OnePager.pdf    | One-page report outlining the approach    |
| video_link.txt                        | Contains Loom walkthrough video link      |

## Approach Summary

This tool combines unsupervised machine learning with structured business logic to produce highly relevant company recommendations.

- **KMeans Clustering**: Used to segment companies based on revenue, growth rate, country, and domain.
- **Rule-Based Filtering**:
  - Matches the same country and domain
  - Revenue within ± ₹50 Cr of user input
  - Positive growth rate only

This hybrid method ensures both data-driven insight and commercial practicality.

## Setup Instructions

To use this notebook:

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/caprae-ai-leadgen.git
   ```

2. Install required Python packages:
   ```
   pip install pandas numpy scikit-learn matplotlib
   ```

3. Open and run `Caprae_Leadgen_Notebook.ipynb` in Google Colab or Jupyter Notebook.

## Video Walkthrough

A brief walkthrough of the project and rationale can be found here:  
https://www.loom.com/share/b073ffd19f434604a646d57ff07b1f72

## Author

[Shubh Shah]  
[shubhshah453@gmail.com]
