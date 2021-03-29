# Analysis of US stocks
Financial analysis and evaluation of a selected NYSE, NASDAQ listed company.

The program based on the uploaded data from the financial statements of the company carried out an analysis of the financial results and the evaluation of the company. <br>
First, preliminary data analysis and preparation are performed. Then the main figures are checked (i.a. net profit, sales revenues, debt, cash flow, equity, dividends, etc.).<br>
Based on the data, financial ratios are calculated (i.a. book value, increase in sales revenues, increase in net profit, profitability ratios, liquidity ratios, activity ratios, debt ratios, property ratios, description of financial flows). <br>
An assessment of the company is performed using the determined indicators and the loaded data. On the basis of a defined criterion, 1 point is added to the evaluation depending on the level of a given indicator.<br>

Criteria (met, 1 point added):<br>
- Dividend:
  - Dividend yield > 2%
  - Dividend value per share > 1  
- Book value:
  - Change in book value > 0%
- Increasing sales revenues:
  - Change in sales revenues > 0%
- Increasing net profit:
  - Change in net income > 0%
- Profitability:
  - ROE > 20%
  - ROA > 10%
  - ROS > 10%
  - Operating margin > 10%
  - Net profit margin > 10%
- Liquidity:
  - Current ratio > 2
  - Cash ratio > 20%
  - Working capital > 0
- Activity:
  - Cash conversion cycle <0
- Debt:
  - Long-term debt of equity < 20%
  - Debt ratio < 67% 
- Cash flow:
  - Cash flow description == 'III - (+--) stable company, best situation'
  - Cash flow description == 'VI - (--+) start-up, early stage of operation'
  - Cash flow description == 'VIII - (+-+) after the start-up phase'
- Property:
  - 1st degree of coverage > 0.6

Company rating:
- 15-18 points: Very good company,
- 12-14 points: Good company,
- 9-11 points: Average company,
- 0-9 points: Weak company. <br>

The summary presents the change in the value of the company's rating over time and selected financial ratios.
