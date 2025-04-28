# MIST-4610-Group-5-Project-2

# Team Name:
Group 5
# Team Members:
1. Jeremiah Doherty: https://github.com/jeremiahd72
2. Chase Ratelle: https://github.com/Bubb-Rattle
3. Isaac Self: https://github.com/mrslimeballl
4. Alex Vuong: https://github.com/akv74603
5. Deven Yadav: https://github.com/dmy41514

# Dataset Title:  EZAUCR Arrest Statistics
Source: https://catalog.data.gov/dataset/ezaucr-arrest-statistics

# Manipulation to the Data Set:
There were no changes made to the original CSV file of this dataset, as after careful analysis done by our group, we determined that the dataset was organized well and did not need any modificatios to suit the questions we would come with based off this dataset.

# Dimensions of Dataset:
Number of Rows: 201,342

Number of Columns: 37

# Summary of Variables:

# 1. Administrative & Demographic Information
CYear – Calendar year of the reported data

State_Name – Name of the U.S. state or jurisdiction

Full_name – Full jurisdiction name (can be redundant with State_Name)

PART – UCR classification (1 = serious/violent/property crimes, 2 = other)

Total Population – Total population of the reporting area

Coverage Indicator – Percentage of the jurisdiction's population covered by data

# 2. Aggregated Offense Totals
Total Arrests – Total number of arrests recorded

Violent Crime Index – Aggregate total of violent crime arrests

Property Crime Index – Aggregate total of property crime arrests

# 3. Violent Crimes
Murder/nonneg. mans. – Arrests for murder and non-negligent manslaughter

Rape – Arrests for rape

Robbery – Arrests for robbery

Aggravated assault – Arrests for aggravated assault

# 4. Property Crimes
Burglary – Arrests for unlawful entry with criminal intent

Larceny-theft – Arrests for theft (excluding motor vehicle theft)

Motor vehicle theft – Arrests for stolen vehicle incidents

Arson – Arrests for deliberately setting property on fire

# 5. Additional Assaults and Public Threats
Other assaults – Arrests for non-aggravated or simple assaults

Weapons – Arrests involving illegal weapons use or possession

# 6. White-Collar and Property Offenses
Forgery and counterfeiting – Arrests for fraudulent documents

Fraud – Arrests for financial or identity fraud

Embezzlement – Arrests for misusing or stealing entrusted funds

Stolen property – Arrests for handling or possessing stolen goods

Vandalism – Arrests for willful property destruction

# 7. Vice and Morality Offenses
Prostitution/commercialized vice – Arrests related to prostitution and related activities

Sex offenses (other) – Non-rape sexual crimes (e.g., indecent exposure)

Gambling – Arrests for illegal gambling activities

# 8. Drug and Alcohol-Related Offenses
Drug abuse violations – Arrests related to illegal drugs (possession, trafficking, etc.)

Driving under the influence – DUI/DWI arrests involving alcohol or substances

Liquor laws – Arrests for violations of alcohol-related laws

Drunkenness – Arrests for public intoxication

# 9. Public Order and Behavioral Offenses
Disorderly conduct – Arrests for disruptive or inappropriate behavior in public

Vagrancy – Arrests involving homelessness or loitering

All other offenses – Miscellaneous uncategorized arrests

# 10. Juvenile-Specific Offenses
Curfew and loitering – Juvenile arrests for violating curfews or loitering laws

Runaways – Incidents involving juveniles reported as runaways

# General Overview:
EZAUCR Arrest Statistics provides comprehensive arrest data compiled from U.S. law enforcement agencies across years and states. It includes arrest counts by offense type, population coverage, and category-level crime breakdowns. These insights are critical for criminal justice analytics, resource allocation, and policy evaluations.

# Research Questions:

# Question 1:
Out of robbery, fraud, or murder, which crime decreased the most at a nationwide level over 20 years? To what extent?
# Why is this question important?
Seeing different crime trends helps evaluate how effective crime prevention programs are and how societal behaviors are changing. From an economic standpoint, crimes impose costs and reductions in crime can save public resources that can be used to improve society in other areas. Trends can be studied to determine which crimes have the greatest economic impact. Policywise, lawmakers are able to assess which policies are working and where resources need to be shifted to prevent  further damages based on the crime. Policies supporting the reduction of the crime that’s decreased the most over the last 20 years can be used as a model to decrease other crimes.

# Question 1 Visualizations:
# Graph for Robberies:
<img width="626" alt="Screenshot 2025-04-28 at 4 42 49 PM" src="https://github.com/user-attachments/assets/4bde89ba-0eeb-4872-9f97-f23c64c27c88" />

# Graph for Fraud:
<img width="621" alt="Screenshot 2025-04-28 at 4 45 15 PM" src="https://github.com/user-attachments/assets/d67b553c-12d9-470c-b8ce-e1859a63dae8" />

