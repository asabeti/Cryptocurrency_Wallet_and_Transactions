# Module_19_Cryptocurrency_Wallet_and_Transactions

## Description
I am working for a startup that has a new platform named Fintech Finder. Fintech Finder is an application that allows its customers to find fintech professionals from a list of candidates, hire them, and pay them. The tasks for this weeks challenge include: 

* Generate a new Ethereum account instance by using your mnemonic seed phrase
 (we used Ganache to generate our mnemonic seed phrase).

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

* Digitally sign a transaction that pays a Fintech Finder candidate.

* To verify the transaction went through correctly, we use Ganache, which is our testing platform to see the transaction details.

* Review the transaction hash code associated with the validated blockchain transaction.

When the application is opened through Terminal(OS) or GitBash(Windows) using Streamlit, a browser will open and the user will land on the welcome page, as seen below. The user is able to see different Fintech professionals available for hire and their hourly rate.
![alt text](https://github.com/asabeti/Module_19_Cryptocurrency_Wallet_and_Transactions/blob/main/Images/Stremlit%20Web%20Page%20Success.png)

The user is able to select which Fintech professional they would like to hire by scrolling in the left panel. Once satisfied with whom they would like to hire, the user is able to input the amount of hours they will require from the professional which is also located in the left panel. The user will now be able to see the hourly rate (in Ethereum), and the total wage for the job is then displayed below. Once the user clicks "Send Transaction" the Ethereum is taken from the users wallet (Ganache account in this case) to the wallet address of the Fintech professional selected. The transaction hash is then displayed below the "Send Transaction" button. An example of this full process is shown below.
![alt text](https://github.com/asabeti/Module_19_Cryptocurrency_Wallet_and_Transactions/blob/main/Gifs/GifMaker_20230313153826441.gif) 

To verify the transaction went through correctly, we use Ganache, which is our testing platform to see the transaction details. When we first open Ganache, we can see that our account balance is lower (started with 100 Eth). We can see the transaction in Index 0.
![alt text](https://github.com/asabeti/Module_19_Cryptocurrency_Wallet_and_Transactions/blob/main/Images/Ganache%20Account%20Index%200.png)

After clicking on the transaction located at Index 0 on Ganache we can further inspect the details of this transaction. For instance, we can verify the transaction hash that was passed back to the user when the transaction went through.
![alt text](https://github.com/asabeti/Module_19_Cryptocurrency_Wallet_and_Transactions/blob/main/Images/Ganache%20Transaction.png)

---

## Technologies

This application was written in Python 3.9.12. This application is dependent on the following libraries:

* [streamlit](https://streamlit.io/)
* [dataclasses](https://docs.python.org/3/library/dataclasses.html)
* [typing](https://docs.python.org/3/library/typing.html)
* [web3](https://web3py.readthedocs.io/en/v5/)
* [mnemonic](https://pypi.org/project/mnemonic/)
* [os](https://docs.python.org/3/library/os.html)
* [requests](https://pypi.org/project/requests/)
* [dotenv](https://pypi.org/project/python-dotenv/)
* [bip44](https://pypi.org/project/bip44/)

---

## Installation Guide

Install [VS Code](https://code.visualstudio.com/) if you don't already have it.

Install [Ganache](https://trufflesuite.com/ganache/) if you don't already have it.

If you have [Anaconda](https://www.anaconda.com/products/distribution) downloaded, then dataclasses and typing will be part of your package. You can check that they're ready to use by typing the following in your CLI terminal:

```python
conda list dataclasses
conda list typing
```
In the terminal, with the Anaconda dev environment activated, install the following packages and dependencies before running the application.

```python
pip install streamlit
pip install web3==5.17
pip install mnemonic
pip install os-sys
pip install requests
pip install python-dotenv
pip install bip44
```