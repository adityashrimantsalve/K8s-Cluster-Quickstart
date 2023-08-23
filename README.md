# K8s-Cluster-Quickstart
The K8s-Cluster-Quickstart script simplifies the setup of a Kubernetes cluster, whether it's on a master or worker node.
This script streamlines the process from configuring system settings to installing essential components, resulting in a functional Kubernetes environment.

Features:

Disables SWAP and Firewall to adhere to Kubernetes requirements.
Loads kernel modules required for Kubernetes.
Configures sysctl settings to optimize networking for Kubernetes.
Installs necessary dependencies such as Docker, apt-transport-https, ca-certificates, and curl.
Installs and configures Docker and containerd.
Adds the Kubernetes apt repository key and repository.
Installs Kubernetes components: kubelet, kubeadm, and kubectl.
Initializes Kubernetes master node and sets up kubeconfig.
Deploys the Weave CNI plugin to enable networking in the cluster.
Verifies the node status using kubectl get nodes.
Usage:

Execute the script on your target system (master or worker node).
Adjust /etc/fstab as needed (if applicable).
Follow the instructions within the script's comments to execute certain sections based on your use case (master or worker).






