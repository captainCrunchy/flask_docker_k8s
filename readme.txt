06/06/2023

Example
https://www.youtube.com/watch?v=W8CZOUINxfo

Build
docker build -t hello-world-flask .

Run
docker run -p 8080:8080 hello-world-flask

Test
http://127.0.0.1:8080/

Create a tag
docker tag hello-world-flask ep210/hello-world-flask

Login to Docker Hub
docker login

Push image to Docker Hub
docker push ep210/hello-world-flask

Deploy to Kubernetes
kubectl apply -f deployment.yml

Check Kubernetes deployment
kubectl get deployments

Delete deployment on Kubernetes
kubectl delete -f deployment.yml

Confirm clean up
kubectl get all
