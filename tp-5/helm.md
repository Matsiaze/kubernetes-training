# Install
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
helm version

# Deploy WordPress
helm repo add bitnami https://charts.bitnami.com/bitnami
helm install wordpress bitnami/wordpress -f https://raw.githubusercontent.com/Matsiaze/kubernetes-training/main/tp-5/values.yml

# Links
https://devopscube.com/install-configure-helm-kubernetes/
