# AI_driven_Financial_Chatbot
 Custom made from scratch in Python created and no OpenAI API key or outside integrations. Just simply pure python was used.



# Languages -  ![](https://img.shields.io/badge/^-Python-blue?logo=Python) - ![](https://img.shields.io/badge/^-Pandas-blue?logo=Pandas) - ![](https://img.shields.io/badge/^-Numpy-blue?logo=Numpy) - ![](https://img.shields.io/badge/^-Plotly-blue?logo=Plotly) 

# The AI powered Financial Chatbot Prototype currently responds only to the given set of questions for selected companies and fiscal years wiz: –

1. What is the total revenue?
2. What is the Net Income?
3. What is the sum of total assets?
4. What is the sum of total liabilities?
5. What is cash flow from operating activities?
6. What is the revenue growth(%) ?
7. What is the net income growth(%) ?
8. What is the assets growth(%) ?
9. What is the liabilities growth(%) ?
10. What is the cash flow from operations growth(%) ?
11. What is the year by year average revenue growth rate(%)?
12. What is the year by year average net income growth rate(%)?
13. What is the year by year average assets growth rate(%)?
14. What is the year by year average liabilities growth rate(%)?
15. What is the year by year average cash flow from operations growth rate(%)?

# Testing AI Driven Financial Chatbot!!!

```python

import pandas as pd
data = pd.read_csv('/content/final_data_report.csv')
data_2 = pd.read_csv('/content/Summary_final_report.csv')
data```
Unnamed: 0	Year	Total Revenue	Net Income	Total Assets	Total Liabilities	Cash Flow from Operating Activities	Company	Revenue Growth (%)	Net Income Growth (%)	Assets Growth (%)	Liabilities Growth (%)	Cash Flow from Operations Growth(%)
0	0	2023	211915	72361	411976	205753	87582	Microsoft	0.000000	0.000000	0.000000	0.000000	0.000000
1	1	2022	198270	72738	364840	198298	89035	Microsoft	-6.438902	0.520999	-11.441443	-3.623276	1.659017
2	2	2021	168088	61271	333779	191791	76740	Microsoft	-15.222676	-15.764800	-8.513595	-3.281425	-13.809176
3	3	2023	96773	14974	106618	43009	13256	Tesla	0.000000	0.000000	0.000000	0.000000	0.000000
4	4	2022	81462	12556	82338	36440	14724	Tesla	-15.821562	-16.147990	-22.772890	-15.273547	11.074231
5	5	2021	53821	5519	62131	30548	11497	Tesla	-33.931158	-56.044919	-24.541524	-16.169045	-21.916599
6	6	2023	383285	96995	352583	290437	110543	Apple	0.000000	0.000000	0.000000	0.000000	0.000000
7	7	2022	394328	99803	352755	302083	122151	Apple	2.881146	2.894995	0.048783	4.009820	10.500891
8	8	2021	365817	94680	351002	287912	104038	Apple	-7.230275	-5.133112	-0.496945	-4.691095	-14.828368


print("Year by Year Average Growth from 2021 to 2023")
data_2

Year by Year Average Growth from 2021 to 2023
Unnamed: 0	Company	Revenue Growth (%)	Net Income Growth (%)	Assets Growth (%)	Liabilities Growth (%)	Cash Flow from Operations Growth(%)
0	0	Apple	-1.449710	-0.746039	-0.149388	-0.227092	-1.442492
1	1	Microsoft	-7.220526	-5.081267	-6.651679	-2.301567	-4.050053
2	2	Tesla	-16.584240	-24.064303	-15.771471	-10.480864	-3.614123

%run /content/AI_Driven_Financial_Chatbot.ipynb

Year-By-Year Average Growth Rates(%) :-
             OR
Overall Growth/Fall rate for Apple, Microsoft and Tesla from Fiscal Year 2021 - 2023
----------------------------------------------------------------------------

Enter Hi to start the chatbot session; type 'exit' to quit): Hi

Hello! Welcome to AI Driven Financial Chatbot!!!

I can help you with your financial queries
Please select the company name from below: -

1.Microsoft 
2.Tesla 
3.Apple
Enter company name : Tesla

The data for the fiscal year 2023, 2022, and 2021 is currently available
The fiscal year for the selected company : 2022

Please enter your query
What is the cash flow from operations growth(%) ?
The Cash Flow from Operations Growth(%) for Tesla for fiscal year 2022 is 11.0742(%)
----------------------------------------------------------------------------

Enter Hi to start the chatbot session; type 'exit' to quit): Hi

Hello! Welcome to AI Driven Financial Chatbot!!!

I can help you with your financial queries
Please select the company name from below: -

1.Microsoft 
2.Tesla 
3.Apple
Enter company name : Tesla

The data for the fiscal year 2023, 2022, and 2021 is currently available
The fiscal year for the selected company : 2023

Please enter your query
What is the liabilities growth(%) ?
The Liabilities Growth(%) for Tesla for fiscal year 2023 is 0.0(%)
----------------------------------------------------------------------------

Enter Hi to start the chatbot session; type 'exit' to quit): Hi

Hello! Welcome to AI Driven Financial Chatbot!!!

I can help you with your financial queries
Please select the company name from below: -

1.Microsoft 
2.Tesla 
3.Apple
Enter company name : Tesla

The data for the fiscal year 2023, 2022, and 2021 is currently available
The fiscal year for the selected company : 2021

Please enter your query
What is the liabilities growth(%) ?
The Liabilities Growth(%) for Tesla for fiscal year 2021 is -16.169(%)
----------------------------------------------------------------------------

Enter Hi to start the chatbot session; type 'exit' to quit): exit
Year by Year Average Growth from 2021 to 2023
```
