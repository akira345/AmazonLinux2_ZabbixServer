# AmazonLinux2_ZabbixServer
AmazonLinux2でZabbixServerをインストールするAnsibleプレイブックです。

AmazonLinux2+Ansible2.4.2.0+Cygwin環境で作成しています。



```/inventries/<ホスト名>/group_vars/sites.yml```にパラメタを、hosts.iniにサーバ接続情報をセットして、



```
ansible-playbook ./inventries/zabbix3.example.com/main.yml -i ./inventries/zabbix3.example.com/hosts.ini -c paramiko
```

な感じで動かします。
