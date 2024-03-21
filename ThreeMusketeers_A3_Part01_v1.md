# 3040 Crypto Pay

## 3040Crypto Pay API Description
The 3040 Crypto Pay API is designed to offer a simple yet powerful interface for processing payments. The ease, security, and speed of the API will set us apart. The API will allow users to:  
- Transfer money to other users
- Spend their money on their needs
- Change their crypto currency to their desired currency


## Endpoints, Parameters, and Sample Responses
```
1. GET /BankAccount
GET BankAccount?BankAccount=4

{
   "BankAccountNumber": 890173730
   "BankAccountHolderName": "HiBye"
}
```
```
2. GET /CompanyName
GET CompanyName?companyID=3
{
   "CompanyName": "Skip The Dishes"
   "Company'sBankAccountNumber": 293891827
}
```
```
3. GET /Currency
GET Currency?currencyID=USD
{
   "CurrencyValue": 15 
}
```
