# Question-1

This presumes Kubernetes and a container runtime e.g. Docker are installed.

Setup:
1. Navigate to directory containing rabbitmqsvc.yaml
2. Run `kubectl apply -f rabbitmqsvc.yaml`
3. Check that the deployment and services are running with `curl -ik http://localhost:15672`
