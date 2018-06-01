# dind-builder
scaleable dind (Docker-in-Docker) builder for kubernetes

# Usage
Just run `kubectl apply -f .` in the folder.

Then you can just connect to the service from any other pod like this:
- `docker --host=docker.builder.svc.cluster.local:2375 info`
