# Network-design-proposal-for-internet-cafe

## :computer:
<p>This is a Computer Communication subject Project.</p>
<br>
This project presents a network design proposal for <b>Internet Cafe</b>. 
The design was constructed on <b>Cisco Packet Traces</b>. 
<br>

### :question: PROBLEM STATEMENT:
<p> The project is to prepare a network design proposal for an Internet cafe. 
The following are the requirements. The cafe is to support 30 users and requires a web filtering device or software to filter websites based on content.
The users need to share one ADSL internet connection. The cafe has to be managed with a billing software. </p>
 
 ### :book: ABSTRACT:
 <li>
 Network design for Internet café to support 30 users and also ensure web filtering and ADSL internet connection.</li>
<li>Primary methods used:
                       Formulating a proper plan.
                       Designing complete network diagram in Cisco Packet Tracer.
                       Creating logical and physical links between all the components.
                       Ensuring web filtering, message and packet switching
                       Ensuring that nodes and links are arranged appropriately using proper network topology. </li>

<li>The major results of our project will be – PCs being able to share and access files among each other, Users will be able to login to the main server via login credentials and serve their purposes accordingly, Message passing will also be ensured. IP addresses and connections will be appropriate based on the requirements and LAN topology. Web filtering and a proper billing method will also be implemented. </li>

<li> The final project will ensure a proper network design implemented for an Internet café supporting around 30 users at a time. All day to day activities can be successfully performed by the users at a given time. This project will ensure a proper full time running internet café.
</li>

### :electric_plug: NETWORK DESIGN:

![Picture1](https://user-images.githubusercontent.com/85094341/193050397-6e03e1b8-b0ed-4ea4-8ff2-a3903ba729fd.png)

## :scroll: MODULES DESCRIPTION: 

![Picture2](https://user-images.githubusercontent.com/85094341/193050963-8c6bf5d1-129b-4e86-8a47-d3011f27198e.png)

<b>1. Network Design Analysis</b>
To design a network for an internet cafe which has 30 users. The internet cafe has one ADSL connection which is to be shared among the users. A cafe billing management system has to be configured and deployed in the cafe.

<b>2. Design Requirement Analysis</b>
   The internet cafe is to support 30 users. So, 30 desktop computers would be required. To form a network for the computers, a switch would be required.
   Since 30 computers need to be networked, a switch with 30 ports would be required. Switches typically come with 24 ports or 48 ports. Since a 24-port switch        would not suffice the requirement, a 48-port switch is recommended.
   An ADSL router which is capable of NAT (Network address translation) is required. NAT is a mandatory feature which is required on the router, for sharing the        ADSL internet connection.
   The router, although not mandatory, needs to have the DHCP server feature installed. The DHCP server is required for providing dynamic IP addresses to the          users. 
   The availability of the feature on the router reduces/rules out the need to setup and configure an additional DHCP server on the network.

<b>3. Network Diagram </b>

<b>4.IP Address Design</b>
     The interval private IP address range for the users within the cafe is 192.168.1.0/24.
     The DHCP scope on the router should lease out IP addresses on the 192.168.1.0/24 scope.
     The IP addresses of the LAN interface of the router and the computer on which the cafe management system is setup should be configured with a static IP address      belonging to the 192.168.1.0/24 network.
     It should be ensured that the static IP addresses provided for the LAN interface of the router and the cafe management system are excluded from the DHCP scope      configured on the router for avoiding duplicate IP addressing.

<b>5. Hardware and Software Products</b>

![pic](https://user-images.githubusercontent.com/85094341/193053791-822f9398-7d52-4d9d-be17-27414e3c783a.png)



### Concepts Learnt:
1. DHCP IP addressing
2. Subnetting and Subnet mask
3. Default Gateway
4. Concept of Routers and switches
5. Sharing resources between computers (like printer)
6. Sharing resources between server and PCs
7. Firewall security
8. Restricting use of certain protocols to ensure safety





