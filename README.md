# k8scontainer
auto build kubernets images by docker hub from gcr.io.

# How to check the stable version of Kubernetes?
https://storage.googleapis.com/kubernetes-release/release/stable.txt

# How to check the images from gcr.io?
https://console.cloud.google.com/gcr/images/google-containers/GLOBAL?project=google-containers

# How to check which image and version will be used in kubeadm?
kubeadm init --dry-run | grep image
