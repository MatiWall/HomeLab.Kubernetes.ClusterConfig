

```shell
docker compose run --rm -it ansible ansible-playbook -i inventories/production.yaml playbooks/master.yaml --ask-pass

```
seems you have to run argocd separately to make it work