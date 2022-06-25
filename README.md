# Pychain
I built a pychain ledger by creating a Record Data Class with a formalized data  structure that consists of 'sender', 'receiver', and 'amount'. I revised the existing block data class to store record data by renaming the data attribute to record.
#
For the streamlit interface, I created input areas to capture sender, reeiver, amount for each transaction that was stored in the Block Record. As part of the 'Add Block' functionality, I updated the 'new_block' to include 'Record' class which contains the sender, reciever and amount values. I ran the steamlit application and tested it by adding sender, receiver and amount values and ran the validation.

## Results
![Streamlit interface](Pychain\Steamlit_interface\image_1.png)


![Transactions](Pychain\Steamlit_interface\image_2.png)
