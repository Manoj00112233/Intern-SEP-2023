Intern ID : HPTI-SEP23-140

<img src="https://raw.githubusercontent.com/Manoj00112233/Intern-SEP-2023/main/Tools/Wireshark/wireshark.png">
<h1><a href="https://github.com/wireshark/wireshark">Wireshark</a></h1>

What is WireShark?

Wireshark is an open-source network protocol analyzer that allows you to capture and analyze network traffic in real-time. It is widely used by network administrators, security professionals, and developers for network troubleshooting, analysis, and security assessments.

Wireshark provides a graphical interface that displays captured network packets, allowing you to inspect and analyze their contents. It supports a wide range of network protocols, making it a versatile tool for analyzing different types of network traffic.


Here's a more detailed about key features and functionalities of Wireshark:

Packet Capture: Wireshark captures network packets from various sources such as wired or wireless interfaces, and even from saved capture files.

Protocol Support: It supports a vast number of network protocols, including Ethernet, TCP/IP, UDP, HTTP, DNS, SSL/TLS, DHCP, and many more. This enables the analysis of different layers of the network stack.

Live Packet Analysis: Wireshark provides real-time analysis of captured packets, allowing you to monitor network traffic and diagnose issues as they occur.

Packet Filtering: It offers powerful filtering capabilities to isolate and focus on specific packets of interest. Filters can be applied based on various criteria like source/destination IP addresses, protocols, ports, packet size, and more.

Packet Decoding: Wireshark decodes network packets and displays their contents in a human-readable format. This includes dissecting and presenting information from protocol headers, payloads, and other network metadata.

Detailed Packet Inspection: The tool allows you to inspect individual packets, view their timing information, analyze sequence numbers, examine error messages, and perform in-depth analysis of network behaviors.

Statistical Analysis: Wireshark provides statistical information and graphical representations to analyze network traffic patterns, identify anomalies, measure network performance, and troubleshoot issues.

Protocol Troubleshooting: With its extensive protocol support and decoding capabilities, Wireshark helps identify and diagnose network protocol-related problems, such as misconfigurations, compatibility issues, or protocol violations.

Capture File Export: Wireshark allows you to save captured packets in various file formats, including popular formats like PCAP and PCAPNG. These files can be shared and analyzed later or used for further investigation.

Overall, Wireshark is a versatile and powerful network analysis tool that helps network administrators and security professionals gain insights into network traffic, identify issues, analyze protocols, and enhance network performance and security.


Installing Wireshark:

You can download its latest version from the official website
Download: www.wireshark.org

Install Wireshark on your computer (available for Windows, macOS, and Linux).
Ensure you have the necessary permissions to capture network traffic on your device.

Capturing Network Traffic:
Launch Wireshark and select the desired network interface for packet capture.
Click on “Start” to initiate real-time packet capture.
Apply filters to capture specific types of traffic (e.g., HTTP, DNS) or packets to and from particular IP addresses.

Filtering Captured Data:
Utilize Wireshark’s powerful filtering capabilities to focus on specific data of interest.
Apply filters based on protocols, IP addresses, ports, or custom expressions.
Use logical operators (AND &&, OR ||, NOT !) to create complex filters for precise data analysis.

Analyzing Captured Packets:
Examine the lower layers (Ethernet, IP, TCP/UDP) to understand packet structure and source/destination information.
Wireshark presents captured packets in a detailed format, displaying various layers of the OSI model.

Protocol Analysis:
Wireshark automatically dissects packets and identifies the protocols used in communication.
Analyze higher-level protocols (HTTP, DNS, FTP) for application-specific data and potential issues.
Drill down into protocol details to identify malformed packets or unusual behavior.

For a Commands, Filters & Syntax you can refer this
<h1><a href="https://www.stationx.net/wireshark-cheat-sheet/">Wireshark Commands, Filters & Syntax </a></h1>

How to Use Wireshark?

1.Open Wireshark.

2.Select the “local interface” in the “Capture” section at the bottom of “The Wireshark Network Analyzer” (wireshark.exe). This can be something like “Wi-Fi [#]” if using a wireless connection, or “Ethernet [#]” if connected to the Internet using an Ethernet cable. You can see the traffic for each local interface based on the line graph the right of each. Choose one that is not flat.

3.Start capture.

4.File → Save As . . . → Wireshark . . . pcap. This is the most complete and raw form of your data. You can always load this pcap file and export different forms of the data, as needed.

5.File → Export Packet Dissections → As CSV / JSON. I like these two formats because I find them easy to parse and work with.
