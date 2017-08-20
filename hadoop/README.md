# Deploy hadoop to server command
```
# ansible-playbook -i hosts deploy-master-playbook.yml
```

# Start slave node command
```
# ansible-playbook -i hosts start-slave-node-playbook.yml --extra-vars "slave_node=slave"
```
