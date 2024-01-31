# Networks-and-Network-Security-Google

<h1>👋Hi!!!!!!     🙅 📢🛑🚧🚨🦺⚙️(Under construction)</h1>

<h2>👨‍💻 ,💡Cybersecurity Projects:</h2> 

<h2>The following scenario describes how an Internal Security Audit is done:</h2>

Audits help ensure that security checks are made, to monitor for threats, risks, or vulnerabilities that can affect an organization’s business continuity and critical assets. 

Scenario

In this activity, I was able to analyze DNS and ICMP traffic in transit using data from a network protocol analyzer tool. I identified which network protocol was utilized in the assessment of the cybersecurity incident. 

In the internet layer of the TCP/IP model, the IP formats data packets into IP datagrams. The information provided in the datagram of an IP packet can provide security analysts with insight into suspicious data packets in transit.
Knowing how to identify potentially malicious traffic on a network can help cybersecurity analysts assess security risks in a network and reinforce network security.

Scenario

As a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

I was tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, I visited the website and you also received the error “destination port unreachable.” Next, I loaded my network analyzer tool, tcpdump, and loaded the webpage again. This time, I received a lot of packets in your network analyzer. The analyzer showed that when I send UDP packets and receive an ICMP response returned to my host, the results contain an error message: “udp port 53 unreachable.” 

<img src="https://imgur.com/xewEjpJ.png" height="70%" width="70%" alt=/>

tcpdump packet data
In the DNS and ICMP log, I found the following information:

In the first two lines of the log file, I saw the initial outgoing request from my computer to the DNS server requesting the IP address of yummyrecipesforme.com. This request is sent in a UDP packet.

Next, I found timestamps that indicate when the event happened. In the log, this is the first sequence of numbers displayed. For example 13:24:32.192571. This displays the time 1:24 p.m., 32.192571 seconds.

The source and destination IP address is next. In the error log, this information is displayed as: 192.51.100.15.52444 > 203.0.113.2.domain. The IP address to the left of the greater than (>) symbol is the source address. In this example, the source is your computer’s IP address. The IP address to the right of the greater than (>) symbol is the destination IP address. In this case, it is the IP address for the DNS server: 203.0.113.2.domain

The second and third lines of the log show the response to your initial ICMP request packet. In this case, the ICMP 203.0.113.2 line is the start of the error message indicating that the ICMP packet was undeliverable to the port of the DNS server.

Next are the protocol and port number, which displays which protocol was used to handle communications and which port it was delivered to. In the error log, this appears as: udp port 53 unreachable. This means that the UDP protocol was used to request a domain name resolution using the address of the DNS server over port 53. Port 53, which aligns to the .domain extension in 203.0.113.2.domain, is a well-known port for DNS service. The word “unreachable” in the message indicates the message did not go through to the DNS server. Your browser was not able to obtain the IP address for yummyrecipesforme.com, which it needs to access the website because no service was listening on the receiving DNS port as indicated by the ICMP error message “udp port 53 unreachable.”



The remaining lines in the log indicate that ICMP packets were sent two more times, but the same delivery error was received both times. 

Now that I have captured data packets using a network analyzer tool, it is my job to identify which network protocol and service were impacted by this incident. Then, I will need to write a follow-up report. 

As an analyst, I can inspect network traffic and network data to determine what is causing network-related issues during cybersecurity incidents. Later in this course, I will demonstrate how to manage and resolve incidents. For now, I only need to analyze the situation. 

This incident, in the meantime, is being handled by security engineers after you and other analysts have reported the issue to your direct supervisor. 


<img src="https://imgur.com/LpxZjqF.png" height="70%" width="70%" alt=/>

# Another Example:

I am a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. My organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, My organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

A new firewall rule to limit the rate of incoming ICMP packets

Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

Network monitoring software to detect abnormal traffic patterns

An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, I am tasked with using this security event to create a plan to improve my company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). I will use the CSF to help me navigate through the different steps of analyzing this cybersecurity incident and integrate my analysis into a general security strategy:

Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential security gaps. 

Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

<img src="https://imgur.com/vFHWIjR.png" height="70%" width="70%" alt=/>

<h1>Google Course Certification</h1>



<h2>Description</h2>
The following section shows the certification I have taken to gain experience in the field of Cybersecurity Analyst. 
<br />


<p align="center">
Certifications: <br/>
<img src="https://imgur.com/RlUFXjZ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>


<h2> 🤳 Connect with me:</h2>

[<img align="left" alt="JoshMadakor | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube]
[<img align="left" alt="JoshMadakor | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="JoshMadakor | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="JoshMadakor | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

[twitter]: https://twitter.com/joshmadakor
[youtube]: https://www.youtube.com/c/joshmadakor
[instagram]: https://www.instagram.com/joshmadakor/
[linkedin]: https://linkedin.com/in/joshmadakor

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

