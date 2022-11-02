# openvpn_as
openvpn access server + 破解连接数限制
# install
```
 wget http://swupdate.openvpn.net/as/clients/openvpn-as-bundled-clients-17.rpm
 wget http://swupdate.openvpn.net/as/openvpn-as-2.9.2_04614689-CentOS7.x86_64.rpm
 
 yum install ./openvpn-as-bundled-clients-17.rpm
 yum install ./openvpn-as-2.9.2_04614689-CentOS7.x86_64.rpm
 
 systemctl restart openvpnas
 ```
 # 替换破解文件后重新初始化
```
\cp pyovpn-2.0-py3.6.egg /usr/local/openvpn_as/lib/python/
 /usr/local/openvpn_as/bin/ovpn-init
```
