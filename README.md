# Exploratory-Data-Analysis-of-Marketing-Campaign
The main objective is to analyze the marketing dataset, to uncover insights to optimize campaign performance and to discover location-based trend which are impacting to their success.


## Dataset overview: 
This is a marketing campaign dataset which has 200,005 rows by 13 columns. These datasets include impression, clicks, costs, campaign_id and lots more. The key performance metrics analyzed are Return on investment(ROI), Click-Through Rate(CTR), Cost Per Clicks(CPC), Conversion Rate.

## Data Cleaning and Exploration

The Issues Identified:

- They were inconsistent data format(Acquisition-cost datatype was object because it had the dollar sign($) and (comma),instead of (int) 

- The duration was saved as objects. it had an alphabet(30 days)

- The date was saved in string format.

## Data Cleaning Steps:

- I changed the datatype from Object to int for Acquisition Cost and Duration.

<img width="1245" height="132" alt="Screenshot 2025-08-08 002847" src="https://github.com/user-attachments/assets/734bfb7f-3cb1-4351-b265-49e9f589870a" />

- I changed the Date datatype from object to datetime

<img width="1301" height="124" alt="Screenshot 2025-08-08 003628" src="https://github.com/user-attachments/assets/7c9a8d80-bdb7-40ac-9c9a-70ed80479c6e" />
  
- I also created new metrics for CPC and CTR

<img width="1271" height="329" alt="Screenshot 2025-08-08 004049" src="https://github.com/user-attachments/assets/d53af720-cb8a-4d00-9073-382f7a234862" />

## Insights and Visualisation

- To visualize, the alredy cleaned data, i plotted a Bar chat that displays the ROI values. The x-axis represents campaign type while the y-axis represent average ROI. The chart compares the average Return on Investment for different campaign types.

<img width="529" height="538" alt="Screenshot 2025-08-08 005526" src="https://github.com/user-attachments/assets/7730233f-fdc3-45e3-a663-784c09da8087" />

- The chart below is a Heatmap. This charts shows the location and channel_Used generated the highest ROI. These helps identify regional strength and underperforming channels.

  <img width="792" height="478" alt="Screenshot 2025-08-08 010207" src="https://github.com/user-attachments/assets/43a2a76b-e544-4f6b-9a5f-05163aeed7db" />

- The chart above is a line chart. The chart displays the CTR percentage for each month. The x-axis represents month while the y-axis represent CTR. The chart identifies seasonal trends and period of High or low engagement.

  <img width="658" height="440" alt="Screenshot 2025-08-08 010703" src="https://github.com/user-attachments/assets/f9e7e38f-83d7-4bdd-a669-a4531e99c6f3" />

- The histogram shows that conversion rates are evenly spread across campaign. No significant spikes or dips, meaning no extreme outlier.
  
  <img width="724" height="477" alt="Screenshot 2025-08-08 010918" src="https://github.com/user-attachments/assets/300f6493-ca47-4323-9203-9325a4a132e8" />
  
## Conclusion
Based on the analysis of campaign performance data, several strategic opportunities have been used to enhance overall marketing effectiveness and to increase the return on investment (ROI). 
- Firstly, it is recommended to increase budget allocation to high-performing channels that consistently yield strong ROI. These channels have shown the ability to attract and convert the target audience efficiently and should be prioritized in future budget planning.

- Secondly, there is a need to refine targeting strategies in underperforming geographic locations. By leveraging localized insights and demographic data, campaigns can be tailored more precisely to the preferences of audiences in these areas, potentially unlocking untapped market potential and improving regional conversion rates.

- Thirdly, the analysis revealed varying levels of engagement with different creative assets. This highlights the importance of adjusting campaign creatives based on content engagement trends. Creative elements that resonate with the audience such as specific messaging, visuals, or formats should be scaled, while less effective assets should be revised or phased out.

In summary, by reallocating resources to the most impactful channels, optimizing location-specific targeting, and iteratively improving creative content, the marketing team can significantly enhance campaign efficiency, boost customer engagement and ultimately drive higher revenue growth.






