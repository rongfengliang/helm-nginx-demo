# nginx deploy

## How to deploy

* add repo

```code
helm repo add --username=admin --password=password jira http://hostip/chartrepo/jira

```

* install

```code
helm install jira/nginx
```
