**Network Security Threats Report**          

**Overview on common network security threats.**
**1. DoS Attack**
   Dos attack is referred to as Denial-of-Service attack that is used to deny legitimate users access to a resource suh as accessing a website,network,emails etc or making it extremely slow.This attack is usually implementated by hitting the target rsource such as a web server with too many requests at the same time, this results into server failure or slowing them down. The goal of DoS attack is not to gain unauthorized access to system or data but to prevent legitimate users from accessing the services.
DoS attack works by ping command; ping command is usually used to test the availability of network by sending small data packerts.But,the ping of death takes advantage of this by sending data packets above the maximum limit. Since the data packets sent are larger than what server can handle, the server can crash, freeze or reboot.In order for the attack to be more effective,the attacker attacks the target computer with pings from more than one system. The attacks led to service disruption,system overload,security risks, reputational damage, financial losses, etc..
An organization can adopt the following policy to protect itself against Denial of Service attacks:
   (a)Firewalls can be used to stop simple DoS attack by blocking all traffic coming from an attacker by identifying it's IP.
   (b)Rate limiting can be used to control the number of requests per IP or session.
   (c)Concept of load balancing can be used to distribute traffic across multiple servers.
   (d) Intrusion detection/prevention system can be used detect and block unusual traffice patterns.
Example:
   (a) February 2020,Reported by AWS: AWS reported massive DoS attack in February 2020, this attack saw incoming traffic at a rate of 2.3 Tbps.

**2. MITM Attack**
    MitM attack is referred to as Man-in-the-Middle attack that occurs when threat actor secretly intercepts & possibly alters communication between two parties who believe they are directly communicating with each other. The main aim of the attacker is to eavesdrop, manipulate, or impersonate to steal sensitive data.MitM poses serious threat to online security because they give attacker the ability to capture & manipulate information.During the attack, the attacker insert themselves in the middle of the online communication.Through the distribution og malware, the attacker gains easily access to the user's browser.
