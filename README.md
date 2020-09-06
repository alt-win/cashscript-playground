## CashScript Playground
The CashScript Playground is a way to write CashScript contracts and immediately interact with them in the browser. It is inspired by Ethereum's Remix, but slightly less feature-rich.

In the left panel you can write CashScript contracts and comple them. After compiling, a form is generated to create a new instance of this CashScript contract. It will then display some information about the contract and generate new forms to call contract functions to send BCH transactions.

A live demo is available at https://playground.cashscript.org/.

### Limitations
No special transaction options (such as OP_RETURN or hardcoded fees) are supported by the playground, and only one single transaction output can be specified for the transaction sending. The CashScript Playground is not meant to be the main solution to write and use CashScript contracts, but instead is is meant to be a quick and easy way to try it out.

The CashScript Playground is connected to the Bitcoin Cash mainnet, but keep in mind that this is experimental software and be sure to **not send large amounts** of money to contracts generated by the CashScript Playground.

### Example
![Example](/example.png)

### Running locally
```
git clone git@github.com:rkalis/cashscript-playground.git
cd cashscript-playground
yarn
yarn start
```
