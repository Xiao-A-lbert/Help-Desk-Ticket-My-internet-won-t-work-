# Help Desk Ticket: My internet won't work!

<h2>Description</h2>
In this practical help desk ticket, a user states that their internet is not working. Given the details of the ip address, subnet mask, and gateway address, here are the steps I woudld take by applying the OSI model to resolve this ticket.
<br />


<h2>Languages and Utilities Used</h2>

- <b>OSI Model</b> 

<h2>Environments Used </h2>

- <b>Help Desk Ticket Scenario</b> 

<br />
<br />
Help Desk Ticket 

![1) help desk ticket](https://github.com/user-attachments/assets/52f238e2-ad4c-468b-aa72-e57df9893e0d)

<br />
<br />
The OSI Model

![OSI-7-layers](https://github.com/user-attachments/assets/e18f8980-a3de-465b-878f-ce9fbfd006dc)

<br />
<br />
A Layer 1 solution might be to check the network cables are plugged in properly, check for visible signs of damage, and to open the adapter settings in the control panel to see if the cable is identified in Windows. 

![OSI Layer 1](https://github.com/user-attachments/assets/64e8c737-bed4-4472-b1a0-9d2763bbab5e)

<br />
<br />
A Layer 2 solution might be to check if the link light is flashing on the Network Interface Card (NIC) to see if layer 2 traffic is moved across the NIC. Also checking the ARP table to see if entries are being registered. 

![OSI Layer 2](https://github.com/user-attachments/assets/6d074778-0aed-4a72-8f50-fa335b7b2468)

<br />
<br />
A Layer 3 solution might be to run ipconfig to verify the user's ip address, subnet mask, and gateway address in the network. 
Then use ping to check connectiviity to the gateway and out to the internet. 
Next use tracert to see where connectivity might be dropped.
Finally we can use ipconfig release/renew to release/renew the DHCP and flush/register DNS to re-register the DNS.

![OSI Layer 3](https://github.com/user-attachments/assets/9298a0a6-cf6f-4e62-b504-9e98c94de178)
<br />
<br />
A Layer 4 solution might be use netstat on a linux VM to verify that the correct ports are open and they're being attached to the right network interface.

![OSI Layer 4](https://github.com/user-attachments/assets/fa1e5ec8-19cd-4fa8-bf3b-bb909d9c86fa)
<br />
<br />
Layer 5 no troubleshooting required.

![OSI Layer 5](https://github.com/user-attachments/assets/b1015e2f-0d80-495e-9c9d-24b4c3ced6d6)
<br />
<br />
A Layer 6 solution might be check if the certificates being used are correct in our browser. This might be due to internal company websites or self-signed certificates. 

![OSI Layer 6](https://github.com/user-attachments/assets/773d2a03-ca7a-42d6-a879-2ad86903e683)
<br />
<br />
A Layer 7 solution might be to check the browser console for errors, clearing browser cache, or having the user use a different browser. 

![OSI Layer 7](https://github.com/user-attachments/assets/aad9a38f-5f48-465f-92ff-9994e05ece03)<br />
<br />
