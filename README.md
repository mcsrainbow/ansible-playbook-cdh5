### Ansible playbook for CDH5

#### HDFS, HBase, Hive, HTTPFS, Oozie, Pig, Zookeeper, Spark

#### Steps:

```
1. Specify the hosts in hosts.cdh5
2. Specify the configuration values in groups_var/cdh5-all
3. Make sure all hosts can be logged into as root or normal user with sudo permissions
4. Run 'ansible-playbook cdh5.yml -i hosts.cdh5 -u heydevops --sudo -k'
```
