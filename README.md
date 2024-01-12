# ansible-os
Ansible playbook for Opensearch2

## Deploy OpenSearch 2

```bash
ansible-playbook --inventory $INVENTORY_DIR --user=root --become ./$REPO_NAME/site.yml
```

## Init Jaeger [rollover](https://www.jaegertracing.io/docs/1.17/deployment/#elasticsearch-rollover)

```bash
ansible-playbook --inventory $INVENTORY_DIR --user=root --become ./$REPO_NAME/jaeger-init
```
