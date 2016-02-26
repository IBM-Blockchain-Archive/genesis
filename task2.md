For this task, you can use either the [Swagger UI](https://ibmblockchainapi.mybluemix.net/swagger/ui.html?scheme=https&host=cp-demo.blockchain.ibm.com:31443&basepath=/) (recommended) or the [NodeJS SDK](https://github.com/IBM-Blockchain/ibm-blockchain-js)

The initial challenge for this task will be to discover the block number for the transaction where IBM commercial paper was issued.  Blocks are created in sequential order starting with the block 1.  You will use the Block API for this.  Hint:  the payloads for transactions are base64 encoded.

Once you complete the initial challenge, see if you can find the following:
* the block number for the paper you created
* the block number for any paper you purchase
* all of the block numbers where IBM paper has been purchased
