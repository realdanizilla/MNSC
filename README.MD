# Law Firm Contract Profitability Analysis


- [Law Firm Contract Profitability Analysis](#law-firm-contract-profitability-analysis)
  - [Project Objective](#project-objective)
  - [Project Structure and Steps](#project-structure-and-steps)
  - [Tools and Techniques Utilized](#tools-and-techniques-utilized)
  - [Specific Results and Outcomes](#specific-results-and-outcomes)
  - [What I Have Learned From This Project](#what-i-have-learned-from-this-project)
  - [How to use this repository](#how-to-use-this-repository)



## Project Objective
The goal of this project was to create a data model for a law firm to track and analyze the profitability of individual contracts. This model integrates customer, contract, and financial data to assess the impact of attorney costs, expenses, and indirect costs on the profitability of contracts by partner.

[Back to Top](#law-firm-contract-profitability-analysis)

## Project Structure and Steps
1. **Understading Business Needs**
   - Met with partners and attorneys to understand current ways of working and what was expected for the solution
   - Agreed on scope of solution and required features

2. **Data Collection and Consolidation**:
   - Gathered contract data, attorney billing records, expenses, and customer details.
   - Grouped data by law firm partners, their clients, and specific contracts.

3. **Profitability Calculation**:
   - Developed a rationale to calculate profit using:
     - **Revenue**: Income from each contract.
     - **Attorney Costs**: Hours billed by attorneys on the contract.
     - **Upfront & Other Expenses**: Direct contract-related costs.
     - **Indirect Costs**: Applied as a percentage of total revenue.
     - **Net Expenses**: Total expenses after adjustments.

4. **Classification and Analysis**:
   - Created dashboards to display rankings and profitability.
   - Classified contracts as either “Loss” or “With Revenue” based on net outcomes.
   - Identified key revenue thresholds, such as contracts with revenue greater than $3000 or $5000.

5. **Visualization and Reporting**:
   - Generated graphs and tables to provide insights into attorney performance, contract success rates, and profitability distribution.

[Back to Top](#law-firm-contract-profitability-analysis)

## Tools and Techniques Utilized
- **Microsoft Excel**: Used for data consolidation, calculations, and reporting.
- **Business Analytics**: Discussed and understood specific business needs, pains and existing records and datasets to envision the solution.
- **Data Modeling**: Merged multiple datasets to create a unified view of contract profitability.
- **Dashboards**: Created visualizations for easy tracking and decision-making.

[Back to Top](#law-firm-contract-profitability-analysis)

## Specific Results and Outcomes
- **Profit Distribution**: The analysis showed that a significant number of contracts (especially private ones) were operating at a loss, with zero or negative revenue after expenses.
   - **Loss-Making Contracts**: Several contracts were classified as "Loss" due to high attorney costs and upfront expenses without generating sufficient revenue.
   - **Without Revenue**: Some contracts had no recorded revenue at all, resulting in negative profitability due to incurred expenses.

- **Partner and Customer Profitability**: 
   - Tracked performance by **Partner** and **Customer**, helping identify which attorneys and partners were associated with the most profitable contracts.
   - Identified patterns where **litigation contracts** tended to have higher associated costs and lower profitability compared to consultancy contracts.

- **Threshold Analysis**:
   - Few contracts surpassed the **$3000 and $5000 revenue thresholds**, highlighting the need for better client and contract management strategies.
   - **Private contracts** had a lower success rate compared to **public contracts** in generating significant profits.

- **Cost Breakdown Insights**:
   - **Attorney Costs** were found to be a major component of the overall contract costs, directly impacting profitability.
   - **Indirect Costs** were applied as a percentage of revenue, which had a compounding effect on contracts with low revenue.
   - The firm identified areas where expenses could be optimized, particularly around upfront and operational costs.

- **Profitability Metrics**:
   - **Best Performing Contracts**: Public contracts with revenue-generating clients, where revenue offset attorney costs and indirect expenses.
   - **Worst Performing Contracts**: Private contracts with no revenue or minimal activity, leading to financial losses.

- **Impact on Firm Operations**:
   - Enabled partners and attorneys to monitor profitability per contract and make informed decisions about clients and cases.
   - Allowed the finance team to focus on high-performing contracts and suggest strategies to manage low-performing ones.
   - Highlighted a need to manage **multiple attorney lines and partner-specific client management**, which was reflected in the consolidated reporting.

- **Resulting Software Solution**:
   - The original Excel-based model evolved into a **custom software tool** for tracking profitability, automating cost calculations, and generating financial reports.
   - This software is still in use today, replacing manual reporting processes with automated insights, contributing to better contract management and profitability tracking.

[Back to Top](#law-firm-contract-profitability-analysis)

## What I Have Learned From This Project 
- **Business Acumen**: Learning to ask the right questions in the right way to extract business needs, expectactions and pains, as well as thinking as a business owner to make decisions on how to set up the solution
- **Data Modeling**: Gained experience in consolidating data from multiple sources into a coherent analytical model.
- **Profitability Analysis**: Developed skills in financial analysis, including indirect cost allocation and expense tracking.
- **Excel Dashboards and Reporting**: Improved capabilities in building Excel dashboards and generating insightful reports.
- **Process Automation and Systematization**: Contributed to the transition from Excel-based reports to a software solution, enabling long-term usage and efficiency improvements.

[Back to Top](#law-firm-contract-profitability-analysis)

## How to use this repository

1. Clone the Repository git clone https://github.com/realdanizilla/MNSC.git

2. Open the main Excel File and start at sheet "Start"
   
3. Select between adding more contract information to the database or visualizing analysis
   
4. Explore views, rankings, analysis and graphs to understand how profitability is calculted and how is works for different contracts.

5. Add information for a new contract and see how it adds to the analysis and graphs

[Back to Top](#law-firm-contract-profitability-analysis)
