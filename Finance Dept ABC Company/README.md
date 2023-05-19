## 👉Business Case: 
The Finance Department of ABC Company maintains the invoice level details of all Payroll vendors and the cost associated with generating payslips for their employees. The Analyst receives invoices for each vendor and he fills all the details from each invoice in an excel sheet. He along with his colleagues collects similar data for all the countries and collates that information in one spreadsheet. The Global Finance leader along with other Country-level Finance leaders seeks data from these analysts to identify the Per Payslip Costs (PPC), that helps them in negotiating with vendors to reduce overall cost for the company. 

## 👉Problem Statement: 
Since data is being captured for different regions by separate analysts there is no way the Global leader could view the real-time global metrics, he has to wait for all the Country/Region-specific leaders to share their metrics with him and it only happens once a month. Your manager has got a request to build a global dashboard with some key metrics, that can be one source of truth for all regions. Your manager has assigned this task to you to collate all the Region-specific sheets in one file, clean all unwanted data and map it with the other master tables and create an automated dashboard solution that can serve all.

## 👉Dataset Description:
- Country-wise Detailed information on Vendor Charges/fees ( Regional Table1, Regional Table2)
- Country-wise Payslip Information (Payslips)
- Master Mapping table – Country – Region – Vendor Name (Mapping)
- Summary Table consists of Monthly summary of cost as well as payslip information

## 👉 𝐓𝐨𝐨𝐥𝐬 𝐔𝐬𝐞𝐝: 
- 𝐌𝐢𝐜𝐫𝐨𝐬𝐨𝐟𝐭 𝐏𝐨𝐰𝐞𝐫 𝐁𝐢 (with Some DAX functions)

## 👉 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐏𝐫𝐨𝐜𝐞𝐝𝐮𝐫𝐞:
 🍀Data Cleaning
 🍀Data Transformation
 🍀Data Modelling
 🍀Data Visualization
 🍀Findings
 🍀Recommendations

This project involves using a dataset provided by the Coding Invaders LMS platform. The dataset is then connected to Power BI Desktop for analysis. Power Query is utilized to transform and clean the data, ensuring it is in a suitable format for analysis.

## 👉Findings:

- February month has the highest Total Amount($) at 400,298,983M which was 126.72% higher than March.
- XDP accounted for 43.51% of the Total number of Invoices and highest Total Amount with 0 % Rebate.
- Total % Of Top two Vendors which are Xcs Corp and ABF Inc is  91.09%
- ABF Inc. catering the highest Count of Country at 18 and on second position XDP i.e 7 then SSN Intl i.e 5.
- USA had the highest Average of Payslip Count at 6,568,913.83. USA accounted for 35.78% of the Sum of Total Amount($).
- Serbia had the lowest Average of Payslip Count at 8.45, which was significantly lower.
- EMEA had the highest total Sum of Total Amount($) at 1.472M and lowest is LATAM
- North America had highest total amount than other regions.
- The highest scope for PPC negotiation lies for Xcs Corp & ABF Inc.
- DFG Corp, it has a presence in Morocco, Greece, and Russia, but there’s no amount or payslip information available for Greece and Russia.

## 👉Recommendations:

- Vendor Management: Strengthen relationships with vendors who are contributing highest in Total Amount and explore opportunities for negotiation to optimize pricing and maximize profitability.
- Country Focus: ABF Inc. caters to the highest Count of Country at 18, followed by XDP with 7 and SSN Intl with 5. Identify the reasons for ABF Inc.'s extensive reach and analyze the potential for expansion in other countries
- Regional Analysis: EMEA had the highest total Total Amount($), followed by North America. Focus on understanding the factors driving success in these regions and consider allocating additional resources or implementing targeted strategies to maximize growth and revenue.
- PPC Negotiation: Xcs Corp and ABF Inc present the highest scope for PPC (Pay-Per-Click) negotiation. Review the current PPC agreements with these vendors, analyze the market rates, and negotiate for better terms to improve profitability.
