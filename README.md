### Webserver minimalistic sets of iptables / firewall rules

Install iptables-persistent:
```sh
sudo apt-get install iptables-persistent
```

Curl to download the file to the correct location:
```sh
curl -L https://raw.githubusercontent.com/edenreich/iptables-persistent-rules/master/rules.v4 > /etc/iptables/rules.v4
```

Restart the iptables-persistent service:
```sh
sudo service iptables-persistent reload
```