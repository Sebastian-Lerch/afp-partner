# How to use this reposititory

**This is still work in progress**

This repository holds postman examples for a partner model integration.

Import the collection and the environment file in postman.

After that edit the environment file and enter your credentials. From that on everything else should work out of the box. (TODO check if this is really the case).

Environment parameters:

| Variable                   | Type    | Comment                                                                        |
|----------------------------|---------|--------------------------------------------------------------------------------|
| BalanceApiKey              | secret  | This is the API key for user ending with @BalancePlatform.[CompanyAccountName] |
| LemApiKey                  | secret  | This is the API key for user ending with @Scope.[CompanyAccountName]           |
| PspApiKey                  | secret  | This is the API key for user ending with @Company.Company_[CompanyAccountName] |
| MerchantAccountNamePartner | default | Name of the merchant account used                                              |
| BalancePlatformName        | default | Name of the platform                                                           |
| TerminalId                 | default | ID of the terminal used for testing                                            |
| CompanyAccountName         | default | Name of the Company account                                                    |

If you want to e.g. change API Versions used go to the collection variables and change it there.
