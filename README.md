# Pychain
I built a pychain ledger by creating a Record Data Class with a formalized data  structure that consists of 'sender', 'receiver', and 'amount'. I revised the existing block data class to store record data by renaming the data attribute to record.
#
For the streamlit interface, I created input areas to capture sender, reeiver, amount for each transaction that was stored in the Block Record. As part of the 'Add Block' functionality, I updated the 'new_block' to include 'Record' class which contains the sender, reciever and amount values. I ran the steamlit application and tested it by adding sender, receiver and amount values and ran the validation.

## Results
![Transactions](https://user-images.githubusercontent.com/98926434/175790564-2f508816-54f1-49e3-b72e-93f77f34bb45.png)


![Steamlit Interface](https://user-images.githubusercontent.com/98926434/175790599-f4e63c32-5d9e-4ed4-95ed-5f514560129d.png)
