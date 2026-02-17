# Cookie Cats A/B Test Analysis

**Statistical evaluation of gate placement impact on mobile game player retention**

## 📊 Project Overview

Analyzed 90,189 Cookie Cats mobile game players to determine whether moving a progression "gate" from level 30 to level 40 affects player retention. Used statistical hypothesis testing in R to evaluate business impact.

## 🎯 Key Findings

- **Day 7 retention decreased by 0.82 percentage points** when gate moved to level 40 (p = 0.00155)
- Effect is **statistically significant** and translates to estimated **$246K annual revenue loss**
- **Heavy players (51+ rounds) most affected**: 4.6pp retention drop vs 0pp for casual players
- **Recommendation**: Keep gate at level 30 to protect high-value user segment

## 🛠️ Technical Approach

- **Statistical Methods**: Two-proportion z-tests, confidence intervals, effect size analysis
- **Tools**: R (tidyverse, ggplot2, broom), R Markdown
- **Analysis Type**: A/B testing, segmentation analysis, business impact modeling
- **Sample Size**: 90,189 players (44,700 control, 45,489 treatment)

## 📁 Repository Contents

- `cookie_cats_analysis.Rmd` - R Markdown analysis document
- `cookie_cats_analysis.html` - Rendered HTML report
- `cookie_cats.csv` - Source dataset
- `README.md` - This file

## 🔗 View Analysis

Download the HTML file and open in your browser to see the full interactive report.

## 💡 Skills Demonstrated

- A/B test design and analysis
- Statistical hypothesis testing
- Data visualization (ggplot2)
- Business impact quantification
- Stakeholder communication
- R programming & R Markdown

---

**Author**: Alexandra Lugo | [Portfolio](https://alexandralugo.com) | [LinkedIn](https://linkedin.com/in/lugoalexandra)
