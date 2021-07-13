# Camunda Plattform with Optimize Logging Demo

*Demo to show how optimize polls the engine while a user is logged in.* 

## Get it up and running

1. Log into the camunda registry, see the [Docs](https://docs.camunda.org/optimize/3.3/technical-guide/setup/installation/#production-docker-image-without-elasticsearch) to pull the optimize image
2. Paste the optimize license key into the [OptimizeLicense.txt](./licenses/OptimizeLicense.txt).
3. Start the services `docker-compose up`.

Log into optimize (*username*: admin, *password*: admin) and keep an eye on the console output of the engine.
