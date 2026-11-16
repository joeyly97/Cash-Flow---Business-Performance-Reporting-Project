# Cash Flow & Business Performance Reporting Project
## 1. REPORT OBJECTIVES
The report provides the Board of Directors and relevant departments with a comprehensive and timely view of the enterprise's financial health through data on:
- Cash Flow (Statement of Cash Flow): Helps the enterprise trach whether cash flows are  being utilized efficiently and in accordance with the plan.
- Business Performance (Income Statement): Helps the enterprise understand current business conditions and profitability.
Automating the reports minimizes time consumption and enhances accuracy compared to manual reporting, while supporting the Board of Directors and departments in immediately identifying abnormal indicators for timely decision-making.
  
## 2. DATA DESCRIPTION: 
Input data is structured in to Excel files corresponding to each financial statement: Cash Flow and Income Statement
   
## 3. DATA PROCESSING WITH POWER QUERY
- Segmented financial statements into 2 separate folders by report type to make future data ingestion seamless without re-work.
- Input data has been standardized from Excel files with zero errors.
- Checked headers and data types for each column; renamed tables following Dimension and Fact naming conventions for standardiztion.
  
## 4. DATA MODELING
- Created a Dim_Date table: Day, Month Name, Month Number, Quarter, Year to link with other FACT and DIMENSION tables, forming a Star Schema data model.
- Established relationships: between Dim tables and Fact tables
  
## 5. DASHBOARD DESIGN
The dashboard consists of 4 pages: Cash Flow Plan ; Cash Flow Fluctuations ; Income Statement ; Income Statement Execution Details
### 5.1. CASH FLOW PLAN
- Provides the Board of Directors and departments with an over view of cash flow performance versus the plan across activities and line items.
- Visualizes fluctuations over time to support early detection of anomalies and prompt decision-making.
### 5.2. CASH FLOW FLUCTUATIONS
- Dives deep into analyzing components constituting cash flows and period-over-period varitaion by activity type.
- Helps the Board and departments assess cash flow status per specific activity and evaluate how effectively capital is utilized relative to generated revenue.
### 5.3. INCOME STATEMENT
- Provides a macro perspective on revenue, COGS, and profit movements over time.
- Analyzes profitability across individual items.
### 5.4. INCOME STATEMENT EXECUTION DETAILS.
- Offers granular views into income statement variances of the current period versus prior periods, as well as against targeted plans.
    
## 6. REPORT FINDING AND RECOMMENDATIONS
### 6.1. Cash Flow Execution Over Time:
- Current Status: Overall, the execution rates for Inflows, Outflows, and Net Cash Flow are relatively very good. However, the absolute scale diminishes toward late 2025; starting July 2025, Net Cash Flow and its Plan turned negative.
- Impact: The business met its plans by reducing inflows alongside outflows over time, but planned inflows decreased faster than outflows. If sustained, this will deplete operating capital reserves.
- Recommendations: Re-evaluate the business plan. Although percentage target achievements look favorable on paper, liquidity is facing genuine structural issues.
### 6.2. Cash Flow Fluctuations by Activity Over Time
- Current Status: In 2024, ending cash and cash equivalents grew exponentially until year-end (inverse to investing cash flows), driven primarily by operating and financing inflows. In 2025, alarming downward shifts occurred in operating and financing flows, cash dropped to extremely low year-end levels, while investing cash outfiows climbed continuously.
- Impact: Severe signs of liquidity instability, altering capital structure and allocation. Focusing less on core operating inflows and shifting toward investing activities; potential missteps risk triggering insolvency.
- Recommendations: Re-evaluate core business model (trading vs. investment). Review and divest underperforming investments. Establish contingency planning for liquidity crisis scenarios.
### 6.3. Cash Flow Quality vs. Revenue
- Current Status: Business sales revenue shows a slight contraction in 2025 compared to 2024 with modest annual increments. However, many months experience high revenue growth over prior periods accompanied by declining customer cash receipts (e.g., Oct 2024: sales revenue up 27% MoM, but customer cash receipts dropped 17%), a pattern prone to recurrence.
- Impact: The enterprise likely extends extensive credit terms. While normal in business, continuous extension creates severe real working capital deficits and low liquidity.
- Recommendations: Pursue stable revenue growth while enforcing robust debt collection and early-payment incentive policies to stabilize liquidity when needed.
### 6.4. Income Statement Trends Over Time
- Current Status: Revenue and profit growth rates increase year-over-year while COGS remains controlled-even showing slight reductions mid-2024.
- Impact: The business operates reasonably well with stable COGS control. Monthly profit growth rates consistently outpace revenue growth rates.
- Recommendations: Sustain and promote revenue growth while seeking cost-reduction and COGS-lowering measures to maximize net profitability.
### 6.5. Divergence Between Cash Flow and Income Statement
- Current Status: Examining individual monthly income statements, certain line items may miss targets, but overall business performance appears stable, with strong revenue, controlled COGS, and expanding profit margins. Yet, cash flow fluctuations from the Statement of Cash Flows reveal critical liquidity strains.
- Impact: Relying solely on the income statement suggests growth, but profits are not actually reinvested to strengthen core sales and service competencies. This leads to operational cash shortages for running day-to-day operations and reinvestment.
- Recommendations: Maintain growing business operations. Audit cash flow rationality and direct profit utilization toward true core competencies.
