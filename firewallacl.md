The firewall has multiple Ethernet ports in this scenario only port GigEthernet 0/0 and GigEthernet 0/1 are in use. GE0/0 faces the Public/Outside or red zone and port Ethernet0/1 face the Inside or green zone. 
In this scenario the firewall provides internet access using PAT, with a static Public IP address on the outside (70.2.10.201). The Firewall also provides DHCP services to the system on network. Let's create firewall configuration!
First let's install Firewall between Outside and Inside network segments:
![Picture24](https://github.com/mikekad1/firewallsandvpns/assets/62948569/874df790-33f4-4b83-8da3-563f0bc6b2cd)

We can than assign a hostname to our Firewall appliance: 

![Picture25](https://github.com/mikekad1/firewallsandvpns/assets/62948569/f6e180d6-b155-4c83-93f2-19cd8aba3239)

Now that we changed our hostname, let's do the same with the domain name:

![Picture26](https://github.com/mikekad1/firewallsandvpns/assets/62948569/a806ec92-c110-4588-8310-642c2517c650)

We should also assign an admin password:

![Picture27](https://github.com/mikekad1/firewallsandvpns/assets/62948569/40d13000-9e79-4077-8548-beea3d757f97)

Let's set our NAT to dynamic.

![Picture28](https://github.com/mikekad1/firewallsandvpns/assets/62948569/3cecf893-6b87-4316-a545-825c6a33399e)

Next step is allowing outbound ICMP traffic:

![Picture29](https://github.com/mikekad1/firewallsandvpns/assets/62948569/bad5ca3a-dfda-4dab-87bf-b593e4aab152)

I also configured local authentication and allowed ssh/telnet:

![Picture30](https://github.com/mikekad1/firewallsandvpns/assets/62948569/b5a506ff-7f0e-4ee9-93fe-da47a3b1f03b)

We can enable SNMP traps, like so:

![Picture31](https://github.com/mikekad1/firewallsandvpns/assets/62948569/00257a7f-fe24-42c9-b171-54529f78f26f)

After that we can enable Threat Detection:

![Picture32](https://github.com/mikekad1/firewallsandvpns/assets/62948569/85d3addd-4036-4103-972d-9dfb467f67b7)

Finally let's set DHCP address range:

![Picture33](https://github.com/mikekad1/firewallsandvpns/assets/62948569/4e67f7ee-2027-4c25-a1d0-e89222a22d58)

