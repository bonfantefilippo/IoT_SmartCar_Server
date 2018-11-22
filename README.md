# SmartCar IoT Project

IoT project that provide communication between SmartCart data_simulator e database(s).
This server is useful to receive and retreive data through different protocols:
 - case HTTP: API to write and retrieve data related to generated date
 - case MQTT 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Neccessary technology useful to start the project

```
NodeJS
Internet Connection
Postman o other services to call API
InfluxDB
```

### Installing

A step by step series of examples that tell you how to get a development env running

Step:

```
npm install //install al packages
node index //start server
```

### HTTP 
```
Open Postman
Choose HTTP Verbs
Insert url
Send Request
```
For example:
Verb: GET
URL: http://localhost:8080/v1/sensors/
Send request

## Built With

* [NodeJS](https://nodejs.org/en/) - JavaScript runtime built on Chrome's V8 JavaScript engine
* [Restify](http://restify.com/) - Node.js web service framework optimized for building semantically correct RESTful web services

## HTTP Versioning

I use [Restify](http://semver.org/) for API versioning. 


### MQTT
```
 ADD MQTT CASE
```
For example:
little mqtt example







## Authors

* **Filippo Bonfante** - *IoTProject* - [BonfanteFilippo](https://github.com/bonfantefilippo)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
