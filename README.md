# eth_transaction
Challenge 19

This application makes an Ethereum payment.

---

## Libraries and Dependancies

* [streamlit](https://docs.streamlit.io/en/stable/) - an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science.

* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - provides a decorator and functions for automatically adding generated special methods such as __init__() and __repr__() to user-defined classes.

* [typing](https://docs.python.org/3/library/typing.html) - provides runtime support for type hints as specified by PEP 484, PEP 526, PEP 544, PEP 586, PEP 589, and PEP 591. The most fundamental support consists of the types Any, Union, Tuple, Callable, TypeVar, and Generic.

* [web3](https://web3py.readthedocs.io/en/stable/) - a Python library for interacting with Ethereum.

* [bip44](https://www.cs.utexas.edu/users/moore/acl2/manuals/current/manual/index-seo.php/BITCOIN____BIP44?path=3370/27092/5157/6093/9771) - Bitcoin Improvement Proposal 44. BIP44 refers to the accepted common standard to derive non segwit addresses. These addresses always begin with a 1.

* [requests](https://docs.python-requests.org/en/master/) - an elegant and simple HTTP library for Python, built for human beings.

* [os](https://docs.python.org/3/library/os.html) - provides a portable way of using operating system dependent functionality.

* [dotenv](https://pypi.org/project/python-dotenv/) - reads key-value pairs from a .env file and can set them as environment variables.

---

## Usage

The application operates in the following steps:

1. Import Ethereum Transaction Functions from crypto_wallet.py into the tintech_finder.py
2. Sign and Execute a Payment Transaction
3. Inspect the Transaction on Etherscan

---

## Results

Key outcomes of the transaction are demonstrated below:

The ethereum transaction:
![transaction](https://github.com/Jyou965/eth_transaction/blob/main/screen_shots/payment_detail.png)

Transaction history of sender's address:
![sender](https://github.com/Jyou965/eth_transaction/blob/main/screen_shots/address_history.png)

Transaction history of recipient's address:
![recipient](https://github.com/Jyou965/eth_transaction/blob/main/screen_shots/recipient_address_history.png)

---

## Contributors

Jackie You with the support of FinTech Boot Camp Staff

---