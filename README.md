# PyChain A Python based simple ledger system for record keeping
This is a simple ledger system built with python using a few libraries for hashing and cryptography.

Streamlit was utilized for the UI of the application.

## How to use the application 

- Install the required libraries using pip from requirements.txt
- Run the application using the following command:
```streamlit run PyChain.py```
- The app will start in you're default browser.
- Add a sender , receiver and amount to the app and click on add block button to add a block to the chain.
- you can add as many blocks as you want.
- the blocks are stored and can be seen in the table as well as sidebar on the left.
- To ensure the integrity of the chain, the app will check the hash of the previous block and the hash of the current block and this is done with the validate button.

This implementation is simple and easy to use to demonstrate the blockchain concept.

## Demo of the App in Action 

![App Demo](/imgs/pychain_demo.gif)
