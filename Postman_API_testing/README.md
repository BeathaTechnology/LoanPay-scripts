# Postman scripts for testing direct integration

# Set up environment

	* Go to Postman and press Import in upper left corner
	* Drop in downloaded environment JSON file
	* Choose environment in drop down selection box in upper right corner
	* After selecting environment, you edit it by pressing on gear icon on the right of selected environment 
	* In environment set up your secret key and API key provided from us

# Set up collections
	* Go to Postman and press Import in upper left corner
	* Drop in downloaded collections JSON file
	* After that you will see folder with two post requests
	* POST for creating order. You only to put merchant_id and the rest of data needed for a valid request
	    - If you are a payment gateway then under vendor_id put merchant_id for which is order being created
	* POST for checking user/merchant max limit. You need to put in merchant_id and phone number
	    - If you are a payment gateway you don't need to use this one,it is for merchant so they can see user limit

