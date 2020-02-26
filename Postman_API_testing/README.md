# Postman scripts for testing direct integration

# Set up environment

	* Go to Postman and press Import in upper left corner
	* Drop in downloaded environment JSON file
	* Choose environment in drop down selection box in upper right corner
	* After selecting environment you can edit it by pressing on gear icon on the right of drop down selection box
	* In environment set up your secret key and API key provided from us

# Set up collections
	* Go to Postman and press Import in upper left corner
	* Drop in downloaded collections JSON file
	* After that you will see folder with two post requests
	* One is for creating order and in that you only need to put marchant_id and rest of data needed for valid request
		- If you are a gateway then under vendor_id put merchant id for which is order being created
	* Second is if checking user/merchnat max limit and you need to put in merchant id and phone number
		- If you are gateway you don't need to use this one,it is for merchant so they can see uses limit

