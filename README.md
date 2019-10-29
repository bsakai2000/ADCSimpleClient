# SimpleClient
A single html file provides (nearly) the simplest possible client for https://github.com/AutomaticDoorControl/AutoDoorCtrlWebAPIPHP, which can be used to better understand the requests being made to the API or can be used as a standalone client (albeit one incapable of actually opening doors with bluetooth requests). View requests, return codes, and authorization tokens as they are sent and recieved, with dead simple implementation. This contrasts the real web client, which has unit tests and different components and services and is therefore much more difficult to quickly interpret

## How to use
Fill in the values for the fields you would like to send with your request (only for POST requests), click the name of the request you would like to make, and the status code and server response will populate the bottom table.

If a request is made that generates a JWT, the JWT will be stored in the `Authentication Token` portion of the third table. That JWT will be sent as part of all requests. That field can also be filled by hand (or more likely by copy paste)

Really don't like downloading things? Try https://htmlpreview.github.io/?https://raw.githubusercontent.com/bsakai2000/ADCSimpleClient/master/simpleClient.html to get the most recent version in all its glory (or lack thereof)

Want to test against a server other than https://rpiadc.com? Build your own using [ADCInstaller](https://github.com/bsakai2000/ADCInstaller), a set of scripts which generates the entire ADC stack given a clean Ubuntu 18.04.3 installation.
