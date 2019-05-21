# Recommendation-System
Collaborative filtering models for recommending products to customers using the purchase data.

Model on GitHub adapted to Microsoft Adventure Works Database for demo purposes

Link to Database Readme - https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/adventure-works

Link to download database - https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks

For this model the AdventureWorksDW2017.bak data set was used, from where the customers data and transaction history was extracted into 2 files as in the repository

## The tool will be able to search for a recommendation list based on a specified user, such that:
Input: customer ID
Returns: ranked list of items (product IDs), that the user is most likely to want to put in his/her (empty) “basket”
