# MMR2 coverage: Birmingham, Surrey and England

**Question:** How has MMR2 coverage changed in Birmingham and Surrey compared with England and the 95% target, 2010/11 to 2024/25?

**Data:** OHID Fingertips, indicator "Population vaccination coverage - MMR2 (2 doses, 5 years old)", retrieved October 2026. Open Government Licence.

**Method:**
1. Compiled Fingertips data for Birmingham, Surrey and England (15 years, 45 records) into one pandas data frame.
2. Validated the data against the source download.
3. Derived the gap to the 95% target, the gap to England, year-on-year change and 95% confidence-interval flags.
4. Published the results as a Tableau dashboard.

**Findings:** Birmingham fell 12.0 points to 75.5% (19.5 below target). Surrey rose 16.9 points to 87.0% (8.0 below target).

**Limits:** This is area-level data, so it cannot show why coverage changed or show differences within an area.

**Files:**
- mmr2_analysis.ipynb: the analysis code
- mmr2_clean_data.csv: the cleaned data
- dashboard_screenshot.png: the finished dashboard

**Re-run:** Install the libraries imported at the top of the notebook (pandas), then run the notebook from top to bottom.

**Dashboard:** https://public.tableau.com/app/profile/oluwadamilola.olaiya7614/viz/MMR2coveragedashboard/Dashboard1

**Author:** Damilola Olaiya, MSc Health Promotion and Public Health, Ulster University.
