# ETHF20 Protocol
ETHF20 Protocol base on ETHF blockchain writing the string into the memo field of the transaction to achieve this.

## Token Economic
 - Token: ETFS
 - Supply: 21000000000(Non-autobiography and contract invalid)
 - limit: 1000

## Method
 - deploy: `data:,{"p":"etf-20","op":"deploy","tick":"etfs","max":"21000000000","lim":"1000"}`
 - mint: `data:,{"p":"etf-20","op":"mint","tick":"etfs","amt":"1000"}`
 - transfer: `data:,{"p":"etf-20","op":"transfer","tick":"etfs","detail":[{"to":"ETHF Address","amt":"1000"}]}`

## Deploy txid
https://www.oklink.com/cn/ethf/tx/0x472c15f8f69c71d70491aa60670c4d6a9e8a025f7f85b0df880dccb846da24d6

## Deploy block
18516916

## Mint ETFS with TokenPocket Wallet
 - Receiver address: Your address. 
 - Transfer amount 0 ETHF
 - Click on Advanced Settings and fill in text `data:,{"p":"etf-20","op":"mint","tick":"etfs","amt":"1000"}`
 - or Click on Advanced Settings and fill in hexadecimal `0x646174613a2c7b2270223a226574662d3230222c226f70223a226d696e74222c227469636b223a2265746673222c22616d74223a2231303030227d`


## Mint ETFS with Other Tools
