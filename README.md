# Multi-service K8 Deployment Reference Project

This is reference project which deploys multiple services via Kubernetes (K8) config files

Inspired by [this](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/) Udemy course by Stephen Grider

## Run Locally

Apply the K9 config files via kubectl:

```bash
kubectl apply -f k8s # apply all K8 config files within k8s director
minikube ip # get the minikube VM IP address i.e. 192.168.64.2
```

Then navigate to the VM IP address

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
