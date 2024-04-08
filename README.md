<h1>Analyze packet with Wireshark</h1>

<h2>Description</h2>
As a security analysts, we’ll need to analyze network traffic in order to learn what type of traffic is being sent to and from systems on the networks we’ll be working with.
Analyzing packets can help security teams interpret and understand network communications. Network protocol analyzers such as Wireshark, which has a graphical user interface or GUI, can help us examine packet data during your investigations. Since network packet data is complex, network protocol analyzers (packet sniffers) like Wireshark are designed to help us find patterns and filter the data in order to focus on the network traffic that is most relevant to our security investigations. So in this project, we will use Wireshark analyze a network packet capture file that contains traffic data related to a user connecting to an internet site. 

<br />

<h2>Task 1. Explore data with Wireshark</h2>

In this task, we will identify the network interfaces that can be used to capture network packet data by using the command "sudo tcpdump -D"(can also use "sudo ifconfig") to identify the interfaces that are available. 

<p align="center">
This command returns output similar to the following: <br/>
<img src="https://imgur.com/7aQkhJw.png"<br />

The Ethernet network interface is identified by the entry with the "eth" prefix.

<h2>Task 2. Inspect the network traffic of a network interface with tcpdump</h2>

In this task, we'll use tcpdump to filter live network packet traffic on the eth0 interface using the command "sudo tcpdump -i eth0 -v -c5"

This command will run tcpdump with the following options:

- <b>-i eth0: Capture data specifically from the eth0 interface.</b>
- <b>-v: Display detailed packet data.</b>
- <b>-c5: Capture 5 packets of data.</b>








<h2>Task 1. Explore data with Wireshark</h2>

In this task, we will identify the network interfaces that can be used to capture network packet data by using the command "sudo tcpdump -D"(can also use "sudo ifconfig") to identify the interfaces that are available. 

<p align="center">
This command returns output similar to the following: <br/>
<img src="https://imgur.com/7aQkhJw.png"<br />

The Ethernet network interface is identified by the entry with the "eth" prefix.

<h2>Task 2. Inspect the network traffic of a network interface with tcpdump</h2>

In this task, we'll use tcpdump to filter live network packet traffic on the eth0 interface using the command "sudo tcpdump -i eth0 -v -c5"

This command will run tcpdump with the following options:

- <b>-i eth0: Capture data specifically from the eth0 interface.</b>
- <b>-v: Display detailed packet data.</b>
- <b>-c5: Capture 5 packets of data.</b>
