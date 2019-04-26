# K8s Redis Helm Chart exmaple

Example is done in minikube, but can easily be used in Aws using EBS backed volumes.

# Requirements

* minikube
* helm 
* kubectl

# Install

## Install Brew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
## Install VirtualBox
```
brew cask install virtualbox
```

## Install MiniKube
```
brew cask install minikube
```
## Install Helm & kubectl
```
brew install kubernetes-helm
brew install kubectl
minikube start
helm init
helm status
```

## Standup
```
helm install redis/
```

## Teardown
```
minikube delete
```
