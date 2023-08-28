## Objective:

As a Business Analyst for EMD Solutions, a fictional vertical B2B SaaS startup, one of your tasks is to analyze historical sales data and provide insights to the leadership team regarding sales performance across the EMD Solutions product suite. EMD Solutions provides financial modeling, analytics, accounting and reporting tools to small businesses across the United States, who would otherwise have to build, maintain and staff more-robust financial functions on their own.

Our Leadership team is looking to expand our current product offering, and in order to successfully launch, they are eager to answer the following business question: ***"Has the total addressable market (TAM) and advertising spend significantly influenced historical sales performance, and if so, what is the optimal allocation of our advertising budget to maximize sales?"***

## Data and Task Guidelines:

You have been provided a raw data file containing historical revenue data ("Revenue Data.csv") and a file containing historical marketing spend and TAM data ("Marketing Spend and TAM by Product.csv") for your analysis. Additionally, a Data Dictionary file has been provided to facilitate the use of the data in the provided files. With the provided files, please perform the exercise below. 

## Submission Requirements:

Please submit your analysis and findings in Google Sheets file containing the calculated results, charts, and notes/descriptions. Your report should also include a concise executive summary (no more than 1 page) describing your methodology, analysis, actionable insights, and recommendations. Please make sure answers are marked clearly (e.g. If you proivde two answers in one tab of a Google Sheet workbook, please clearly label which answer is for 2a vs 2b.)



1. Summarize Historical Performance: (For this section, all analysis should be performed at a company-level.)
   
   - a) Plot the overall sales trend for the entire data period for the entire company.
   - b) Provide insights into company-level sales performance and trends over time.
   - c) Assume the data is complete (i.e. the data does not contain duplicates or test data records).


2. Segmentation Analysis:
   
      - a) Propose five segmentations of the customer revenue data that are helpful for exploring potential, actionable business insights. Concisely explain why each segmentation may be valuable.
      - b) Choose one of the five proposed segmentations to analyze in depth. Please show your analysis neatly in Google Sheets. What are the characteristics and preferences of each segment?
      - c) Have the segment's characteristics and preferences changed over time? If so, how?
    

3. Time to create a model!
   
    - a) Prepare the data for analysis:
       * Some Tips: We have previously analyzed the historical revenue data and observed two items worth noting:
           * New accounts take about a year to season and fully utilize the products they are subscribed to.
           * Even though we have clients that are in the Research industry, we have not historically marketed to Research firms the past (i.e. Customer_Type = Research).
           * For purposes of building a model (section 3), feel free to make additional data exclusions if you determine it is appropriate. If any exclusions are included, please describe those additional exclusions and your rationale for the exclusion.
    - b) Build a model you can use to provide a business recommendation for the following scenario:
       * The Leadership team would like to launch three new products. Please assume:
         * All products must launch.
         * Each of the new products has a $6M, $8M, and $10M annual TAM, respectively.
         * The Marketing team has a budget of $250k. You may recommend to use some, all, or none of the budget.
       - i) What were your considerations when building this model?
       - ii) Based on your conclusions, how would you allocate a $250k marketing budget? Describe your thought process.
       - iii) How much average monthly revenue do you anticipate from each product based on your marketing budget allocation?
         


