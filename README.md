# kubernetes

1. Deploy kubernetes resource from yaml file
    ```
    kubectl apply -f <filename.yaml>
    ```
2. command to port forward the pods
    ```
    kubectl port-forward <podname> <host_port>:<container_port>
    ```

3. create docker registry secret
    ```
    kubectl create secret docker-registry <secret_name> --docker-server=<server_url> --docker-username=<docker_registry_username> --docker-password=<docker_registry_password> --docker-email=<docker_registry_email>
    ```