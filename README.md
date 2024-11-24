# Loan_Approval_Rate_Analysis
This project focuses on analyzing loan approval rates based on various customer attributes, such as demographic factors, flags indicating provided contact information, and socioeconomic parameters. It is designed to provide insights into factors influencing loan approval rates, ultimately assisting loan approval departments in improving decision-making and operational efficiency.
</br><img src="https://github.com/user-attachments/assets/ddbe46db-0fda-4935-b642-67cd562634c4" alt="Dashboard_image"></img>
## Table of Contents
<ul>
  <li>Overview</li>
  <li>Features</li>
  <li>Data Sources</li>
  <li>Tools and Technologies Used</li>
  <li>Visualizations</li>
  <li>Key Insights</li>
  <li>How to Use</li>
  <li>Future Enhancements</li>
  <li>Acknowledgments</li>
</ul>

## Overview
Loan approval is a critical process in the financial sector, requiring thorough analysis to reduce risks and improve customer satisfaction. This project provides a detailed analysis of loan approvals based on:
<ul>
  <li>Flags (e.g., provided phone/email, reachable mobile).</li>
  <li>Demographic attributes (e.g., occupation, region ratings, family size).</li>
  <li>Education and income-related factors.</li>
</ul>
The project also includes Power BI dashboards that visually demonstrate the key metrics and insights.

## Features
<ul>
  <li>Loan approval rates based on:</li>
    <ul>
      <li>Contact information flags.</li>
      <li>Occupation and demographic details.</li>
      <li>Region and city ratings.</li>
    </ul>  
</ul>
<ul>
  <li>Visualizations for:</li>
  <ul>
    <li>Approval rates by loan type (e.g., cash vs. revolving loans).</li>
    <li>Demographic segmentation (e.g., age, gender, family size).</li>
    <li>Education level and its influence on approvals.</li>
  </ul>
</ul>
<ul>
  <li>Key performance indicators (KPIs):</li>
  <ul>
    <li>Default rates.</li>
    <li>Portfolio health.</li>
    <li>Customer behavior trends.</li>
  </ul>
</ul>

## Data Sources
The project uses a dataset containing various attributes of loan applicants, such as:
<ul>
  <li>Dataset from Kaggle: <a  href="https://www.kaggle.com/datasets/shreshthvashisht/bank-loan-case-study-dataset?select=previous_application.csv">Bank Loan Case Study Dataset</a>, providing comprehensive loan application data for analysis.</li>
  <li>Flags (e.g., work phone, mobile, email).</li>
  <li>Demographic details (e.g., gender, occupation type, family size).</li>
  <li>Loan-related details (e.g., loan type, interest rates, loan amount).</li>
  <li>Region ratings for understanding geographic influences.</li>
</ul>

## Tools and Technologies Used
<ul>
  <li>Power BI: For creating interactive dashboards and visualizations.</li>
  <li>GitHub: For version control and portfolio showcase.</li>
</ul>

## Visualizations
### Power BI Dashboards
1. **Loan Status by Education Level:**
    <ul><li>Shows the approval and rejection rates segmented by education levels.</li></ul>
2. **Loan Approvals by Occupation:**
    <ul><li>Analyzes loan status across different occupations (e.g., laborers, managers, sales staff).</li></ul>
3. **Loan Type and Approval Rates:**
    <ul><li>Compares approval rates for cash and revolving loans.</li></ul>
4. **Region Ratings and Loan Approvals:**
    <ul><li>Evaluates the influence of region ratings on approval rates.</li></ul>
5. **Total Loans by Contract Types:**
    <ul><li>Provides a breakdown of loan distribution by contract type.</li></ul>
## Sample Graphs
<ul>
 </br><li><strong>Area Chart:</strong> Loan approval rate by flags (e.g., FLAG_WORK_PHONE, FLAG_EMAIL).</li>
   <img src="https://github.com/user-attachments/assets/5a38abb4-e0f1-4e15-8108-41f3b60210c2"></img>
  </br><li><strong>Line & Clustered Column Chart:</strong> Loan approvals by education level and region rating.</li>
   <img src="https://github.com/user-attachments/assets/f587037e-0a82-4a21-98b8-c133da8666fa"></img>
  </br><li><strong>Pie Chart:</strong> Loan type distribution.</li>
  <img src="https://github.com/user-attachments/assets/ef6cb51d-c3f4-4f55-b810-19ab2a1912e9"></img>
  </br><li><strong>Donut Chart:</strong> Average age vs. approval rate.</li>
   <img src="https://github.com/user-attachments/assets/e2e9a6c6-67cb-4347-9479-9abc1f438464"></img>
</ul>
 
 
  
## Key Insights
1. **Higher approval rates** for customers with complete contact information (e.g., reachable mobile and email provided).
2. **Education matters:** Customers with higher education levels tend to have better approval rates.
3. **Geographic influence:** Regions with higher ratings exhibit better approval chances.
4. **Occupations** such as managers and high-skill tech staff are more likely to get approvals compared to laborers or security staff.

## How to Use
### Pre-requisites
1. Install Power BI Desktop for viewing the .pbit file.
2. Clone the repository and explore the code and visualizations.

### Steps
1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/Loan_Approval_Rate_Analysis.git
```
2. Open the Power BI dashboard (Loan_GIt.pbit) to view interactive visualizations.

## Future Enhancements
1. Machine Learning: Integrate predictive models to estimate loan approval chances.
2. Advanced Visualizations: Add drill-through pages and deeper insights in Power BI.
3. Integration: Link the dashboard to live data sources for real-time updates.
## Acknowledgments
Special thanks to the Kaggle for free datasets and Power BI community for enabling the creation of this project.




