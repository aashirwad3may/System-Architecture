## Overview
The architecture presented in the above doc is of a microservices providing following services in 5g Core.
- User Registration / Deregistration in 5g core
- Forwarding user message from source to destination and vice versa(messaging service)
- Request authentication using Oauth

## DOCUMENTS
- 5gMsgService-Architecture : HLD of the microservice
- 5gMsgServiceModules : Module decsription used in the architecture

## Performance and Scalability
- A single cluster can provide service to 30Million users
- Can handle a peak load of 50K tps by scaling horizontally


