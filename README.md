*Fraud Detection*

*Overview* 
- This project implements a MySQL database to analyze and detect fraudulent credit card transactions. 
- It utilizes a robust dataset loaded from a CSV file, along with sample queries for fraud analysis and reporting.

*Features*
- Complete data model for transactions in the 'fraudtest' table
- Real data loaded from a CSV file
- Advanced SQL queries for fraud detection and analysis
- Easily extensible for additional features and analytics

*Database Structure*
The main table 'fraudtest' includes fields such as:
- Transaction details (date, amount, merchant)
- Cardholder information (name, gender, location)
- Merchant location data
- Fraud indicator
- Sample Queries

*The repository includes example queries for:* 
- Identifying fraudulent transactions
- Calculating fraud amounts by category
- Listing top merchants with fraudulent activities
- Analyzing fraud percentages by state

*Database Sourced From:* 
@misc{anonymous_2022,
	title={fraud transactions dataset},
	url={https://www.kaggle.com/dsv/4521194},
	DOI={10.34740/KAGGLE/DSV/4521194},
	publisher={Kaggle},
	author={anonymous},
	year={2022}
} 
