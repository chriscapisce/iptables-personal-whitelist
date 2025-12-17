# iptables-personal-whitelist

It's not really possible to have a whitelist here with private ips because you want it to be private which causes a token key after the /file.txt url.  It's not possible to load this into iptables.

# iptables-personal-whitelist

I have two types or resources for IPtables whitelists within HestiaCP.


#### 1. Local whitelist based on a .sh script. The files are hosted locally on the server.

    root@host: cd /usr/local/hestia/data/firewall/ipset/
  
- asn-personal-blacklist.sh

##### 1a. Read here how to configure local whitelist: [Configure Local Blacklists](https://github.com/chriscapisce/iptables-personal-blacklists/blob/main/Configure-Local-Blacklists.md)
  
#### 2. Remote blacklists based on a .txt file. These files are hosted on f.e. Github.

    https://raw.githubusercontent.com/chriscapisce/iptables-personal-blacklists/main/single-ips-personal-blacklist.txt

    
    

