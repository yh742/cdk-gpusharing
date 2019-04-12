# GPU Sharing for CDK

The Canonical Distribution of Kubernetes (https://jujucharms.com/canonical-kubernetes/)runs a bit differently than deployments used in kubeadm/kops. Services on the master node is ran with systemd.  

This script sets up the gpu sharing services from (https://github.com/AliyunContainerService/gpushare-scheduler-extender/blob/master/docs/userguide.md).
