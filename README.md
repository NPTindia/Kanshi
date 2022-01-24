# kanshi
Deep Learning in  Network  monitoring ( கண்காணிப்பு )  

# 1. Introduction

 The Internet is designed to carry data by using IP packets across the network and deliver,  as per destination given its header segment. Challenge is to monitor above mentioned IP packets in a given enterprise  network and permit the same IP packet to travel to a defined destination mahine. IP packets have few variations such as TCP, UDP and ICMP.  Moreover, mentioned IP packets need  to use PORTs in a given Machine to deliver.  There have been events in which unwanted and harmful IP packets are used  to perform certain act in a remote machine.  Thus, there is a need to stop such IP packets in a given enterprise network and provide safety  to users of the internet in their enterprise. Volume of IP packets travels in a given enterprise network requires a huge amount of computing power to monitor IP packets and safeguard their user application.  

 Autonomous monitoring systems require “capturing IP packets “ in neal time and infer safety level of enterprise network,  Digital Assistant with AI provides a method to monitor a given enterprise IP network. 


![vv4](https://user-images.githubusercontent.com/58679469/150686392-ab116404-3be5-4d41-b347-e30a8ebe09d3.png)

Above mentioned Assistant is designed to have conversations with Human user.  To have effective and efficient conversion, a design is expected to include “ Intents”  that are very useful for Assistant to narrow down questions and synthesise answers in a given time frame.  “Entities “ expected to helpAssistant to understand conversion from Human at other end.  For example, Port can be intent and entities can be Port is blocked, Port is opened etc. Essentially, there can be manu entities have association with one Intent.   Dialog is useful part for Human being to have conversation with a given Assistant and find out information from Network Monitoring Task.  



# 2. Problem Definition 

Packet sniffing provides IP packets for analysis.  Often, mentioned analysis is expected to happen in near real time.   IBM Watson Assistant provides a tool set to design “கண்காணிப்பு Monitoring  Assistant '', in a short period of time and deploy it in cloud or in on-premise infrastructure.  



![v5](https://user-images.githubusercontent.com/58679469/150686405-8ccc22ac-616a-49d8-95d4-24df45d4ec12.png)


Kanshi Assistant is required to perform  deep learning model based inference on one side and continue to have a meaningful conversation with Human being. IB< Watson Assistant provides infrastructure for design and development of Kanshi Assistant.  Moreover, experts in network security can handle the above mentioned design and development of Kanshi Assistant.  In fact, during development, No limitations, no complications, no code required to build Kanshi Assistant. 


# 3. Tool Set For Design and Development of Kanshi Assistant 

Create and launch a highly-intelligent, AI-powered virtual agent in an hour without writing a single line of code. Connect to existing content sources and applications to get stuff done for your customers { Ref 1 ]. 



The new Watson Assistant experience, focused on using actions to build customer conversations, is designed to make it simple enough for anyone to build a virtual assistant. Building, testing, publishing, and analyzing your assistant can all now be done in one simple and intuitive interface.

<ul>
  <li>  New navigation provides a workflow for building, previewing, publishing, and analyzing your assistant.  </li>
   <li>  Each assistant has a home page with a task list to help you get started.  </li>
   <li> Build conversations with actions, which represent the tasks you want your assistant to help your customers with. Each action contains a series of steps that represent individual exchanges with a customer.  </li>
   <li> 
    A new way to publish lets you review and debug your work in a draft environment before going live to your customers.  </li>
   <li>     Use a new suite of analytics to improve your assistant. Review which actions are being completed to see what your customers want help with, determine if your assistant understands and addresses customer needs, and decide how can you make your assistant better.  </li>
</ul>


   




![v6](https://user-images.githubusercontent.com/58679469/150686417-834d2fac-1fba-40b6-b9d9-de18adc26eec.png)

Flow collection requires custom made hardware and associated software such that near real time Packet capture cam be carried out.   IBM Security QRadar Network Packet Capture (MTM 4412-F2C) offers an optional IBM Security QRadar  Packet Capture appliance to store and manage data that is used by QRadar Incident Forensics when no other network packet capture (PCAP) device is deployed. Any number of these appliances can be installed as a tap on a network or sub-network to collect the raw packet data.

TAP devices provide a way to access the data flowing across a computer network, typically for the benefit of network security and performance monitoring tools. The monitored traffic is referred to as the “pass-through” traffic and the ports used for monitoring are called “monitor ports.” For a greater visibility into the network, a TAP can be placed between the router and the switch.

To begin with, Port mirroring, also known as SPAN or roving analysis, is a method of monitoring network traffic that forwards a copy of each incoming and/or outgoing packet from one or more port (or VLAN) of a switch to another port where the network traffic analyzer is connected. SPAN is often used on simpler systems to monitor multiple stations at once

QRadar® Network Insights appliances connect to network TAPs, SPAN, or mirror ports to access full packet data for real-time analysis. All QRadar Network Insights appliances provide detailed analysis of network flows to extend the threat detection capabilities of QRadar.

The IBM® QRadar® Network Insights 1940-C (MTM 4654-F7G) appliance provides detailed analysis of network flows to extend the threat detection capabilities of IBM QRadar. QRadar Network Insights 1940-C is based on the Dell R740xd XL server



![v7](https://user-images.githubusercontent.com/58679469/150686420-3b85e3df-344a-4cc8-923a-427ebbfc8b3e.png)


Berkeley Packet Filters (BPF) provide a powerful tool for intrusion detection analysis. Use BPF filtering to quickly reduce large packet captures to a reduced set of results by filtering based on a specific type of traffic. Both admin and non-admin users can create BPF filters

Build complex filter expressions by using modifiers and operators to combine protocols with primitive BPF filters

Throughout 2021, we observed low  sophistication threat actors learn that they  could create big impacts in the operational  technology (OT) space—perhaps even bigger than they intended. Actors will continue to  explore the OT space in 2022 and increasingly use ransomware in their attacks. This targeting  will occur because of the need to keep OT environments fully operational, especially when the systems are part of critical infrastructure. Attacks against critical OT environments can cause serious disruption and even threaten human lives, thereby increasing the pressure for organizations to pay a ransom. To compound the issue, many of these OT devices are not built with security at the forefront of the design, and we’re currently seeing a massive uptick in the number of vulnerabilities being identified in OT environments

QRadar collects network activity information, or what is referred to as "flow records".  Flows represent network activity by normalizing IP addresses, ports, byte and packet counts, as well as other details, into "flows", which effectively represent a session between two hosts. QRadar can collect different types of flows, which differ greatly in the collected details. In this video series, we explain and demonstrate the differences between the following network flow capture mechanisms:

<ul>
  <li> Cisco Netflow </li>
   <li> QRadar QFlow  </li>
   <li> QRadar Network Insights (QNI)  </li>
</ul>

Difference between QRadar events and flows??,  packet header and payload: which information is available in the header and packet, and which technologies to use to investigate header and payload information.

QRadar analyzes your flow data for applications, flow direction, and superflows. You also learn how to build a QRadar flow rule, and how to perform flow searches in QRadar.

IBM Security QRadar flows represent network activity by normalizing IP addresses, ports, byte and packet counts, and other data, into flow records, which are records of network sessions between two hosts. Flows are a differentiating component in QRadar that provide detailed visibility into your network traffic.


# 4. Mathematicaal Model 
![v9](https://user-images.githubusercontent.com/58679469/150686429-1e6be85d-d9fc-4d70-8b89-55f7433b1748.png)

# 5. Sanshi Assistant Design

![NetworkSecurityLab](https://user-images.githubusercontent.com/58679469/150686458-0f1f0f10-84d9-4580-a694-15644f2064ec.jpg)

# 6. Sanshi Assistant Development 

![NetworkSecurityLab(1)](https://user-images.githubusercontent.com/58679469/150686463-becf05b1-cd0e-4d4c-868e-d07a55f7f4f2.jpg)

# 7. Sanshi Assistant Deployment


![NetworkSecurityLab(4)](https://user-images.githubusercontent.com/58679469/150686584-18f43ef8-22f9-4664-8c13-a7345a1b0000.jpg)


# Reference 

1. https://cloud.ibm.com/registration?target=/developer/watson/launch-tool/conversation&hideTours=true&cm_sp=WatsonPlatform-WatsonPlatform-_-OnPageNavCTA-IBMWatson_Conversation-_-Watson_Developer_Website&cm_mmca1=000027BD 
2.  ..

