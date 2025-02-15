# About the project 

Project done by: 
- Sheryll Dumapal 

## Business Case 
Shark attacks pose a serious risk to surfers and swimmers, impacting tourism, local economies, and public safety. My project focuses on developing data-driven insights and potential solutions to enhance shark awareness and mitigation strategies.

## Problems  
- Lack of real-time shark detection solutions.
- Inconsistent and incomplete historical data.
- Difficulty in predicting attack-prone locations and times.

## Oppertunity 
- Use data analytics to identify attack patterns.
- Develop AI-powered shark tracking applications.
- Provide governments and businesses with actionable insights to improve public safety.

## Hypotheses
- Hypothesis 1: Certain activities, such as surfing, increase the likelihood of shark encounters.
- Hypothesis 2: Attacks are more frequent in the afternoon due to increased human activity.
- Hypothesis 3: Some regions have a higher concentration of attacks due to environmental conditions.

### Hypothesis 1: Certain activities, such as surfing, increase the likelihood of shark encounters.

Surfing accounts for 1,150 shark attack cases, the highest among all recorded activities.
Swimming is the second most affected activity with 631 incidents.
Spearfishing follows with 307 cases.
Other high-risk activities include Wading (145), Diving (132), and Snorkeling (126).
Lower-risk activities include Boogie Boarding (53), Windsurfing (22), and Kayaking (10).
Conclusion: Surfing has the highest recorded shark encounters, supporting the hypothesis that it increases the likelihood of an attack. This is likely due to surfers spending extended periods in the water, making movements that could attract sharks, and being present in coastal areas where sharks hunt.

### Hypothesis 2: Attacks are more frequent in the afternoon due to increased human activity.

Afternoon: 659 cases – highest attack frequency.

Midday: 591 cases – second highest.

Morning: 391 cases.

Dusk: 277 cases.

Dawn: 117 cases.

Night: 90 cases.

Unknown time: 1,453 cases (highlighting reporting gaps).

Conclusion: The hypothesis is supported. Shark attacks peak in the afternoon and midday, aligning with the periods of highest human water activity. This pattern suggests that the increased presence of people in the ocean during these hours contributes to the likelihood of shark encounters.

### Hypothesis 3: Some regions have a higher concentration of attacks due to environmental conditions.
Analysis:

Countries with the highest attacks:

United States: 1,683 cases (highest globally).
Australia: 608 cases.
South Africa: 303 cases.
Other notable locations: Brazil (97), Bahamas (97), New Zealand (61), Reunion (55), New Caledonia (53), Papua New Guinea (49), Mexico (48).
USA-specific data:

Florida: 908 cases (highest within the USA).
Hawaii: 226 cases.
California: 183 cases.
Australia-specific data:

New South Wales: 200 cases.
Western Australia: 140 cases.
High-risk locations:

New Smyrna Beach, Florida: 182 cases (highest globally, known as "Shark Bite Capital of the World").
Daytona Beach, Ponce Inlet, and Melbourne Beach are also high-risk locations.

## Conclusion: 
Certain regions, particularly Florida (USA), New South Wales (Australia), and South Africa, show a higher concentration of shark attacks. This supports the hypothesis that environmental factors (such as warm coastal waters, high marine biodiversity, and popular surf spots) contribute to increased shark activity. Additionally, improved reporting and human presence in the water influence the numbers.

## Next Steps and Implementation Plan 
- Enhance data collection and classification accuracy.
- Develop a real-time shark monitoring system.
- Collaborate with stakeholders to implement safety measures.

## Why This Matters and the Big Picture Vision 
Shark attacks not only impact individuals but also have broader economic and environmental consequences. By leveraging data-driven insights, I aim to create safer ocean environments while promoting coexistence with marine life.

## Methodology 
To ensure a structured and data-driven approach, the following methodology was applied to test each hypothesis:

- Dataset Selection: Used the cleaned dataset (cleaned_data.pkl) containing shark attack records. Focused on data from the 19th to 21st centuries to ensure reliability.
- Data Importing & Preprocessing: Loaded the dataset using pandas, checked for missing values, and conducted exploratory data analysis (EDA) to understand patterns.
- Activity Classification & Analysis: Extracted and analysed the "Cleaned_Activity" column, counting the number of shark attacks per activity type. Surfing, swimming, and spearfishing were compared to determine high-risk activities.
- Time-Based Analysis: Extracted the "Time" column and grouped attacks into different time periods (Morning, Midday, Afternoon, Dusk, Dawn, Night). Counted occurrences to identify peak attack times.
- Geographical Distribution Analysis: Used the "Country" and "State" columns to count attacks by location. Identified the top 10 countries and high-risk states (USA, Australia) to determine regional concentration.
- High-Risk Location Identification: Analysed specific locations with high shark activity (e.g., New Smyrna Beach, Florida), considering environmental factors such as warm coastal waters and high marine biodiversity.
- Trend Analysis & Comparison: Used matplotlib and seaborn for visualisation, comparing attack trends across activities, time periods, and geographical locations to validate each hypothesis.
- Missing Data Handling: Considered 1,453 cases with unknown time and ensured valid comparisons in the analysis.
- Visual Validation: Utilised pre-generated charts and tables to support findings and confirm statistical patterns.
This structured methodology ensures that conclusions are drawn based on actual data trends rather than assumptions.

# Functions 
- Data cleaning and preprocessing functions.
- Visualization functions for attack trends.
- Statistical analysis for hypothesis testing.

# Problems and Technical Challenges 
- Data Issues: Missing and inconsistent data made it challenging to establish patterns. I resolved this by normalizing and filling gaps using statistical methods.

- Complexity of Shark Species Classification: Many attack records lacked clear species identification, which affected accuracy. I mitigated this by categorizing them based on available descriptions.

- Timeframe Selection: Filtering relevant time periods required careful consideration to balance data accuracy and representativeness.

# Deliverables  
- Presentation link: https://docs.google.com/presentation/d/1l3DNc6utO-Tkynjjr5XsAR8GYVs2QHLGYXhtc02mE8I/edit#slide=id.g2af7b6d980b_0_24