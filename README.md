# feature-examples

For each feature, there should be a "Feature" task in Asana
This task should include:
* A link to the feature file. Currently in this repo as an example, but they may live in a Box folder instead as text files.
* Any additional acceptacnce criteria.


Examples

Task Name: Bank Account Transfer

**Feature File**

https://github.com/CommunicateHealth/feature-examples/blob/main/bank-account-transfer

**Acceptance Criteria**  
User must be logged in to make a transfer.  
User must have at least two accounts.  
User must have sufficient funds in the source account for the transfer.  
Upon successful transfer, the source account's balance is decreased by the transfer amount.  
Upon successful transfer, the destination account's balance is increased by the transfer amount.  
If the transfer is unsuccessful, the balances of the source and destination accounts remain unchanged.  
User receives a confirmation message upon successful transfer.  
If the source account does not have sufficient funds for the transfer, the user should see an error message, and the balances of the source and destination accounts should remain unchanged.  
If the destination account does not exist, the user should see an error message, and the balance of the source account should remain unchanged.  
If the user is not logged in, they should be redirected to the login page when they attempt to make a transfer.  
