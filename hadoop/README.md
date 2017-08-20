## Deploy hadoop to server command
```
# ansible-playbook -i hosts deploy-master-playbook.yml
```

## Format Namenode command
```
# ansible-playbook -i hosts format-namenode-playbook.yml
```

## Start Hadoop master command
```
# ansible-playbook -i hosts start-master-all-playbook.yml
```

## Start Hadoop all slave command
```
# ansible-playbook -i hosts start-slave-all-playbook.yml
```

## Start slave node command
```
# ansible-playbook -i hosts start-slave-node-playbook.yml --extra-vars "slave_node=slave"
```
