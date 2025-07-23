# Effects of Characteristics on Penguin Body Mass
This project analyzes how sex, species, and flipper length influence the body mass of penguins using ANOVA and linear modeling in R. The goal was to identify statistically significant predictors of body mass using model comparison techniques such as AIC, BIC, and adjusted R².

## Summary
- Data Source: [Palmer Penguins Dataset (Gorman et al., 2014)](https://allisonhorst.github.io/palmerpenguins/)
- Sample Size: 300 penguins (random subset)
- Transformations: Log transformations on body mass and flipper length to approximate normality
- Statistical Tests: ANOVA for group differences; Levene’s test for equal variances; Shapiro test for normality
- Model Selection: Compared 7 linear models with combinations of sex, species, and flipper length
- Best Model: The model including all three predictors minimized AIC/BIC and had the highest R²

## Tools & Packages
- R & RMarkdown
- `ggplot2`
- `tidyverse`
- `psych`
- `car`
- `bookdown`
- `knitr`

## Project Structure
- `penguin_body_mass_analysis.Rmd`: Main RMarkdown file with exploratory analysis, modeling, and diagnostics
- `dataset_151.csv`: Cleaned dataset used for modeling
- `penguin_body_mass_analysis.html`: Knitted HTML report showing full analysis and plots
- `README.md`: Project overview and deliverables

## Modeling Results
The linear model including sex, species, and flipper length as predictors produced the best results with the lowest AIC/BIC values and the highest R². Residual diagnostics confirmed normality and homoscedasticity, validating model assumptions.

## How to Run
To reproduce this project:
1. Clone this repository or download the ZIP
2. Open `penguin_body_mass_analysis.Rmd` in RStudio
3. Make sure `dataset_151.csv` is in the same folder
4. Knit the RMarkdown file to generate plots and tables

## View Project Deliverables
- [Full analysis report (HTML)](https://sath-parimi.github.io/penguin-body-mass/penguin_body_mass_analysis.html): Knitted RMarkdown showing all code, diagnostics, and visualizations

## Author
**Sathvika Parimi**  
B.S. Financial Mathematics and Statistics, UC Santa Barbara
