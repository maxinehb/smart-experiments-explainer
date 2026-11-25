# SMART Experiments: What Comes Next?

An interactive statistical explainer exploring Sequential Multiple Assignment Randomized Trials (SMARTs) as an alternative to traditional A/B testing when treatment decisions need to adapt to individual responses.

## Live Interactive Explainer

[**View the SMART Experiments Explainer**](https://maxinehb.github.io/smart-experiments-explainer/)

## Project Overview

Traditional randomized experiments typically assign participants to a treatment at the beginning of a study. SMART designs extend this framework by allowing subsequent treatment decisions to depend on participants' responses.

This project uses interactive animations, statistical explanations, and reproducible simulations to demonstrate how SMART designs work and how adaptive treatment strategies can be evaluated.

## Key Topics

- Traditional A/B testing versus sequential randomization
- Adaptive treatment strategies
- The BestFIT clinical trial as a motivating example
- Inverse probability weighting
- Weighted versus unweighted estimation
- Monte Carlo simulation
- Type I error and multiple testing
- Confidence interval coverage

## Technical Skills Demonstrated

- Statistical modeling and inference
- Experimental design
- Monte Carlo simulation
- Data visualization
- Interactive statistical communication
- Reproducible research

## Tools and Technologies

- R
- Quarto
- HTML, CSS, and JavaScript
- SVG animations

## Repository Structure

| File | Description |
|---|---|
| `SMART_Explainer.qmd` | Quarto source document containing explanations and R code |
| `index.html` | Rendered interactive explainer |
| `styles.css` | Custom visual styling |
| `README.md` | Project documentation |

## Reproducibility

The explainer can be rendered using R and Quarto. The source document contains the statistical simulations and supporting code.

To render the document, run the following command in the terminal:

`quarto render SMART_Explainer.qmd`

The simulated results are intended for educational purposes and do not represent actual patient-level clinical trial findings.

## Author

**Maxine Hakimi-Bulson**

M.S. in Data Science Candidate, Emory University

B.S. in Applied Mathematics and Statistics, Emory University

[LinkedIn](https://www.linkedin.com/in/maxine-hakimi-bulson/) | [GitHub](https://github.com/maxinehb)