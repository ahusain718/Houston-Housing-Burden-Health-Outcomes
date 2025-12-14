# Houston-Housing-Burden-Health-Outcomes
Houston Housing Burden and Health Outcomes Analysis
Executive Summary

This analysis investigates the relationship between housing cost burden and health outcomes across Houston ZIP codes. The findings indicate that higher housing cost burden is associated with worse physical health, mental health, and higher prevalence of diabetes, with statistically significant moderate correlations for all three outcomes. These results suggest that housing affordability is not just a housing issue but a public health concern, highlighting the need for targeted policy interventions.

Background

Houston is one of the most populous and economically diverse cities in the U.S., with over 2.3 million residents in the city proper. Key context:

Approximately 20–25% of Houston households live below the federal poverty line, with low-income and renter households disproportionately affected.

Houston is racially and ethnically diverse: roughly 45% Hispanic/Latino, 23% Black/African American, 7% Asian, and 25% non-Hispanic White.

Housing cost burden is widespread: many households spend more than 30% of their income on housing, limiting resources for healthcare, nutrition, and other essentials.

These socioeconomic pressures make Houston an ideal case to explore the intersection of housing and health outcomes.

Data & Methods

Data Sources

Housing: American Community Survey (ACS) 5-year estimates for ZCTA-level housing cost burden and income (https://data.census.gov/table/ACSDT1Y2024.B25070?q=ACS+Table+B25070). 

Health Outcomes: CDC PLACES data for ZCTA-level health indicators including poor physical health days, poor mental health days, and diabetes prevalence (https://data.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-ZCTA-Data-2025/qnzd-25i4/about_data).

Geography

ZIP Code Tabulation Areas (ZCTAs) covering Harris County, including the city of Houston.

Variables

Independent Variable: Percent of households spending >30% of income on housing.

Dependent Variables: Poor physical health days, poor mental health days, diabetes prevalence.

Analysis

Pearson correlation and linear regression (SciPy linregress) to quantify associations.

Scatter plots with regression lines to visualize trends.

Findings

Physical Health: Moderate positive correlation with housing cost burden, statistically significant (p < 0.05).

Mental Health: Moderate positive correlation with housing cost burden, statistically significant.

Diabetes Prevalence: Moderate positive correlation with housing cost burden, statistically significant.

Implication: ZIP codes with higher housing cost burden consistently experience worse health outcomes across multiple measures.

Visualizations include scatter plots for each health outcome with regression lines illustrating the relationship.

Policy Implications

Affordable Housing Expansion: Increasing availability of low-cost units could mitigate health risks.

Integrated Health & Housing Support: Programs that combine housing assistance with access to clinics or preventive care may improve outcomes.

Targeted Interventions: Focus on ZIP codes with both high housing cost burden and poor health indicators for maximum impact.

Limitations

Correlation does not imply causation.

ZCTA-level analysis may mask individual-level variability.

ACS and PLACES data are estimates with inherent sampling and reporting error.

Conclusion

Addressing housing affordability in Houston is critical not only for economic stability but also for public health, as moderate, statistically significant correlations link housing cost burden to poor physical health, mental health, and diabetes prevalence.
