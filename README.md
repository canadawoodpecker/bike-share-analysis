# bike-share-analysis
## Executive Summary
This project analyzes Cyclistic’s bike‑share trip data from 2016 to 2025 to understand how annual members and casual riders differ in their usage patterns and how these behaviors have evolved over time. Historically, annual members have shown consistent commuting‑oriented behavior—weekday usage, peak travel hours, shorter trip durations, and evenly distributed station activity—while casual riders have exhibited leisure‑focused patterns with longer rides and concentrated usage near tourist destinations.

However, starting in 2020, casual rider behavior changed dramatically. Their weekday usage increased, trip durations shortened, and station usage diversified, indicating that many casual riders began using Cyclistic for routine mobility rather than occasional recreation. Casual ridership also grew significantly faster than member ridership during this period.

These shifts present a strong opportunity for Cyclistic: a large portion of casual riders now behave similarly to annual members and may be highly receptive to targeted membership‑conversion campaigns. The insights from this analysis provide a data‑driven foundation for designing marketing strategies that increase annual memberships and support Cyclistic’s long‑term growth.

## Background Information
Cyclistic, a leading bike-share program in Chicago, has grown significantly since its launch in 2016, now operating more than 5,800 bicycles across nearly 700 docking stations. Its inclusive fleet—featuring traditional bikes as well as reclining, hand tricycle, and cargo options—serves a diverse customer base that rides for both leisure and daily commuting. Historically, Cyclistic’s marketing strategy has focused on broad awareness and flexible pricing plans, offering single-ride passes, full-day passes, and annual memberships. While this approach has expanded ridership, internal financial analysis shows that annual members generate substantially higher long-term profitability compared to casual riders.

## Stretigic Goal of Marketing
Recognizing this opportunity, Lily Moreno, Director of Marketing, has set a strategic goal to increase annual memberships by converting existing casual riders. Casual riders already know the Cyclistic brand and actively use its services, making them a promising segment for targeted marketing interventions. To design an effective conversion strategy, the marketing analytics team must first understand how casual riders and annual members differ in their usage patterns, motivations, and engagement behaviors.

## Key Question
How do annual members and casual riders use Cyclistic bikes differently?
This project analyzes Cyclistic’s historical trip data to uncover behavioral trends, usage frequency, ride duration, temporal patterns, and station preferences across rider types. These insights will inform the development of a data-driven marketing strategy aimed at converting casual riders into committed annual members. These findings will directly influence Cyclistic’s future marketing direction and will serve as the evidence base for executive approval of the proposed membership growth strategy.

## Limitations
Cyclistic’s trip data is fully anonymized, meaning the analysis is based solely on ride behavior rather than customer‑level information. Because personally identifiable data is not included:  
  
* Trip records cannot be linked to individual riders or purchase histories
* We cannot determine whether casual riders live in the service area
* We cannot identify riders who repeatedly buy single‑ride passes
* Customer segmentation (demographics, residency, frequency profiles) is not possible

Additionally, usage ratios—such as 70% member trips vs. 30% casual trips—reflect trip volume, not the number of unique riders.
We cannot conclude whether members ride more because there are more members, or because each member rides more frequently.  
  
All insights therefore rely on observable trip patterns (duration, time of day, station usage), not customer‑level targeting.  

## Considerations to analysis
* Product Context - Bicycle usage is highly seasonal and strongly influenced by weather conditions.
* Location Context - Chicago experiences harsh winters, which significantly affect bike‑share activity and must be considered when interpreting trends.
* Time Context - The dataset spans 2016 to the present, a period that includes the COVID‑19 pandemic. Pandemic‑related behavioral changes must be accounted for in the analysis.
* Analytical Focus - Because the business goal is to convert casual riders into annual members, the analysis centers on comparing these two groups.
* Methology & Skills - The goal of this project is to identify patterns and trends by analyzing large‑scale historical trip data. Python is the primary tool for data manipulation, cleaning, and visualization due to its efficiency and flexibility with diverse data formats. Excel is used for initial inspection and manual preprocessing of complex or inconsistent data.

## Key tools and libraries include:
* Jupyter Notebook with Python Technology - Jupyter Notebook with Python is ideal for exploring messy, multi‑year datasets through interactive, step‑by‑step analysis and data visualization.
* Python libraries: NumPy, pandas, datetime, openpyxl
* Visualization: Matplotlib, seaborn, IPython
* Excel: Manual review and preprocessing of raw CSV structures with formulas and functions such as vlookup
* These tools support the extraction, cleaning, transformation, and visualization of Cyclistic’s trip data, enabling a comprehensive and reliable analysis.
