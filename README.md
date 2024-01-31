# Networks-and-Network-Security-Google

<h1>👋Hi!!!!!!     🙅 📢🛑🚧🚨🦺⚙️(Under construction)</h1>

<h2>👨‍💻 ,💡Cybersecurity Projects:</h2> 

<h2>The following scenario describes how an Internal Security Audit is done:</h2>

Audits help ensure that security checks are made, to monitor for threats, risks, or vulnerabilities that can affect an organization’s business continuity and critical assets. 
Scenario

In this activity, you will analyze DNS and ICMP traffic in transit using data from a network protocol analyzer tool. You will identify which network protocol was utilized in assessment of the cybersecurity incident. 

In the internet layer of the TCP/IP model, the IP formats data packets into IP datagrams. The information provided in the datagram of an IP packet can provide security analysts with insight into suspicious data packets in transit.

Knowing how to identify potentially malicious traffic on a network can help cybersecurity analysts assess security risks on a network and reinforce network security.

Be sure to complete this activity before moving on. The next course item will provide you with a completed exemplar to compare to your own work. 

Scenario

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.” 

tcpdump packet data
In the DNS and ICMP log, you find the following information:

In the first two lines of the log file, you see the initial outgoing request from your computer to the DNS server requesting the IP address of yummyrecipesforme.com. This request is sent in a UDP packet.

Next you find timestamps that indicate when the event happened. In the log, this is the first sequence of numbers displayed. For example: 13:24:32.192571. This displays the time 1:24 p.m., 32.192571 seconds.

The source and destination IP address is next. In the error log, this information is displayed as: 192.51.100.15.52444 > 203.0.113.2.domain. The IP address to the left of the greater than (>) symbol is the source address. In this example, the source is your computer’s IP address. The IP address to the right of the greater than (>) symbol is the destination IP address. In this case, it is the IP address for the DNS server: 203.0.113.2.domain

The second and third lines of the log show the response to your initial ICMP request packet. In this case, the ICMP 203.0.113.2 line is the start of the error message indicating that the ICMP packet was undeliverable to the port of the DNS server.

Next are the protocol and port number, which displays which protocol was used to handle communications and which port it was delivered to. In the error log, this appears as: udp port 53 unreachable. This means that the UDP protocol was used to request a domain name resolution using the address of the DNS server over port 53. Port 53, which aligns to the .domain extension in 203.0.113.2.domain, is a well-known port for DNS service. The word “unreachable” in the message indicates the message did not go through to the DNS server. Your browser was not able to obtain the IP address for yummyrecipesforme.com, which it needs to access the website because no service was listening on the receiving DNS port as indicated by the ICMP error message “udp port 53 unreachable.”

The remaining lines in the log indicate that ICMP packets were sent two more times, but the same delivery error was received both times. 

Now that you have captured data packets using a network analyzer tool, it is your job to identify which network protocol and service were impacted by this incident. Then, you will need to write a follow-up report. 

As an analyst, you can inspect network traffic and network data to determine what is causing network-related issues during cybersecurity incidents. Later in this course, you will demonstrate how to manage and resolve incidents. For now, you only need to analyze the situation. 

This incident, in the meantime, is being handled by security engineers after you and other analysts have reported the issue to your direct supervisor. 




<img src="https://imgur.com/yuQwYT7.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/r6Dd5xX.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/EguAkvR.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/jsxmDY4.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/kH8xnRI.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/2sFRtTI.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/K9xjOlN.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/Swy5wK0.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/q6ShEXI.png" height="70%" width="70%" alt=/>

<img src="https://imgur.com/F53y8dc.png" height="70%" width="70%" alt=/>




<h1>Google Course Certification</h1>



<h2>Description</h2>
The following section shows the certification I have taken to gain experience in the field of Cybersecurity Analyst. 
<br />


<p align="center">
Certifications: <br/>
<img src="https://imgur.com/RlUFXjZ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<br />
<br />
Enter the number of passes: <br/>

<br />
<br />
Confirm your selection:  <br/>
<img src="https://imgur.com/Qn0Typr.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
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

