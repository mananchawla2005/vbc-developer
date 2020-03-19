---
title: Get extension data by account ID and extension number
navigation_weight: 1
---

# Get extension data by account ID and extension number

This example shows you how to get details of the extension. This will include the extension's number, the caller id and the headsets associated with this extension. 

Replace the following placeholder value in the sample code:

| Key        | Description                                                                                            |
|------------|--------------------------------------------------------------------------------------------------------|
| bearer_token | Your OAuth token. [Read more about OAuth tokens](https://developer.nexmo.com/vonage-business-cloud/vbc-apis/getting-started/authentication) |
| account_id | The Vonage Business Communications account ID. |
| extension_id | The extension Id. |


``` bash
curl --location --request POST 'https://api.vonage.com/t/vbc.prod/provisioning/v1/api/accounts/$account_id/extensions/$extension_id' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer $bearer_token' \
```