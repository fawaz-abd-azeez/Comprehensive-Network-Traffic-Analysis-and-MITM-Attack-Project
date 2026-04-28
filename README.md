# Comprehensive-Network-Traffic-Analysis-and-MITM-Attack-Project

 ## Executive Summary

This project focuses on analyzing network traffic and understanding how communication happens between devices in a network. It also demonstrates how Man-in-the-Middle (MITM) attacks can be performed in a controlled lab environment. Using command-line tools, the project shows how attackers can intercept unencrypted data and highlights the importance of secure communication.

 ## Objectives
 
- To understand how network traffic flows across a system
- To capture and analyze packets using industry tools
- To simulate MITM attacks in a safe environment
- To identify risks in unencrypted communication
- To learn the importance of network security and encryption 
  
## Tools Used

- TShark – Packet capture and protocol analysis
- Tcpdump – Lightweight network traffic analyzer
- Ettercap – MITM attack simulation using ARP poisoning
- Bettercap – Advanced network attack and monitoring framework

## Project Structure
```
network-traffic-analysis-mitm/
│
├── README.md
├── commands.txt
└── project-report.pdf
```

## Methodology

  1.  Set up a controlled lab environment for testing
  2. 	Captured live network traffic using TShark and Tcpdump
  3. 	Applied filters to analyze specific protocols like HTTP and DNS
  4. 	Performed ARP spoofing using Ettercap and Bettercap
  5. 	Intercepted and analyzed traffic between target devices
  6. 	Observed how sensitive data can be exposed in unencrypted communication

  ## Key Findings
  
 - 	Unencrypted HTTP traffic can expose sensitive information such as login credentials
 - 	DNS and other protocols can reveal user activity on the network
 -  HP spoofing can successfully position an attacker between devices
 -  Network traffic can be easily monitored if proper security measures are not applied

  ## Results
 -  Successfully captured and analyzed live network traffic
 -  Demonstrated MITM attacks using ARP spoofing
 -  Identified risks in insecure network communication
 -  Gined practical understanding of real-world network security scenarios

## Security Implications

 - Unencrypted communication (such as HTTP) can expose sensitive data like usernames and passwords
 - Attackers can use techniques like ARP spoofing to intercept and monitor network traffic
 - Lack of encryption makes it easier to capture and modify data in transit
 - DNS traffic can reveal user browsing activity if not properly secured
 - Insecure network configurations increase the risk of unauthorized access and data leakage

## Conclusion

This project provided practical experience in network traffic analysis and demonstrated how common attack techniques like MITM can compromise communication. It clearly shows the risks of using unencrypted protocols and weak network configurations.
Overall, the project emphasizes the importance of using secure protocols (such as HTTPS), proper network security measures, and continuous monitoring to protect data and systems from potential attacks.

## Author

**Fawaz Abdul Azeez**

 Cybersecurity Researcher
