Identify at least 2 instances of suspicious, interesting, and/or unfamiliar protocols/communication.

### ARP and DCP-AF


I filtered on `!tcp` and found two new protocols I didn't know.

## ARP


Address Resolution Protocol is a layer II protocol. This is a broadcast request that every computer on the network can see. In this case a router is asking each device on the network for it's "BURNED IN" MAC address in order to send the request back to the right device that asked for the information from a webserver. 

![arp](https://user-images.githubusercontent.com/8258629/71586262-9727c780-2ae7-11ea-888d-46f04a75d494.PNG)


## DCP-AF
DCP Application Framing Layer

DCP is a protocol designed for communication with and between network devices. 

The Device Control Protocol is a generic, object-oriented protocol which employs a session / transaction paradigm that may be implemented on both connection and connectionless communication between resources. The object-oriented features of DCP allow the protocol to be easily applied to real world objects, or devices. Since the protocol supports both connection and connectionless communication, it offers facilities for reliable and secure communication, as well as broadcast and light-weight messaging. In my home I have a smart light buld and an Alexa. This might have been me talking to Alexa.

![dcp-af](https://user-images.githubusercontent.com/8258629/71586332-d9510900-2ae7-11ea-8314-46340744c0d0.PNG)
