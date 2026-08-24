<h1>Configuring a pfSense Firewall on a Server</h1>

<h2>Description</h2>
In this lab we configured NAT on a pfSense firewall for our private network hosting TargetWindows01 (IP of 10.20.1.3/32). This
IP address of 10.20.1.3 would be resolved to the private IP of 172.30.0.10, acting as the public IP for this lab. Network traffic 
is filtered through the firewall to be permitted or denied based on their port tags. Specifically, I filtered 
based on web browsing (80, HTTP), secure web browsing (443, HTTPS), DNS (Port 53), and mail servers (25, SMTP). The firewall serves 
as a gateway for traffic to flow through to reach external networks.
<br /><br />
This is crucial in modern day networks, providing port security at a fundamental level, ensuring devices can access required services 
while limiting exposure to external threats.
