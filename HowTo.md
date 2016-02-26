# How-to

This application is to demonstrate the use of blockchain technology for the use-case of trading Commercial Paper. Using this application, companies can 

* Issue a new commercial paper and 
* Buy the commercial paper for a discount

Let us jump directly into how to use this application:

1. Login

    ![Login screen](/img/login.png)
	Enter the username and password of your company to login to the application.
	
2. Create

	Click on the Create link to get to the create page.
	
    ![Labelled Create Page](/img/create_marked.png)
	A new Commercial Paper can be issued using the create page. 
	We can switch between create and trade page by clicking on the links on the top of the page. 
	The time the latest block was committed on the chain is shown on the top right.

	We can show/hide the list of the blocks on the chain by clicking on the "*View Tx Blocks*". 
	Hovering or clicking on the block number will show the details of the block.
	We can see a new block being added to the chain when a create/trade transaction is performed
	
	The following details are required for issuing a new commercial paper:
	* **Ticker:** The ticker for the paper
	* **Par:** The value of each paper
	* **Qty:** The number of papers to be issued
	* **Discount:** Discount Rate for the paper
	* **Maturity:** The maturity date for the paper
	
	Click on the Create button to issue the Commercial Paper. Once issued, the paper will be listed on the Trade page.
	
3. Trade

	Click on the Trade link to go to the trade page.

	![Labelled Trade Page](/img/trade_marked.png)
	We can list all the Commercial Papers and buy one from the Trade Center.
	The trade center shows the Account Balance of the company whicch is signed in.
	It lists all the commercial papers ever issued with details of each paper.

	The papers which are already purchased and are not available are greyed out and their Buy button is disabled.
	The papers can be purchased by clicking on the Buy button. 
	Currently, only a single commercial paper can be purchased at a time.
	
	When a paper is purchased, the account balance of the company purchasing the paper and of the issuer company of the paper are affected.  

	We can show/hide the list of the blocks on the chain by clicking on the "*View Tx Blocks*". 
	Hovering or clicking on the block number will show the details of the block.
	We can see a new block being added to the chain when a create/trade transaction is performed.
	
	
	
		
