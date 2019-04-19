# OctoPrint integration with xMatters

## xMatter integration setup 

* Open your xMatters page
* go to page: Developer > Communication Plans
* Import zip file `OctoPrintIntegration.zip` 
    * this will create communication plan for integration
* On communication plan press `Edit` and choose `Integration Builder`
* You should see one configured `Inbound integration`  
    * Note if `Inbound integrations` configuration was not imported you may need to create once with `authentication method` equals to `API key`. 
* Open this configuration and at the bottom you will find all needed credentials

## Configuration

* Take `API Key`, `Secret`, `Integration URL` from xMatters integration and set it in plugin configuration
    * Note: for `recipients` field use comma separated user ids. To find user id in xMatters you should open "users" tab, find your user and you will see it in column "User Id".
* Choose events you interested in and enjoy.
