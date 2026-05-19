*This project has been created as part
of the 42 curriculum by ldepenne*

# Description

The goal of this project is to introduce the principles of computer networks. We need to configure IP addresses, connect devices via a router and understand the role of a gateway within a network.

# Instructions

This project involves solving networking problems to make a network function properly.

	• First, download the file attached to the project's page and extract the files into any folder of your choice or go to the net_practice directorie.
	• In this folder, run the run.sh file. This shell script will launch a web server and open your preferred web browser to the dedicated page.
	• You will have the choice between the training section, which includes levels 1 to 10, or the evaluation section, which provides three random exercises from levels 6 to 10.
For each level, a non-functioning network diagram is displayed.
At the top of your window, you will see one or more objectives that you must achieve by
adjusting the available configuration so that the network functions properly. There are
two buttons you can use:

	• [Check again] to verify whether your configuration is correct.
	• [Get my config] to download your configuration whenever you need to; you will need it when submitting your assignment.
When you have successfully completed a level, a new button will appear. Click this
button to proceed to the next level.

At the bottom of the page, you will see logs. They can help you understand why your
configuration is incorrect, for example, if a gateway is missing or an IP address is
invalid.

To succeed, modify the unshaded fields until your network configuration is correct. To complete this assignment, it is strongly recommended that you understand how addressing works in a network that includes devices such as routers and switches. Read
about TCP/IP addressing to strengthen your understanding of these concepts.

# Ressources

### Subnet masks

source: [zeste de savoir](https://zestedesavoir.com/tutoriels/2789/les-reseaux-de-zero/veuillez-vous-identifier-pour-communiquer/les-masques-de-sous-reseaux-a-la-decouverte-du-subnetting/)

Subnetting is a technique that involves dividing a larger network into several subnets.
The aim is to customise the subnet masks.

### TCP/IP addressing

source: [fortinet](https://www.fortinet.com/fr/resources/cyberglossary/tcp-ip)

The TCP (Transmission Control Protocol) is a communication standard that enables the exchange of messages (packets) over a network.
It organises data so that it can be transmitted between a server and a client; it first establishes a connection between a source and its destination (to ensure transmission).
It breaks large data sets down into small packets for transmission.
SSH (Secure Shell) uses it.

In other words:
It checks the destination (the client) to see if it is there. If so, it sends all its packets to it.

IP (Internet Protocol) has become the standard for fast and secure connections. This address enables communication and data exchange with other devices.

### OSI layers

source: [fortinet](https://www.fortinet.com/fr/resources/cyberglossary/tcp-ip)

OSI (Open Systems Interconnection) splits what happens when two computers communicate over a network into seven layers. Each layer has a specific role and is responsible only for its own part.

### Default gateways

source: [zeste de savoir](https://zestedesavoir.com/tutoriels/2789/les-reseaux-de-zero/veuillez-vous-identifier-pour-communiquer/la-passerelle-les-bases-du-routage/)

A default gateway is used to connect two subnets. In practice, it is almost always a router. It is called a ‘gateway’ because it connects several subnets, and ‘default’ because when we don’t know where to send a request, we send it to the default gateway.

### routers and switches

source: [peer-to-peer](https://profile.intra.42.fr/users/tle-floc)

A router is used to connect different subnets to one another. A switch is used to connect different devices within the same subnet.