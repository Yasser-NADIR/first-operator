# First operator in go and k8s with Kubebuilder

> This project is my first operator in k8s using kubebuilder as SDK

> This porject deploy a simple service and deployment under a controller manager who will supervise them as anytime they deleted or changed in state, it will remaine always the same state

>it deploy nginx in deployment and a service of type node port that will expose the nginx port 80