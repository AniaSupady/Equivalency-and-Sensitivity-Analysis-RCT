# Equivalency and Sensitivity Analysis in Randomized Controlled Trials (RCTs), by Ania Supady

link to Colab: https://github.com/AniaSupady/Equivalency-and-Sensitivity-Analysis-RCT/blob/main/Equivalency_and_Sensitivity_Analysis.ipynb

**Exploring the Significance of Temperature under Conditions of Compromised Equivalency**

Randomized Controlled Trials (RCTs) are fundamental in scientific research for evaluating the effectiveness of interventions or treatments. The core principle of an RCT lies in its ability to randomly assign participants into treatment and control groups, ensuring that any differences observed in outcomes can be confidently attributed to the intervention rather than other factors. This randomization process helps mitigate biases and ensures the validity of the study's findings.

However, even in well-designed RCTs, issues can arise during data collection or experimental execution that compromise the comparability between treatment and control groups. One critical aspect is the equivalency between these groups. Equivalency ensures that both groups are similar in all aspects except for the treatment they receive. Any deviations from equivalency can lead to misleading conclusions about the treatment effect.

In our demonstration, we illustrated a scenario where errors occurred in the experimental setup of an RCT. The experiment involved households randomly selected from different zip codes experiencing varying temperature levels, which inadvertently violated the equivalency principle. We showcased this by plotting temperature patterns using line plots and illustrating the distribution of climate categories across treatment and control groups using bar charts.

These visualizations highlighted the variability in temperature exposure across groups, indicating potential differences that could affect energy usage patterns. Such deviations from equivalency underscore the importance of statistical tests like t-tests and Levene's test to rigorously assess and address any discrepancies between treatment and control groups. These tests are essential for ensuring the robustness and validity of conclusions drawn from statistical models like PanelOLS, which rely on the assumption of equivalency to provide accurate insights into treatment effects.
