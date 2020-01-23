# ECK-on-K8s

## install minikube virtualbox kubernetes-cli
```
brew cask install virtualbox
brew install kubernetes-cli
brew upgrade kubernetes-cli
brew cask install minikube
minikube delete
minikube start --cpus 4 --memory 8192
minikube addons enable ingress
minikube dashboard
```