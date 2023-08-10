# Datasheet Template


## Motivation

The code generated data set was created by myself using random variables.

The Euro interest rate is main banchmark rate for EUR and is available through many sources. The official source is the European Central Bank website. The methodology and composition of the rate are confidential, but its based off market funding transactions throughout the day.

 
## Composition

Code generated:

 - Date: Market Date
 - Balance: Balance in the Client's Account
 - Client ID: This identifier uniquely distinguishes different clients.
 - Category: Balance type category (i.e.,Opening balance, Ending Balance, etc)
 - Currency: Currency of the balance
 
 ECB sourced:
 
 - DATE: Market Date
 - EUR RATE: Historical Interest Rate for the Day
 
 https://data.ecb.europa.eu/data/data-categories/financial-markets-and-interest-rates/euro-money-market/euro-short-term-rate
 

## Collection process

Deposits balances were generated mecanically via code.
Euro interest rates were sourced via CSV.

## Uses

The code generating the deposits could be applied to generate other balance sheet categories or used to create and emulate full cash flow movements.

## Distribution

The data for deposits balances is random generated, so is public.
The data for historical Euro interest rate is public and can be found in the ECB website.

## Maintenance

European Central Bank for Euro Interest Rate.

