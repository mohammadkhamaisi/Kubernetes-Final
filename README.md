# Kubernetes Deployment with Ingress task:
To use the spring music website all you need to do is follow these simple steps:
1) clone the yaml files to your computer
2) use the commands “kubectl apply -f kubernetes-spring.yaml” which creates the pods and connects to the service ClusterIP.
3) to create another pod, we need to scale the pod created by the deployment by using the command “kubectl scale --replicas=2 deployment spring-app”
4) next you will need to use the command “kubectl apply -f ingress.yaml”, access the website through localhost/music
