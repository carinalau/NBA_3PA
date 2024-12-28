# Effect of Three-Point Attempts on NBA Game Outcomes
This project investigates the causal relationship between the number of three-point attempts by NBA teams and their likelihood of winning games. The analysis was conducted as part of INFO 3900: Causal Inference at Cornell University and received a grade of 97/100 as the final project.

## Project Overview
- Causal Question: Does shooting more three-pointers increase the likelihood of winning in the NBA?
- Dataset: NBA game statistics from 2010–2024, including metrics such as three-point attempts (3PA), turnovers (TOV), offensive rebounds (OREB), and blocks (BLKA).
- Methodology:
  - Developed a Directed Acyclic Graph (DAG) to identify relevant covariates.
  - Used nearest neighbor matching to estimate the Average Treatment Effect on the Treated (ATT).
  - Conducted regression analysis to evaluate the causal effect of three-point attempts on game outcomes.
- Key Findings
  - High-volume three-point shooting (defined as >27.5 attempts/game) does not significantly increase a team’s probability of winning, with an ATT estimate close to zero (-0.0097).
  - Covariates such as turnovers, offensive rebounds, and blocks were adjusted for in the analysis to control confounding effects.

## Tools and Libraries
- R: Data processing, matching analysis, and regression modeling.
- MatchIt: For nearest neighbor matching.
- dplyr: For data manipulation.
- ggplot2: For data visualization.

## Highlights
- This project provides valuable insights into modern NBA strategies and their effectiveness.
- Includes detailed data cleaning and visualization, ensuring reproducibility and transparency.
- Combines data science and causal inference principles to address real-world sports analytics questions.

## Credits
This project was completed by:

- Carina Lau
- Daanyal Agboatwalla
- Harshini Cheruvu
- Josh Green
- Kate Li

INFO 3900: Causal Inference, Cornell University.
