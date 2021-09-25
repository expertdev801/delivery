# Delivery Instruction

**Requirement:**

On medline magento website we have some fragile products. And we want users to give us delivery instructions for those products. We want to add a text box in each product page where users can leave their instructions. Now we have some limitations when we use custom options for this purpose. 

So please create an text attribute using setup script which will show in each product page after the price block. This data will be saved in database along with the order so that warehouse people will get this instructions and pack it accordingly.

 Also please add this data in magento backend order details page (in the product block) as well so we can also see it when checking the order.
 
**Instruction to install:**

Clone project in local

Extract it and paste inside **app->code**

**Run Commands:**

sudo php bin/magento setup:upgrade 

sudo php bin/magento setup:di:compile

sudo php bin/magento setup:static-content:deploy -f
