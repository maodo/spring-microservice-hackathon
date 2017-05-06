# spring-microservice-hackathon
[![Build Status](https://travis-ci.org/peterszatmary/spring-microservice-hackathon.svg?branch=master)](https://travis-ci.org/peterszatmary/spring-microservice-hackathon)

Project about how to build microservices with spring ecosystem.

## Used Spring modules / technologies
- **spring cloud config server** : for holding all configuration files for all microservices.
## Microservice application architecture with communication

- **user-microservice** : simple microservice with any external communication. Communicates just at the beginning with configuration-server microservice to obtain configs.
- **config-server** : holds all configs for all microservices in all spring profiles.

