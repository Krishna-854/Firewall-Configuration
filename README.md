# Firewall-Configuration
To configure and test basic firewall rules to allow or block traffic.
1.Open firewall configuration tool (Windows Firewall or terminal for UFW)
Click start button and enter windows defender firewall 
Click firewall status on/off
2.List current firewall rules
Check all Rules ----> Inbound rules and Outbound rules
3. Add a rule to block inbound traffic on a specific port
Add a rule for any port
4.Test the rule by attempting to connect to that port locally or remotely.
Open command prompt and type telnet 127.0.0.1 23 (local ip and port number)
5. Remove the test block rule to restore original state.
Select the rule which we have created and click disable rule and click on delete rule
A firewall filters network traffic by checking data packets against security rules. It examines packet information such as IP addresses, ports, and protocols to decide whether to allow or block the traffic. This helps protect the network from unauthorized access and threats.
