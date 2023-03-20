# Test case template for an API endpoint

## Test step:
Write what we want to check and put the short description what basically about the endpoint.

## Test data:
URL to API documentation: [url]

Prepare a [Method] request: [protocol]://[environment]-[main-endpoint]/[the-rest-of-endpoint-url]

Set up the param(s) which should be used:
* paramName - [required/optional] - short description about validation and what type of value should be here.

Set up the type of authorization:
* typeOfauthorization - [required/optional] - short description about how to get value which is needed for authorization.

Set up the header(s) which should be used:
* nameOfHeader - [required/optional] - short description about validation and what type of value should be here.

Set up request body:
* Type of request body - eg. JSON
* fieldFromObjectBody - [required/optional] - short description about validation and what type of value should be here.

## Test result:
Expected status code: [expectedStatusCode]
Expected response: template of an example response object body.
