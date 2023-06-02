# Identity API Module 
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

Identity API is a microservice which is used for the creation and management of beneficaries.

### Primary Features
* Beneficiary Creation
* Beneficiary Search
* Beneficiary Management


### Patient Visit Category
* Ante natal care (ANC)
* Post natal care (PNC)
* Neonatal and infant health care services
* Childhood and adolescent health care services including immunisation
* Family planning, contraceptive services and other reproductive health care
* Care for acute simple illnesses and minor ailments 
* Management of communicable diseases
* National health programs (General OPD)
* Prevention, screening and management of non communicable diseases (NCD)

## Building From Source
This microservice is built on Java, Spring boot framework and MySQL DB.

### Prerequisites 
* JDK 1.8
* Maven 

$ ./mvn clean install

## Installation
This service has been tested on Wildfly as the application server.

### Prerequisites 
* Wildfly (or any compatible app server)
* Redis
* MySQL Database

## Integrations
* RMNCH

## Usage
All features have been exposed as REST endpoints. Refer to the SWAGGER API specification for details.

