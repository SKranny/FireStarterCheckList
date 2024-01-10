# FireStarter
## Check list
Completed:
- All services are developed using SpringBoot 3.2.1.
- Interaction between services using Kafka broker, as well as File-Upload service and File-Status-Processor interact with each other using FeignClient to check the file for its absence in the database for further validation and upload.
- Spring cloud config server for configuration of all services.
- All microservices can run in local mode, for this purpose each microservice has a local-config.
- Business logic of services is covered by unit-tests
- Initialization of kafka and mongo using docker-compose files for each.
- Developed and configured File-uploader, File-status-processor and File-processor microservices in accordance with the requirements and schema in the ToR.

It remains to be done:
- Cover all microservices with integration tests. I have started studying this issue, I was not familiar with them before, at the moment I have learned only their purpose and I am looking for an example of implementation.
