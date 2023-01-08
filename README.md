# PyChain Ledger

![alt=""](Images/application-image.png)


I took the role of the fintech engineer who’s working at one of the five largest banks in the world. I was recently promoted to act as the lead developer on their decentralized finance team. My task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

I made the following updates to the provided Python file for this assignment, which already contains the basic `PyChain` ledger structure:

1. Created a new data class named `Record`. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

2. Modified the existing `Block` data class to store `Record` data.

3. Added Relevant User Inputs to the Streamlit interface.

4. Tested the PyChain Ledger by Storing Records.

Streamlit Application rusults:
![pychain · Streamlit](https://user-images.githubusercontent.com/110307714/211220887-ef4b1049-9b2c-4e6a-86c6-965fdd531929.png)
![pychain · Streamlit (1)](https://user-images.githubusercontent.com/110307714/211220972-2e8ca1b9-249f-47cb-a87a-ff8543e37319.png)
![pychain · Streamlit (2)](https://user-images.githubusercontent.com/110307714/211220978-9000e3a2-7fe5-4e6f-b352-9a33a5e9fd50.png)

