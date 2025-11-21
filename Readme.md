# CPU Autoscaling Demo for Kubernetes

This is a demo to study how the Horizontal Pod Autoscaling reacts to increased loads.


## Architecture
The C++ demo use a simple CPU burn method to simulate load. The Frontend sends request for the number of active users.

Kubernetes is used for deployment.

Tested with minikube on a local dev PC.


For more technical details see this [Blogpost](http://localhost:7428/posts/projects/kubernetes/kubernetes-for-the-seasoned-noncloud-software-developer.html)

## Usage

run `setup.sh` then run `run-demo.sh`, which should print the running pods and call the frontend in the browser.