# Sample HTTPD Microservice for OKD

This is a simple microservice using Apache HTTPD, containerized and ready to be deployed on an OKD cluster.

## Structure

- `Dockerfile`: Builds the httpd container with a custom index.html
- `openshift/`: Contains OpenShift YAML manifests

## Build and Push

```bash
docker build -t <your-dockerhub-username>/sample-httpd .
docker push <your-dockerhub-username>/sample-httpd
