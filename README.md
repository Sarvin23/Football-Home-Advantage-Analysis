# Home Advantage in Football: Statistical Analysis

A statistical investigation into whether home advantage exists in football, using empirical match data from the 2020/21 Premier League season (no crowd due to COVID regulations) and the 2022/23 season (with crowd).

This project explores whether crowd presence significantly impacts home performance and whether home advantage is driven primarily by external factors or deeper structural influences in the game.

## Project Overview

Home advantage has long been a debated phenomenon in sports analytics. This project investigates whether playing at home provides a measurable performance advantage, and how much of that advantage is influenced by crowd presence.

To isolate the effect of crowd support, I have considered two contrasting seasons:

- 2020/21 Premier League → Matches played largely without crowds (COVID-19 period) 
- 2022/23 Premier League → Matches played with full stadium attendance

The analysis compares home performance across these two environments.

## Methodology

This project combines descriptive statistics and statistical testing:

### Descriptive Analysis

- Home win percentage comparison between seasons
- Home advantage distributions

### Statistical Testing

- F-Test assessing variance homogeneity 
- T-test to assess crowd effect on home advantage between the two seasons

## Key Findings

- A measurable difference exists between home performance in the two seasons analysed  
- The 2022/23 season (with crowd) shows stronger home advantage compared to the 2020/21 season (no crowd) 
- However, home advantage is not solely explained by crowd presence 
- Factors such as: 
  - Team strength 
  - Tactical decisions 
  - Referee Bias 
  - Player's psychological state 
  - Match-specific conditions

### Final Insight

Home advantage is a multifactorial phenomenon, not a single-cause effect \
While crowd influence appears statistically significant, it does not fully explain home performance differences 

## Software & Packages

- *R* (Version 4.4.1) 
- *tidyverse* 
- *ggplot2*

## Limitataions & Future Work

- Aggregate-level analysis may hide match-specific variations 
- Team strength imbalance not fully controlled 
- Future work should include: 
  - Match-by-match modelling 
  - Regression models controlling for team quality 
  - Advanced causal inference techniques

## Conclusion

Home advantage is not a simple outcome of crowd presence. \
While the analysis shows a statistically significant difference between seasons with and without crowds, the effect is modulated by multiple interacting variables such as team ability, tactics, and situational context. \
A more granular analytical approach would provide deeper insight into how and when home advantage truly manifests.

## References

- Neave, N., & Wolfson, S. (2003). *Testosterone, territoriality, and the "home advantage".* **Physiology & Behavior.**

- Nevill, A. M., Balmer, N. J., & Williams, A. M. (2002). *The influence of crowd noise and experience upon refereeing decisions in football.* **Psychology of Sport and Exercise.**
  
- Pollard, R. (2002). *Evidence of a reduced home advantage when a team moves to a new stadium.* **Journal of Sports Sciences.** 

- Pollard, R. (2008). *Home advantage in football: A current review of an unsolved puzzle.* **The Open Sports Sciences Journal.**

- Pollard, R., & Pollard, G. *Home advantage in soccer: A review of its existence and causes.*

## Author 
Sarvin Raaj Gunasekar\
B.Sc. Data Science\
Technical University of Dortmund
