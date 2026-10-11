# Aviation Accident Data Analysis: Jet Airline Safety

## 1. Business Understanding

This project investigates aviation accident records to identify aircraft makes and models associated with more favorable recorded accident outcomes. The analysis supports an insurance client's assessment of aircraft safety.

The project evaluates small aircraft and large passenger aircraft separately and investigates factors potentially associated with accident severity.

## 2. Business Questions

1. Which eligible aircraft makes and models have relatively low recorded fatal or serious injury rates?
2. Which eligible models have relatively low aircraft destruction rates?
3. Which factors are associated with differences in recorded accident outcomes?
4. How reliable are these comparisons given the available sample sizes and missing data?

## 3. Data Sources

The analysis uses the aviation accident dataset from Kaggle, including AviationData.csv and USState_Codes.csv.

The main dataset contains aviation accident records. The state-code dataset provides geographic reference information.

## 4. Data Cleaning

The cleaning process includes:

- Inspecting data types and missing values.
- Standardizing column names and text fields.
- Converting accident dates and numeric injury counts.
- Identifying exact duplicate records.
- Restricting the analysis to records from 1983 onward.
- Reviewing aircraft eligibility and category classifications.
- Creating measures for aircraft destruction and recorded injury outcomes.

## 5. Exploratory Data Analysis

The analysis examines accident patterns over time, summarizes injury and damage outcomes, and compares eligible aircraft makes and models.

Groupby aggregations and descriptive statistics are used to compare outcome rates and sample sizes.

## 6. Factors Associated with Accident Outcomes

The analysis investigates weather conditions and phase of flight, along with any additional factors supported by the available data.

Visualizations and summary tables provide evidence for the reported relationships.

## 7. Aircraft Recommendations

### Small Aircraft

Recommendations will be based on observed outcome rates, sufficient sample sizes, and the reliability of the available data.

### Large Passenger Aircraft

Recommendations will be evaluated separately using the same principles, with attention to the differences between aircraft categories.

## 8. Limitations

The dataset records accidents rather than all flights or flight hours. Consequently, the analysis cannot directly estimate the probability of an accident per flight.

Missing records, reporting practices, aircraft usage, and differences in operating conditions may affect comparisons.

Associations identified through descriptive analysis should not automatically be interpreted as causal relationships.

## 9. Conclusion

The final conclusions and aircraft recommendations will be based on the calculated results, supporting visualizations, sample-size checks, and documented limitations.
