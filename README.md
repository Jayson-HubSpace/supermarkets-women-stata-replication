README
Regression Results for the Main Tables and Figures

Paper: Supermarkets benefit women by reducing time spent on unpaid housework
without lowering nutritional quality

1. Contents

This folder contains six Stata SMCL log files documenting the regression
results for four tables and two figures in the main text of the paper.

- Replication_Table_1.smcl
  Table 1: Effects of supermarket access on women's food shopping and cooking
  time, using binary, count, and categorical treatment specifications.

- Replication_Table_2.smcl
  Table 2: Effects on women's food shopping and cooking time by urban or rural
  residence and by baseline traditional market access.

- Replication_Figure_3.smcl
  Figure 3: Dynamic effects of supermarket access on women's food shopping
  and cooking time, measured in logarithms and minutes per day.

- Replication_Table_3.smcl
  Table 3: Effects on individual energy and macronutrient intake, in total and
  from unprocessed, moderately processed, and highly processed foods.

- Replication_Table_4.smcl
  Table 4: Effects on dietary quality, measured by the Dietary Diversity Score
  (DDS), Chinese Food Pagoda Score (CFPS), and Dietary Nutrient Density Score
  (DNDS).

- Replication_Figure_4.smcl
  Figure 4: Dynamic effects on women's participation in farm and nonfarm work
  and on the hours per day devoted to these activities.

The figure logs report the numerical estimates underlying the corresponding
panels, including standard errors and 95% confidence intervals. Each log also
provides information on the outcomes, model specifications, and sample sizes.

2. Data Source and Access

The analysis uses the China Health and Nutrition Survey (CHNS), a longitudinal
survey collecting individual, household, and community information in China.
The regressions use the 2004, 2006, 2009, and 2011 waves. The time-use analyses
focus on women, while the dietary analyses include adult women and men.
Individual and household information is linked to community-level measures
of supermarket access.

Researchers can obtain publicly available CHNS data by registering through
the official CHNS website and following its data download procedures:
https://www.cpc.unc.edu/projects/china

Access to restricted data, including community-level information used in this
study, requires a separate application and approval from the CHNS team.
Researchers should consult the website for the applicable access procedures
and data use requirements.

Under the CHNS data use agreement applicable to this study, we are not
permitted to redistribute the underlying research data. These data are
therefore not included with the six result files. Interested researchers
must obtain the necessary data access directly from CHNS.

CHNS Agreement for the Use of Confidential Data:
https://chns.cpc.unc.edu/wp-content/uploads/Data-Use-Agreement-CHNS_20201020.pdf

3. Software

The regression results were produced using Stata 18 (Stata/MP).

4. How to Read the Files

Open Stata and drag and drop any of the six .smcl files into the Stata window
to view its contents in the Stata Viewer. Alternatively, select File > View
and choose the file.

You can also open a log from Stata's Command window. For example, after
setting the working directory to this folder, type:

    view "Replication_Table_1.smcl"

The saved results can be read without access to the underlying datasets and
without rerunning the regressions.
