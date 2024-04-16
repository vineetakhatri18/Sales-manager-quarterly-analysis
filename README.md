# Challenge Objective
For the Maven Sales Challenge, you'll play the role of a BI Developer for MavenTech, a company that specializes in selling computer hardware to large businesses. They've been using a new CRM system to track their sales opportunities but have no visibility of the data outside of the platform.
In an effort to become a data-driven organization, you've been asked to create an interactive dashboard that enables sales managers to track their team's quarterly performance.

Link to live dashboard:

Video presentation of the report:

## Understanding Deal Stages
"Deal prospecting" involves identifying and evaluating potential opportunities or leads before any formal engagement or negotiation occurs. It's about finding potential clients or partners who may be interested in doing business with you.

"Deal engaging," on the other hand, involves actively interacting with those identified prospects to negotiate and finalize a business agreement. It's about initiating and maintaining communication, presenting proposals, addressing concerns, and ultimately reaching a mutually beneficial agreement.

"Deal won" refers to successfully closing a business agreement or transaction with a client or partner. It means that the negotiations were successful, terms were agreed upon, and the deal was finalized, resulting in a positive outcome for the company.

On the other hand, "deal lost" refers to a situation where a business agreement or transaction fails to materialize despite efforts to negotiate and finalize terms. It means that the company was unable to secure the deal, either due to competing offers, disagreement on terms, or other factors.

### Data Transformation
1. Data Extraction: Extracted data from four Excel files containing sales information. The data includes four files- accounts gives details of the each company, product gives details of each product such as price and series, sales teams gives details of sales agent, manager and region of each, sales pipeline includes detail of each deal happened in 2017 such as revenue, time to close a deal, stage is deal, etc.
2. Data Transformation: Cleaned and shaped the data using Power Query. Applied transformations like formatting data types to prepare the data for analysis. Conducted operations such as removing duplicates, renaming columns and replacing values. Created a separate date table.
3. Data Modelling: Created relationships between related columns. Defined calculated columns and measures using DAX for additional insights into the data.
Data Model View
4. Report Designing and Visualization: Selected appropriate visualization types from the Visualizations pane. Designed the layout of the report, arranging visuals in a logical and intuitive manner. Added titles, subtitles, and other text elements to provide context and guidance. Ensured consistency in formatting and styling throughout the report for a professional look.
5. Adding user-friendly features in report: Implemented dynamic tooltips to provide additional context and   information to users on hover. Configured tooltips to display relevant details based on the data being visualized, enhancing user understanding and interaction. Created page navigation to facilitate seamless exploration across different sections of the report. Added buttons or links to navigate between pages, allowing users to easily access specific insights or analysis.
   
### Important Metrices

**Deals Win**: This measure calculates the total number of deals that have been won by the company. It counts the number of deals where the outcome is marked as "won". This measure helps track the success rate of closing deals. Knowing the total number of deals won provides a clear indication of the company's ability to convert leads into closed deals. It is a fundamental metric for assessing overall sales performance and evaluating the effectiveness of sales strategies.

**Win Percentage**: This measure calculates the percentage of deals won out of the total number of deals pursued (won/lost). I haven't included deals which are engaging or prospecting. It offers insights into the efficiency and effectiveness of the sales process. A high win percentage indicates strong sales performance and efficient use of resources, while a low win percentage may indicate areas for improvement or inefficiencies in the sales process.

**Average SCL (Sales Cycle Length)**: This measure calculates the average length of time it takes to close a deal, also known as the sales cycle length. It is measured in days and is calculated by averaging the sales cycle length for all closed deals. Here I have calculated SCL with respect to won deals. A shorter sales cycle length typically indicates faster deal closures, which can lead to improved cash flow, increased productivity, and better customer satisfaction. Monitoring the average sales cycle length helps identify bottlenecks, streamline processes, and optimize resource allocation.

**Revenue from Each Deal**: This measure calculates the total revenue generated from each individual deal. It sums up the revenue associated with each closed deal. This measure provides insights into the financial impact of individual deals. Knowing the revenue generated from each deal helps assess the value and profitability of different sales opportunities. It enables sales teams to prioritize high-value deals, allocate resources effectively, and focus on opportunities that contribute the most to the company's bottom line.

**Average Revenue**: This measure calculates the average revenue generated per deal. It is calculated by dividing the total revenue from all deals by the total number of deals. Average revenue per deal is a key indicator of deal profitability and overall sales performance. It represents the average value of each closed deal and provides insights into the company's revenue generation capabilities. Monitoring average revenue per deal over time helps identify trends, track performance against targets, and make informed decisions about pricing, product offerings, and sales strategies.
