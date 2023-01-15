# FlaskBackend-Docker-Azure
A boilerplate repository showcasing how to deploy a flaskbackend container in Azure.


1. Create a simple Flask App (app.py) which can be simply run with the following command: python3 app.py

![image](https://user-images.githubusercontent.com/14300941/212502179-3a42069b-b1a8-4f64-9ba8-58187347dc67.png)



2. Dockerize the Flask APP.
The Docker eliminates the guest host and the hypervisor.
If there is a development, testing and production environment and I am using a specific version of let's say, redis. Then Redis will need to be installed manually 3 times. By using Docker we are encapsulating both the code and its dependencies in a single place: a container and share the container.

We can have in the same machine, different containers running different applications doing different stuff without interferring with other containers.


3. Create Azure resource group, registry.
4. Push the docker image into the registry.
5. Publish the App on Azure Cloud using Azure App Services.
