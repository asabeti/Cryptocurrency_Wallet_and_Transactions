# Module_19_Cryptocurrency_Wallet_and_Transactions

## Description
I am working for a startup that has a new platform named Fintech Finder. Fintech Finder is an application that allows its customers to find fintech professionals from a list of candidates, hire them, and pay them. The tasks for this weeks challenge include: 

* Generate a new Ethereum account instance by using your mnemonic seed phrase
 (we used Ganache to generate our mnemonic seed phrase).

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

* Digitally sign a transaction that pays a Fintech Finder candidate.

* Review the transaction hash code associated with the validated blockchain transaction.

* To verify the transaction went through correctly, we use Ganache, which is our testing platform to see the transaction details.

When the application is opened through Terminal(OS) or GitBash(Windows) using Streamlit, a browser will open and the user will land on the welcome page, as seen below. 
![alt text]("C:\Users\audel\OneDrive\Desktop\Module_19_Cryptocurrency_Wallet_and_Transactions\Images\Stremlit Web Page Success.png")

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