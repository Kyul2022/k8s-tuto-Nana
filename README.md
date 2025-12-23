# This is a demo basic project on minikube. The objective is
# to deploy a very simple MongoDB app wwith a simple Web App. The
# principle is that the service is like the static IP address for a pod, which will also load balance among many instances of a pod depending on their availability. So for each pod we need a service and a deployment file.
# Apart from that We'll also need a ConfigMap file and a Secret file.
# Good to notice that StatefulSets are the equivalent of deployment files but for components requiring persistance. "# k8s-tuto-Nana" 
