# User-Loyality
The data is a bank card transaction and user (card) loyalty analysis dataset provided by a bank in Brazil The overall purpose of the analysis is to predict a
**loyalty score** for each card id represented in userscore.csv.
## Datasets 
The dataset contains four files.
* **userscore.csv** contain card ids and information about the card itself - the first month the card was active. It also contains the predict/analysis target,
i.e., score, which is a score calculated by the bank, indicating the loyalty of each card owner. Three features are provided, all of which are anonymized card
categorical features.

* **merchants.csv** contains aggregate information for each merchant id represented in the data set

* **The historical transactions.csv** and new merchant transactions.csv files contain information about each card’s transactions. historical transactions.csv contains up to 3 months’ worth of transactions for every card at any of the provided merchant ids.
*  **new merchant transactions.csv** contains the transactions at new merchants (merchant ids that this particular card id has not yet visited) over two months.  
