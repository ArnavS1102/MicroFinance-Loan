# MicroFinance-Loan
Product Background:
A specific loan product X involves 3 parties.
1.	Dairy Farmers
2.	A Bank
3.	A Food Company

The dairy farmers provide milk to the food company. The food company in return makes weekly payments to the farmers which are routed through the bank. The bank is offering loans to the dairy farmers against these payments. Duration of loan is 13 weeks. After a farmer has acquired the loan, it'll be repaid in weekly installments. These installments are deducted from payments of the food company to the farmer over the course of next 13 weeks.

Challenge:

Given historical 1 year (52 weeks) of payment data, the challenge is to identify:
1.	Which farmers are most suitable to target for loan product X? In other words, which farmers are likely to have consistent payments in next 13 weeks?
2.	How much loan should be offered to each farmer?

Business Context:

Farmers are not bound to provide milk to the food company. They can provide a portion of overall milk production to the food company, skip weeks or cease supply altogether whenever they want.
Farmers with high milk supply can be offered higher loans. Therefore it is preferable to target them whenever possible.

farmers_salary_transactions was the dataset provided.

Revised_farmers(1) is the dataset which contains the loans disbursed to farmers.


