<h1 align="center">
  <img src="public/firewall.png" width="100">
    <br>
    Template Script for IP-Tables.
</h1>
<p>Script to configure your ipTables at system startup.</p>

## Prerequisites :
- IP-Tables. 
- /etc/init.d activated.
- PC linux.

```
sudo apt update -y
```
```
sudo apt install iptables-persistent -y
```
Confirm that the netfilter-persistent.service is active and enabled.
```
sudo systemctl status netfilter-persistent
```
<br>
*Edit the script with your preferences and add the file to /etc/init.d

 <br>
 by Popovicz. ͡•_ゝ ͡•
