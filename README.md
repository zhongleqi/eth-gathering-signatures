# eth-gathering-signatures
This is my final assignment for Stanford University W23-LAW-1076-01 Blockchain Engineering: Techniques and Legal Implications.

The purpose of the final assignment is to create a solidity smart contract that can reflect the founctionality of Ethereum.

My project is a signature gathing system:

One user creates a file, and specifies other users to sign the file. 
After all the users sign the file, the complete file will be returned to the message sender.
    
1, one user creates a file and specifies other users to sign.

a, one user creates a file.

b, the user inputs the address to the file that will be sent.

c, the file records the file creator’s address.

2, the file circulates to other users who need to sign.

a, the file goes to addresses that are specified in the file.

b, users who get the file need to sign it.

c, the file records the timestamp and addresses that are signed.

3, after gathering all the signatures, the file goes back to the creator.

a, the file returns to the creator.
