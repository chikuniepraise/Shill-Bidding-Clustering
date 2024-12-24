1. Introduction
Clustering is an unsupervised learning technique that helps organise data points into separate clusters based on their similarity (Kriegel et al, 2011). The Shill Bidding Dataset was analysed using clustering algorithms to discover underlying trends. The dataset, provided in CSV format, comprised different features linked to bidding activities; however, the bidder's identity was removed for privacy concerns and since it was not required for the study (Han et al, 2012). The clustering study was performed using two different clustering algorithms: K-Means and DBSCAN.
2. Dataset Overview
The dataset, Shill Bidding Dataset, was imported into a pandas DataFrame for further analysis. The dataset contains many numeric features; however, the field bidder_id was removed because it was unnecessary to the investigation. The initial examination of the dataset revealed important details about the structure, such as the number of records and columns. To ensure that the variables were understood well, the dataset was evaluated using the info() method, which provided information about the data types, and .head(), which examined the dataset's first few rows.
More analysis documented. Check out the documentation.
