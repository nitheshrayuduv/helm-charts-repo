# helm-charts
Helm charts repository for public

To install helm client in katakoda
```sh
curl -L https://git.io/get_helm.sh | bash
```

To build the helm package
```sh
helm package tomcat
```

To generate the index.yaml page
```sh
helm repo index .
```

To add a new repo into helm client
```sh
helm init
helm repo add hung-repo https://nitheshrayuduv.github.io/helm-charts-repo/
helm repo update
helm install hung-repo/tomcat --name tomcat
helm status tomcat
helm delete tomcat
```
