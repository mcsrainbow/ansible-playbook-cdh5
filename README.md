ansible-playbooks-cdh5
=========
Namenodes,HBase,Hive,HTTPFS,Oozie,Pig,Zookeeper,Spark <br />
<br />
Steps:<br />
------------------
1. Specify the hosts in hosts.cdh5 <br />
2. Specify the configuration values in groups_var/cdh5-all <br />
3. Make sure all hosts can be logged into as root or normal user with sudo permissions <br />
4. Run 'ansible-playbook cdh5.yml -i hosts.cdh5 -u heydevops --sudo -k' <br />
