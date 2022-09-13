# Fintech Finder

You work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

To complete this Challenge, you will use two Python files, both of which are contained in the starter folder.

The first file that you will use is called fintech_finder.py. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.

The second file that you will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file.

Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

Specifically, you will assume the perspective of a Fintech Finder customer in order to do the following:

Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

Fetch and display the account balance associated with your Ethereum account address.

Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

Review the transaction hash code associated with the validated blockchain transaction.

Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.



This project produces a Jupyter Notebook that uses machine learning to assess credit risk. Using the imbalanced-learn library a logistic regression model will be built to compare healthy loans vs non healthy loans to determine credit risk. The models built in this project will use histroical data that is provided by a lending service company that focuses on peer to peer lending. 



---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/docs/getting_started/install.html) - For summary statistics, visulizations, and times series analysis.
* [jupyter lab](https://jupyter.org/install) - JupyterLab is the latest web-based interactive development environment for notebooks, code, and data.

* Visual Studio Code Version: 1.70.2 (Universal)
Commit: e4503b30fc78200f846c62cf8091b76ff5547662
Date: 2022-08-16T05:36:37.829Z
Electron: 18.3.5
Chromium: 100.0.4896.160
Node.js: 16.13.2
V8: 10.0.139.17-electron.0
OS: Darwin arm64 21.4.0

---


## Libraries used in analysis


import numpy as np

import pandas as pd

from pathlib import Path

from sklearn.metrics import balanced_accuracy_score

from sklearn.metrics import confusion_matrix

from imblearn.metrics import classification_report_imbalanced


---

## Contributors

#### Antiwan Maxwell
#### Contact Infromation:

email: antiwan.maxwell@outlook.com

[LinkedIn](https://www.linkedin.com/in/antiwan-maxwell-205a11233/)


---

## License
