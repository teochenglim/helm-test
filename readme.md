```shell

$ helm create thunes-app
$ helm package thunes-app/
$ helm repo index thunes-app/ --url https://gitlab.thunes.com/chenglim.teo/thunes-app-v1/thunes-app
$ helm repo add thunes-app https://raw.githubusercontent.com/teochenglim/helm-test/master/thunes-app/
$ helm install myrepo thunes-app

```
