## Adyen payment integration
## Objective
        Adyen provides payment processing solutions for businesses, enabling them to accept payments from customers through various channels such as online, in-store, and mobile. Adyen's integrations allow businesses to seamlessly incorporate Adyen's payment capabilities into their existing platforms, websites, or applications.
## Dependencies 
    •	Studio pro version 9.24.6
## Configuration
    •	Import the module Adyen Module from the mendix marketplace.
    •	Go to the URL to create a developer account in Adyen portal, URL: https://www.adyen.com/signup
    •	Sign up for the Adyen portal by filling in your details. You will receive a username, account name, and password reset link via email. Use that link to create a new password.
## Going live
    •	To access the live endpoints, you need an API key from your live Customer Area.
## Going Test
    •	After creating your password, log in to the Adyen portal and switch to the "Test" tab. Then, log in using your username, account name, and password.
    •	Go to Developer-> API Credentials
    •	Click on “Username” -> ws
    •	Provide a description and generate an API key. Save the changes. (Note: If you have Apple Pay, Samsung Pay, or Google Pay certificates, add them and save the changes)
    •	Go to Settings -> Merchant accounts and retrieve the merchant account ID.
    •	The API key and merchant account should be placed in the default value of API Key constant which is available inside the module.
## Available API:
    •	Card Payment
    •	Pay through payment link (Payment URL will be generated)
    •	Order (Create/Cancel order)
    •	Recurring (Create/Delete Adyen account)
## Screenshots
 ![image](https://github.com/Moulidharan07/Adyen-payment-integration/assets/119506038/6a419907-4fae-4363-8fab-cfafd87fa69a)
 ![image](https://github.com/Moulidharan07/Adyen-payment-integration/assets/119506038/54f56c8c-672d-4ffb-a219-6549ca356437)
 ![image](https://github.com/Moulidharan07/Adyen-payment-integration/assets/119506038/48bbf994-1093-4733-be1e-d9ffeaabd86c)
 ![image](https://github.com/Moulidharan07/Adyen-payment-integration/assets/119506038/5f8837a9-d72e-4534-b5eb-2f45c301c211)
