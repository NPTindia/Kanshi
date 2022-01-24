# kanshi
Deep Learning in  Network  monitoring ( கண்காணிப்பு )  

# 1. Introduction

 The Internet is designed to carry data by using IP packets across the network and deliver,  as per destination given its header segment. Challenge is to monitor above mentioned IP packets in a given enterprise  network and permit the same IP packet to travel to a defined destination mahine. IP packets have few variations such as TCP, UDP and ICMP.  Moreover, mentioned IP packets need  to use PORTs in a given Machine to deliver.  
 
 
 <p align="center">
  <img alt="Light" src="https://user-images.githubusercontent.com/58679469/150729053-6a1deae5-f6a2-46e0-bac0-7dd676c96e04.png" width="35%">
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Dark" src="https://user-images.githubusercontent.com/58679469/150728889-8eb74247-8fc9-4691-96a6-9899583756f0.png" width="55%">
</p>



<div align="justify"> The derogatory term “scrub” means several different things. One definition is someone (especially a game player) who is not good at something (especially a game). By this definition, we all start out as scrubs, and there is certainly no shame in that. I mean the term differently, though. A scrub is a player who is handicapped by self-imposed rules that the game knows nothing about. A scrub does not play to win.</div>


     <dt>justify</dt>
        <dd> There have been events in which unwanted and harmful IP packets are used  to perform certain act in a remote machine.  Thus, there is a need to stop such IP packets in a given enterprise network and provide safety  to users of the internet in their enterprise. Volume of IP packets travels in a given enterprise network requires a huge amount of computing power to monitor IP packets and safeguard their user application. .</dd>
  


 <div  id="content">
 <p> 
 
 
 Throughout 2021, we observed low  sophistication threat actors learn that they  could create big impacts in the operational  technology (OT) space—perhaps even bigger than they intended. Actors will continue to  explore the OT space in 2022 and increasingly use ransomware in their attacks. This targeting  will occur because of the need to keep OT environments fully operational, especially when the systems are part of critical infrastructure. Attacks against critical OT environments can cause serious disruption and even threaten human lives, thereby increasing the pressure for organizations to pay a ransom. To compound the issue, many of these OT devices are not built with security at the forefront of the design, and we’re currently seeing a massive uptick in the number of vulnerabilities being identified in OT environments

 Autonomous monitoring systems require “capturing IP packets “ in neal time and infer safety level of enterprise network,  Digital Assistant with AI provides a method to monitor a given enterprise IP network. 
</p>
 
 </div>

