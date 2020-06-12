# deploy_with_docker_k8s

deploying a stateless django app just to test my newbie skills on Kubernetes

1- start the minikube cluster & enable igress addons


2- create the deployment, services & ingress by using this command:

$ kubectl create -f <filepath/filename>


3-retrieve ip address using this command:

$ kubectl get -f <filepath/ingress.yaml>

enjoy my cute litte baby app :)
