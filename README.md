# kubernetes

1. Deploy kubernetes resource from yaml file
    ```
    kubectl apply -f <filename.yaml>
    ```
2. command to port forward the pods
    ```
    kubectl port-forward <podname> <host_port>:<container_port>
    ```