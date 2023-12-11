# Kubernetes Cluster Setup Scripts

This repository contains a collection of Bash scripts for setting up a Kubernetes cluster.

## Scripts

1. `init_cluster.sh` - Initializes a Kubernetes cluster, sets up `kubectl` for the user, installs Calico for networking, and verifies the nodes.
2. `install_kubernetes.sh` - Disables swap, adds the Kubernetes GPG key and repository, installs specific versions of Kubernetes components (`kubelet`, `kubeadm`, `kubectl`), and disables their automatic updates.
3. `setup_containerd.sh` - Sets up Containerd, configures kernel modules and network parameters for Kubernetes, installs and configures Containerd, and verifies its status.

## Usage

Run the scripts in the following order:
1. `setup_containerd.sh`
2. `install_kubernetes.sh`
3. `init_cluster.sh`

Ensure you have root or sudo privileges for executing these scripts.

## Prerequisites

- A Linux system
- Access to the internet
- Sudo privileges

For detailed information on each script, refer to the comments within the scripts.

