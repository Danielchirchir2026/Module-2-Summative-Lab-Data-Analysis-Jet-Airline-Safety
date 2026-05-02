# Module-2-Summative-Lab-Data-Analysis-Jet-Airline-Safety
This is the repository for DSF-PT15M2 > Assignments > Summative Lab: Data Analysis Jet Airline Safety
# Aircraft Injury and Damage Analysis

## Project Overview
This project analyzes aviation accident data to investigate factors influencing aircraft damage and passenger injury outcomes. The analysis focuses on aircraft size, make, and operational characteristics.

## Key Questions
- Which aircraft makes show lower fatal and serious injury rates?
- How do outcomes differ between small and large aircraft?
- What operational factors affect injury and destruction rates?

## Summary of Findings
- Small aircraft generally show higher variability and higher fatal/serious injury fractions than large aircraft.
- Several small and large aircraft makes consistently appear among the lowest risk group.
- Critical factors influencing injury severity include phase of flight and number of engines.
- Phases such as takeoff and landing are associated with higher injury risk.
- Aircraft with more engines tend to show lower injury severity and variability.

## Recommendations
- Low risk small and large aircraft makes identified in the analysis should be prioritized as safer performers.
- Aircraft makes showing high injury variability or destruction rates warrant further review.
- Safety interventions should focus on high risk flight phases and aircraft configurations with lower redundancy.


## Exploratory Data Analysis & Visualizations

### 1. Lowest-Risk Aircraft Makes
The chart below shows the lowest-risk aircraft makes based on the mean fraction of passengers who were fatally or seriously injured.

![Lowest Risk Aircraft Makes](images/10%20Lowest-Risk%20Makes.png)

---

### 2. Injury Severity by Number of Engines
This visualization illustrates how the fraction of fatal or serious injuries varies by the number of engines, highlighting safety differences across aircraft configurations.

![Injury Severity by Number of Engines](images/Distribution%20of%20Fatal%20or%20Serious%20Injury%20Fraction%20by%20Number%20of%20Engines.png)

---

### 3. Injury Severity by Phase of Flight
The figure below shows the fraction of serious injuries by phase of flight, indicating that certain phases present higher passenger risk.

![Injury Severity by Phase of Flight](images/Serious%20Injury%20Fraction%20by%20Phase%20of%20Flight.png)


## Data Source
Aviation accident data provided in `AviationData.csv`.

## Tools Used
- Python
- Pandas
- Seaborn & Matplotlib
- Jupyter Notebook
