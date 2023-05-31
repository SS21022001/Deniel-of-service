# Deniel-of-service
Cyber Security


Denial of Service (DoS) is a cyber-attack on an individual Computer or Website with the intent to deny services to intended users. Their purpose is to disrupt an organization’s network operations by denying access to its users. Denial of service is typically accomplished by flooding the targeted machine or resource with surplus requests in an attempt to overload systems and prevent some or all legitimate requests from being fulfilled. For example, if a bank website can handle 10 people a second clicking the Login button, an attacker only has to send 10 fake requests per second to make it so no legitimate users can login. DoS attacks exploit various weaknesses in computer network technologies. They may target servers, network routers, or network communication links. They can cause computers and routers to crash and links to bog down. The most famous DoS technique is Ping of Death. The Ping of Death attack works by generating and sending special network messages (specifically, ICMP packets of non-standard sizes) that cause problems for systems that receive them. In the early days of the Web, this attack could cause unprotected Internet servers to crash quickly. It is strongly recommended to try all described activities on virtual machines rather than your working environment Following is the command for performing flooding of requests on an IP

## ping ip_address –t -65500

HERE,

“ping” sends the data packets to the victim.

“ip_address” is the IP address of the victim.

“-t” means the data packets should be sent until the program is stopped.

“-l(65500)” specifies the data load to be sent to the victim.

Other basic types of DoS attacks involve

Flooding a network with useless activity so that genuine traffic cannot get through. The TCP/IP SYN and smurf attacks are two common examples.

Remotely overloading a system’s CPU so that valid requests cannot be processed.

Changing permissions or breaking authorization logic to prevent users from logging into a system. One common example involves triggering a rapid series of false login attempts that lockout accounts from being able to log in.

Deleting or interfering with specific critical applications or services to prevent their normal operation (even if the system and network overall are functional).
