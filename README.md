# Credit-Card-Fraud-Detection-Preditctive-Model

### Competition Overview
Welcome to the IEEE-CIS Fraud Detection Competition, presented in collaboration with Vesta Corporation, a leading payment service company. In this competition, we invite you to tackle the challenging task of fraud prevention using advanced machine learning techniques. Leveraging Vesta's real-world e-commerce transaction dataset, you will have the opportunity to benchmark and develop innovative solutions for detecting fraudulent activities.

### Problem Statement
Fraud detection plays a critical role in safeguarding sensitive information, assets, accounts, and transactions. By employing real-time and near-real-time analysis of user activities and defined entities, fraud detection mechanisms identify anomalies and deviations from expected behavior. Through the utilization of background server-based processes, this competition aims to assess the efficacy of machine learning models in identifying fraudulent patterns within a large-scale dataset.

### Data Description
The dataset provided contains a comprehensive set of features, each offering valuable insights into transaction characteristics and identity attributes. Key attributes include:

TransactionDT: A timedelta from a reference datetime, representing the time of the transaction.

TransactionAMT: The payment amount for each transaction in USD.

ProductCD: A code representing the product associated with each transaction.

card1 - card6: Payment card information, including card type, category, issuer bank, and country.

addr1, addr2: Address details.

dist: Distance information.

P_ and R_emaildomain: Purchaser and recipient email domains.

C1-C14: Counting attributes, which are obfuscated in meaning.

D1-D15: Timedeltas representing days between previous transactions.

M1-M9: Match attributes, such as card and address names.

Vxxx: Engineered features with ranking, counting, and entity relations.

Additionally, the identity table provides network connection information and digital signatures associated with transactions. It includes attributes like DeviceType, DeviceInfo, and id_12 - id_38.
