# Task-4-Firewall-testing
Cyber Security 

Configuring windows firewall

1) Open firewall configuration tool
   
<img width="655" height="336" alt="image" src="https://github.com/user-attachments/assets/054443f2-e210-4096-ab4d-72229fe2c4e9" />

2) List current firewall rules

   <img width="626" height="90" alt="image" src="https://github.com/user-attachments/assets/28a52f5a-915b-4ba5-ac3d-a7bf9d0fc38e" />

   <img width="1349" height="680" alt="image" src="https://github.com/user-attachments/assets/5464094e-f607-4344-ba9b-97d8793e3a29" />

   <img width="1349" height="680" alt="image" src="https://github.com/user-attachments/assets/5e0f4465-415d-40ac-bafa-084ca0770f64" />

3) Block inbound traffic on a specific port (e.g., Telnet port 23)
   
   <img width="1040" height="55" alt="image" src="https://github.com/user-attachments/assets/fc1fbbcf-28db-4da7-93e6-dc0a94de2309" />

4) Test
   
   <img width="769" height="64" alt="image" src="https://github.com/user-attachments/assets/be0965fb-7b5c-4e60-9b4d-9a0543f165ba" />

5) Remove the block
   
   <img width="690" height="78" alt="image" src="https://github.com/user-attachments/assets/5efa7df2-c95d-436e-87ab-d881c544afde" />

6) Try connection again

   <img width="423" height="94" alt="image" src="https://github.com/user-attachments/assets/3b4a5e73-d449-4ac8-9b65-e53c1b40df86" />

   <img width="677" height="254" alt="image" src="https://github.com/user-attachments/assets/995eb9a2-ad41-4773-b025-3be5ebec5de6" />

   <img width="1365" height="350" alt="image" src="https://github.com/user-attachments/assets/6ec13e4a-2011-41c7-8303-0b0e9a238193" />


   **QUESTIONS**
   
1. What is a firewall?
A firewall is a security system that monitors and controls network traffic based on predefined rules. It acts as a barrier between trusted and untrusted networks, allowing or blocking data packets to protect systems from unauthorized access.

2. Difference between stateful and stateless firewall
A stateful firewall tracks the state of active connections and makes decisions based on the context of traffic (e.g., whether it’s part of an existing session). A stateless firewall only checks individual packets against rules without remembering past traffic, making it faster but less secure.

3. What are inbound and outbound rules?
Inbound rules control incoming network traffic to your system, determining which external connections are allowed in. Outbound rules control traffic leaving your system, determining what your computer is allowed to send out.

4. How does UFW simplify firewall management?
UFW (Uncomplicated Firewall) provides a simple command-line interface to configure firewall rules easily without manually handling complex iptables commands. It allows quick enabling, disabling, and managing of rules like allowing SSH or blocking specific ports.

5. Why block port 23 (Telnet)?
Port 23 is used by the Telnet protocol, which transmits data, including passwords, in plain text. This makes it insecure and vulnerable to interception, so it’s commonly blocked to prevent unauthorized access.

6. What are common firewall mistakes?
Common mistakes include leaving unused ports open, not updating rules after network changes, misconfiguring default policies, forgetting to allow essential services, and relying solely on the firewall without other security measures.

7. How does a firewall improve network security?
A firewall improves network security by filtering malicious or unauthorized traffic, preventing intrusions, blocking harmful ports or IP addresses, and enforcing security policies to control what data enters or leaves a network.

8. What is NAT in firewalls?
NAT (Network Address Translation) is a feature in firewalls that hides internal IP addresses by translating them into a single public IP address. It helps conserve IP addresses and prevents direct access to internal network devices, adding an extra layer of protection.