# Graph for Murder:
<img width="622" alt="Screenshot 2025-04-28 at 4 46 01 PM" src="https://github.com/user-attachments/assets/d290e590-bcc0-4e2c-986a-b784dc37b78d" />

# Graph comparing Robbery, Fraud, and Murder:
<img width="626" alt="Screenshot 2025-04-28 at 4 46 37 PM" src="https://github.com/user-attachments/assets/245ee5bd-6b51-45ab-9926-c8df1c335c4c" />

# Question 1 Insights and Analysis:
First Graph – Robbery in Georgia (1994-2014):
Robbery peaked highly in the mid-90s (17K+ robberies).
Sharp drop around 1998–2000.
Mid-2000s (2006–2008) saw another mini-spike, but not bad as the ‘90s peak.
After 2008, consistent downhill slide — less robberies.

Second Graph – Fraud Arrests in Georgia (1994-2014):
Fraud was a big topic of discussion in the late '90s (over 90K arrests).
2000–2005: Still in a bad spot, but not as crazy as before
2006 and beyond: Massive drop
and color fades because numbers went way down. Fraud was by far the biggest issue.

Third Graph – Murder Arrests in Georgia (1994-2014):
Pretty stable most years (around 2,000–2,500 murders).
But 2002 was a bad year with a massive spike — 3,300 arrests.
After 2002, it goes back down to normal levels, no crazy changes besides 2002.

Fourth Graph – Robbery vs Fraud vs Murder Comparison:
Fraud is the biggest crime of them all — it dominated Georgia’s crime stats.
Robbery was bad but not even close to fraud levels.
Murder was the smallest problem.
All three started trending down hard after mid-2000s.

Biggest Overall Insights:
Georgia’s biggest crime issue was fraud, not robbery or murder.
Crime in general spiked in the late '90s.
Mid-2000s = tipping point where crime stats finally started to crash down.
2010s = Safer now in Georgia compared to the chaos of the '90s.

# Summary of Question 1:
Between 1994 and 2014, Georgia experienced significant declines in robbery, fraud, and murder arrests. Fraud arrests were overwhelmingly the largest issue, peaking in the late '90s before rapidly declining after 2006. Robbery showed two peaks but generally followed a downward trend, while murder rates stayed fairly stable except for a major spike in 2002. Overall, all three crime types dramatically decreased by the early 2010s.


# Question 2:
What are the Top 10 Counties in Georgia with the highest number of fraud arrests?
# Why is this question important?
Understanding which counties in Georgia have the highest fraud rates is crucial for several reasons. Georgia consistently ranks among the states most affected by fraud, with over 177,000 reported cases between April 2023 and March 2024, equating to 1,605 cases per 100,000 residents—62% higher than the national average . Identifying the top counties impacted by fraud enables state and local governments, law enforcement agencies, and community organizations to allocate resources more effectively, tailor public awareness campaigns, and implement targeted prevention strategies. For instance, counties like Fulton, DeKalb, and Bibb have been highlighted for higher crime rates, including fraud-related offenses . By focusing on these areas, authorities can address the specific types of scams prevalent there, such as imposter scams, identity theft, and real estate fraud, thereby enhancing consumer protection and reducing financial losses for residents.​

# Question 2 Visualizations:
<img width="621" alt="Screenshot 2025-04-28 at 5 16 09 PM" src="https://github.com/user-attachments/assets/50d978a8-e135-4e8d-9e6a-ced8efb7dcc9" />

# Question 2 Insights and Analysis:
1. Musco​gee County is a clear outlier, with 32,457 reported fraud cases, significantly higher than any other county. This suggests either a very large problem locally, greater reporting efficiency, or perhaps demographic or economic factors contributing to more fraud activity.

2. Fulton County (Atlanta’s county) follows, but with a noticeable gap at 22,819 cases. Given Fulton’s large population and urban setting, high fraud numbers are expected, but the fact that Muscogee surpasses it by almost 10,000 cases is striking.

3. Dougherty and Clayton Counties are also high on the list with 20,277 and 19,472 cases, respectively. These counties might be facing significant socioeconomic challenges that can correlate with higher fraud incidence.

4. Steep drop after the top 4: After Clayton County, the number of fraud cases sharply drops to 9,333 in Cobb County — less than half the fraud volume of the top counties.

# Biggest Overall Insights:

Muscogee County should be a primary focus for fraud prevention and enforcement efforts.

Resource allocation could be more weighted toward the top four counties, as they collectively represent a massive portion of total fraud activity.

Understanding causes (e.g., economic hardship, scam tactics, online fraud) in the top counties could help proactively manage risks elsewhere.
