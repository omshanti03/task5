# task5
To Build a Kubernetes Cluster Locally with Minikube
 step 1) install minikube and kubectl

 step 2) run>  minikube start

 step 3) create deployment.yaml and service.yaml

 step 4) run>   kubectl apply -f deployment.yaml
                kubectl apply -f service.yaml
 
 step 5) run>   minikube service my-app-service      to open browser for nginx server   

 step 6) scale the deployment by>  kubectl scale deployment my-app --replicas=5

 step 7) use> kubectl describe deployment my-app

 step 8) Cleanup.  kubectl delete service my-app-service
                   kubectl delete deployment my-app
                   minikube stop
                   minikube delete
 
