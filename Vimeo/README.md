# Indexing Vimeo using the Generic REST API Connector

## Use case
This example shows how to index Vimeo videos.

## Pre-requisites
To fully understand how to use this example, you must:
1. Have a Coveo platform organization
2. Learn about [Coveo Connectivity](https://docs.coveo.com/en/1702/cloud-v2-administrators/add-or-edit-a-source-using-one-of-the-available-connectors)
3. Learn [how to configure a Generic REST API Connector](https://docs.coveo.com/en/1896/cloud-v2-administrators/add-or-edit-a-generic-rest-api-source)

## Step-by-step guide
1. [Create an App](https://developer.vimeo.com/api/guides/start) and get your access_token
2. Create a Generic REST API source
3. On the authentication section paste your access_token on the API Key section (provided in step 1)
4. Configure your Generic REST API source according to the example in SourceJSONConfig.json.
5. Create the appropiate fields and mappings.