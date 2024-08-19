The above file help you  to configure docker in your window machine . If you  still  see the issue than  please run  below command 

restart the daemon sudo update-alternatives --set iptables /usr/sbin/iptables-legacy
sudo update-alternatives --set ip6tables /usr/sbin/ip6tables-legacy
 
sudo dockerd & 
