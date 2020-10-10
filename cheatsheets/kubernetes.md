### Useful commands

- kubectl get all
- k get po -w
- k get secrets
- k delete all --all --all-namespaces

### Improve Productivity
- https://itnext.io/pimp-my-kubernetes-shell-f144710232a0
- https://learnk8s.io/blog/kubectl-productivity


### Install useful kube plugins
> Krew
	- Brew install krew
	- echo 'export PATH="${PATH}:${HOME}/.krew/bin"' >> ~/.zshrc

> Kubectx - to switch cluster context
	- kubectl krew install kubectx

> Kubens - to switch cluster namespace
	- kubectl krew install kubens

> Kubse-ps1 - for showing kubecontext and ns 
  - Brew install kube-ps1
