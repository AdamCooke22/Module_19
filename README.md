# MODULE 19 CHALLENGE : Fintech Finder

For this challenge we are working as a lead developer at a firm named Fintech Finder. We have been tasked with integrating the Ethereum blockchain network into the application in order to enable our customers to instantly pay the fintech professionals whom they hire with cryptocurrency. 

In this challenge assignment we will generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache, fetch and display the account balance associated with our Ethereum account address, calculate the total value of an Ethereum transaction(including gas estimations, that pay the candidate for their work), digitally sign a transaction that pays the Fintech Finder Candidate and send the tansaction to the Ganashe Blockchain, and review the transaction hash code aassociated with the validated blockchain transaction.


---

## Technologies

This project leverages python 3.7 with the following packages:

* [streamlit](https://streamlit.io/) - This program allows for the creation of web apps from python code.

* [Web3](https://web3py.readthedocs.io/en/v5/) -This module allows for the interaction of Ethereum and to help with sending transactions, interacting with smart contracts, reading block data, and a variety of other use cases.
---

## Installation Guide

Before running the application first install the following dependencies.

```
import streamlit as st
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
```

---

## Usage
To view the streamlit and blockchain demonstration in action, you can view the screenshots in the "SCREENSHOTS" link below. * [SCREENSHOTS](https://github.com/AdamCooke22/module_19/tree/main/Screenshots)

## Contributors

Completed by Adam Cooke

---

## License

MIT
