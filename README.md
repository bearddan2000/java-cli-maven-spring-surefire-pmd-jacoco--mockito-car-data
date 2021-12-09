# java-cli-maven-spring-surefire-pmd-jacoco--mockito-car-data

## Description
A POC for spring app. Testing done with surefire
pmd and jacoco plugins using mockito framework.

## Tech stack
- java
- maven
  - spring
  - surefire
  - pmd
  - jacoco
  - mockito
    - junit5

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/junit-5)
- [Jacoco config](https://www.baeldung.com/jacoco)
