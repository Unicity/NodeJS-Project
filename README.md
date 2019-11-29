# NodeJS-Project

This is a sample "hello world" NodeJS project.

To startup the service graph:

  - `cd services/service-graph`
  - `make dc-graph-up-d`

To call the frontend application:

 - `curl -X GET http://localhost:48080`

To shutdown the service graph:

  - `cd services/service-graph`
  - `make k8s-graph-down`
