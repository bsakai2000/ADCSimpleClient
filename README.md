# SimpleClient
A single html file provides (nearly) the simplest possible client for https://github.com/AutomaticDoorControl/AutoDoorCtrlWebAPIPHP, which can be used to better understand the requests being made to the API or can be used as a standalone client (albeit one incapable of actually opening doors with bluetooth requests). View requests, return codes, and authorization tokens as they are sent and recieved, with dead simple implementation. This contrasts the real web client, which has unit tests and different components and services and is therefore much more difficult to quickly interpret

## How to use
Fill in the values for the fields you would like to send with your request (only for POST requests), click the name of the request you would like to make, and the status code and server response will populate the bottom table.

If a request is made the generates a JWT, the JWT will be stored in the `Authentication Token` portion of the third table. That JWT will be sent as part of all requests. That field can also be filled by hand (or more likely by copy paste)
