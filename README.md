# k8s-learnings
This Repository Contains the Learning Materials Related to K8S

## To install the containerd we can use installContainerd.sh file:
```
sudo wget https://raw.githubusercontent.com/kkpdealwis/k8s-learnings/refs/heads/main/installContainerd.sh -P /tmp 
sudo bash /tmp/installContainerd.sh
sudo systemctl restart containerd.service
```

## To install kubeadm, kubelet, and kubectl we can use the installK8S.sh file:
```
sudo wget https://raw.githubusercontent.com/kkpdealwis/k8s-learnings/refs/heads/main/installk8s.sh -P /tmp
sudo bash /tmp/installK8S.sh
```
