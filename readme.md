```shell

$ helm create thunes-app
$ helm package thunes-app/
$ mv *.tgz thunes-app/
$ helm repo index thunes-app/ --url https://gitlab.thunes.com/chenglim.teo/thunes-app-v1/thunes-app
$ curl -s https://raw.githubusercontent.com/teochenglim/helm-test/master/thunes-app/index.yaml
$ helm repo add thunes-app https://raw.githubusercontent.com/teochenglim/helm-test/master/thunes-app/
$ helm install myrepo thunes-app

```
