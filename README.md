# Fatality_Rate_Analysis_TMU

SECTION 1 : MISSING_VALUES_VISUALIZATION_INSIGHTS.

*Fixing Missing Values in ratedeaths
The EDA report showed that 6.7% of ratedeaths was missing. Since this variable tracks fatality rates, I had to handle it properly.
*Three Fixes I Considered
NOTE 1:
Removing missing values –-- Easy but deletes useful data.
Mean/Median Imputation –--- Keeps data but may distort trends.
Regression Imputation –---- Predicts missing values based on real case & death data.
------------------------------------------------------------------------------
Since ratedeaths is strongly linked to totalcases and numdeaths, I used Regression Imputation to fill gaps without distorting trends.

------------------------------------------------------------------------------
After fixing the missing values, I created a scatter plot to check how cases, deaths, and fatality rates interact.
-------------------------------------------------------------------------------

Some provinces had low case counts but high death rates, meaning healthcare struggles might be an issue.

Larger & darker dots = More deaths ( These areas need urgent medical support. )

High cases don’t always mean high fatality rates, proving that healthcare systems matter more than just case numbers.
--------------------------------------------------------------------------------
NOTE 2 :Final Thoughts

At the end of the day, numbers don’t lie. Some places struggled more, and the data shows exactly where help is needed. We can’t just look at total cases we need to focus on deaths and healthcare gaps.

1. Prioritize medical aid in high-fatality areas. 
2. Improve healthcare access where deaths are high, even if cases are low. 
3. Make smarter decisions using real data, not just assumptions.
--------------------------------------------------------------------------------

NOTE 3 : THE GOAL ISN'T JUST ANALYZING DATA. IT'S MAKING SURE IT LEADS TO ACTION