![vv4](https://user-images.githubusercontent.com/58679469/150686392-ab116404-3be5-4d41-b347-e30a8ebe09d3.png)

Above mentioned Assistant is designed to have conversations with Human user.  To have effective and efficient conversion, a design is expected to include “ Intents”  that are very useful for Assistant to narrow down questions and synthesise answers in a given time frame.  “Entities “ expected to helpAssistant to understand conversion from Human at other end.  For example, Port can be intent and entities can be Port is blocked, Port is opened etc. Essentially, there can be manu entities have association with one Intent.   Dialog is useful part for Human being to have conversation with a given Assistant and find out information from Network Monitoring Task.  



# 2. Problem Definition 

Packet sniffing provides IP packets for analysis.  Often, mentioned analysis is expected to happen in near real time.   IBM Watson Assistant provides a tool set to design “கண்காணிப்பு Monitoring  Assistant '', in a short period of time and deploy it in cloud or in on-premise infrastructure.  



![v5](https://user-images.githubusercontent.com/58679469/150686405-8ccc22ac-616a-49d8-95d4-24df45d4ec12.png)


Kanshi Assistant is required to perform  deep learning model based inference on one side and continue to have a meaningful conversation with Human being. IB< Watson Assistant provides infrastructure for design and development of Kanshi Assistant.  Moreover, experts in network security can handle the above mentioned design and development of Kanshi Assistant.  In fact, during development, No limitations, no complications, no code required to build Kanshi Assistant. 


# 3. Tool Set  used in creating  Kanshi Assistant 

## 3.1 IBM Watson Assistant

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


## 3.2 Hardwaare for Flow Collection 

Flow collection requires custom made hardware and associated software such that near real time Packet capture cam be carried out.   IBM Security QRadar Network Packet Capture (MTM 4412-F2C) offers an optional IBM Security QRadar  Packet Capture appliance to store and manage data that is used by QRadar Incident Forensics when no other network packet capture (PCAP) device is deployed. Any number of these appliances can be installed as a tap on a network or sub-network to collect the raw packet data.

QRadar® Network Insights appliances connect to network TAPs, SPAN, or mirror ports to access full packet data for real-time analysis. All QRadar Network Insights appliances provide detailed analysis of network flows to extend the threat detection capabilities of QRadar.


### 3.2.1 TAP
TAP devices provide a way to access the data flowing across a computer network, typically for the benefit of network security and performance monitoring tools. The monitored traffic is referred to as the “pass-through” traffic and the ports used for monitoring are called “monitor ports.” For a greater visibility into the network, a TAP can be placed between the router and the switch.



### 3.2.1 SPAN
Port mirroring, also known as SPAN or roving analysis, is a method of monitoring network traffic that forwards a copy of each incoming and/or outgoing packet from one or more port (or VLAN) of a switch to another port where the network traffic analyzer is connected. SPAN is often used on simpler systems to monitor multiple stations at once

## 3.3 QRadar for Flow Collection

IBM® QRadar® Network Insights 1940-C (MTM 4654-F7G) appliance provides detailed analysis of network flows to extend the threat detection capabilities of IBM QRadar. QRadar Network Insights 1940-C is based on the Dell R740xd XL server



![v7](https://user-images.githubusercontent.com/58679469/150686420-3b85e3df-344a-4cc8-923a-427ebbfc8b3e.png)


Berkeley Packet Filters (BPF) provide a powerful tool for intrusion detection analysis. Use BPF filtering to quickly reduce large packet captures to a reduced set of results by filtering based on a specific type of traffic. Both admin and non-admin users can create BPF filters

Build complex filter expressions by using modifiers and operators to combine protocols with primitive BPF filters



QRadar collects network activity information, or what is referred to as "flow records".  Flows represent network activity by normalizing IP addresses, ports, byte and packet counts, as well as other details, into "flows", which effectively represent a session between two hosts. QRadar can collect different types of flows, which differ greatly in the collected details. In this video series, we explain and demonstrate the differences between the following network flow capture mechanisms:

<ul>
  <li> Cisco Netflow </li>
   <li> QRadar QFlow  </li>
   <li> QRadar Network Insights (QNI)  </li>
</ul>

Difference between QRadar events and flows??,  packet header and payload: which information is available in the header and packet, and which technologies to use to investigate header and payload information.

QRadar analyzes your flow data for applications, flow direction, and superflows. You also learn how to build a QRadar flow rule, and how to perform flow searches in QRadar.

IBM Security QRadar flows represent network activity by normalizing IP addresses, ports, byte and packet counts, and other data, into flow records, which are records of network sessions between two hosts. Flows are a differentiating component in QRadar that provide detailed visibility into your network traffic.


# 4. Mathematical Model 



What is the need to model binary data? </br> 
What we can do with model? </br>
How probability is assigned  to binary vector ? </br>
how this is connected to the weights of Boltzmann Machine?


Boltzmann Machine models set of Binary Vectors  </br>
How to use Boltzmann machine to detect unusual behaviour of Complex Systems?. For example vital sign monitoring by using Boltzmann machine

Build a model for Normal state. </br>
For example use data of TCP/IP flow  in Enterprise  Network   to model Normal state 

Measured state is Captured Flow 

![image](https://user-images.githubusercontent.com/58679469/150720790-06437eee-0d69-4565-bf28-27e7123f4f4d.png)


Find out  this state is part of normal state or something new, in case new, then this abnormal detection need to be notified to concerned subscribers.

Measurements of any kind, in any experiment, are always subject to uncertainties or errors, as they are  more often called. Measurement process is, in fact, a random process described by an abstract probability distribution whose parameters contain the information  desired. The results of a measurement are then samples from this distribution which allow an estimate of the theoretical parameters. In this view, measurement errors can be seen then as sampling errors.


![image](https://user-images.githubusercontent.com/58679469/150721619-b67ae977-e55d-4f39-994c-c60d87382577.png)


Probability mass function (PMF) is a function that gives the probability that a discrete random variable is exactly equal to some value

A probability mass function differs from a probability density function (PDF) in that the latter is associated with continuous rather than discrete random variables. A PDF must be integrated over an interval to yield a probability.

The probability distribution of a random variable is a function that takes the sample space as input and returns probabilities: in other words, it maps possible outcomes to their probabilities.

"Posterior", in this context, means after taking into account the relevant evidence related to the particular case being examined. The posterior probability distribution is the probability distribution of an unknown quantity, treated as a random variable, conditional on the evidence obtained from an experiment or survey



Poisson sampling is a sampling process where each element of the population is subjected to an independent Bernoulli trial which determines whether the element becomes part of the sample

Poisson distribution expresses the probability of a given number of events occurring in a fixed interval of time 

![image](https://user-images.githubusercontent.com/58679469/150721702-1f34218d-a4ac-49cc-83d7-3802fb65dbc7.png)

Boltzmann machine:  Each undirected edge represents dependency. In this example there are 3 hidden units and 4 visible units. 

This is a restricted Boltzmann machine.

Restricted Boltzmann Machines are probabilistic. As opposed to assigning discrete values the model assigns probabilities. At each point in time the RBM is in a certain state. The state refers to the values of neurons in the visible and hidden layers v and h.

![image](https://user-images.githubusercontent.com/58679469/150721809-68974f08-992c-4a26-ae39-67401350a75a.png)


This is the point where Restricted Boltzmann Machines meets Physics for the second time. The joint distribution is known in Physics as the Boltzmann Distribution which gives the probability that a particle can be observed in the state with the energy E. As in Physics we assign a probability to observe a state of v and h, that depends on the overall energy of the model. Unfortunately it is very difficult to calculate the joint probability due to the huge number of possible combination of v and h in the partition function Z. Much easier is the calculation of the conditional probabilities of state h given the state v and conditional probabilities of state v given the state h... .....and so on. the essential is here, energy-based probability

Reconstruction is different from regression or classification in that it estimates the probability distribution of the original input instead of associating a continuous/discrete value to an input example.


![v9](https://user-images.githubusercontent.com/58679469/150686429-1e6be85d-d9fc-4d70-8b89-55f7433b1748.png)

Bayesian networks are directed acyclic graphs (DAGs) whose nodes represent variables in the Bayesian sense: they may be observable quantities, latent variables, unknown parameters or hypotheses. Edges represent conditional dependencies; nodes that are not connected (no path connects one node to another) represent variables that are conditionally independent of each other. Each node is associated with a probability function that takes, as input, a particular set of values for the node's parent variables, and gives (as output) the probability (or probability distribution, if applicable) of the variable represented by the node.

Probabilistic graphical model that represents a set of variables and their conditional dependencies via a directed acyclic graph (DAG)

Mostly this part is getting attraction in DL

Gibbs sampling is applicable when the joint distribution is not known explicitly or is difficult to sample from directly, but the conditional distribution of each variable is known and is easy (or at least, easier) to sample from.  The Gibbs sampling algorithm generates an instance from the distribution of each variable in turn, conditional on the current values of the other variable. Gibbs sampling is particularly well-adapted to sampling the posterior distribution of a Bayesian network, since Bayesian networks are typically specified as a collection of conditional distributions.  Given an input vector v we are using p(h|v)  for prediction of the hidden values h. Knowing the hidden values we use p(v|h)for prediction of new input values v. This process is repeated k times. After k iterations we obtain an other input vector v_k which was recreated from original input values v_0

 ## 4.1  Quantitative Risk assessment 
 
 This can be measured as the direct cost of the risk and indirect cost of the risk
 Mathematical representation of the risk in statistical terms gets very complex and is beyond the present scope of the paper. When using quantitative risk assessment looks logical, there some drawbacks of this approach in using for information systems. It’s easy to define the cost of the system, but the indirect costs are high, and the recovery cost is high and sometimes unknown. This quantitative risk is described mathematically as Annualized Loss of expectancy (ALE). The expected risk in terms of cost and loss in monetary terms can be expressed as the loss occurred due to risk over a year.
ALE=SLE* ARO
SLE (Single Loss Expectancy) is the value of a single loss of the asset. This may or may not be the entire asset. This is the impact of the loss. ARO (Annualized Rate of Occurrence) is how often the loss occurs. 

The quantitative risk assessment for information systems comes with a huge error margin as this method was not designed primarily for information systems in focus. Nowadays, there is a lot of improvement with new data processing and the high availability of data to use complex statistical processes to extrapolate and uncover hidden trends and risks. The statistical process also ensures that the quantitative risk assessment is repeatable and reproducible with the same consistency 

The main reason for this is complexity in the identification and assigning of value to assets and limitations of statistical data, which helps in determining the frequency
 
 ## 4.2  Quantitative Risk assessment 
 
 Assumption in qualitative risk assessment is that there exists a high degree of uncertainty of impact values and likelihood that’s defined. Risk is subjective in terms of issues where the greater the difficulty in qualitative risk is in describing the likelihood and impact values. These values should be standard scaled so that it can be used with consistency across different risk assessment methods Some drawbacks of qualitative risk assessment are harder to communicate the results to management without precise information. Just saying the risk is high or low will not give a better understanding. To improve and overcome this hurdle, a table with impact and likelihood tables and the potential impact will assist the management in better handling the risk.

 
# 5. Sanshi Assistant Design

![NetworkSecurityLab](https://user-images.githubusercontent.com/58679469/150686458-0f1f0f10-84d9-4580-a694-15644f2064ec.jpg)

# 6. Sanshi Assistant Development 

![NetworkSecurityLab(1)](https://user-images.githubusercontent.com/58679469/150686463-becf05b1-cd0e-4d4c-868e-d07a55f7f4f2.jpg)

# 7. Sanshi Assistant Deployment


![NetworkSecurityLab(4)](https://user-images.githubusercontent.com/58679469/150686584-18f43ef8-22f9-4664-8c13-a7345a1b0000.jpg)


# Reference 

1. https://cloud.ibm.com/registration?target=/developer/watson/launch-tool/conversation&hideTours=true&cm_sp=WatsonPlatform-WatsonPlatform-_-OnPageNavCTA-IBMWatson_Conversation-_-Watson_Developer_Website&cm_mmca1=000027BD 
2.  ..

