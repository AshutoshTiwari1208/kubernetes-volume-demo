# HOW TO RUN THIS APP IN k8's CLUSTER

## Follow the steps 👇

1. Download Minikube & kubectl

2. ```minikube start```

3. ```kubectl apply -f deployment.yaml```

4. ```kubectl apply -f service.yaml```

> Now deployment and service are created, to expose it we need to give an additional command in minikube

5. ```minikube service story-service```

> Now, you can access the application! 😃

```Note:```: The data stored through post route ```/story``` will be persisted even when container crashes. Although it will be destroyed when pod is removed.

