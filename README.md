# CompTIA Security+ SY0-701 notes
 Notes for Security+ SY0-701 
## 1.0 General Security Concepts 12%
## 2.0 Threats, Vulnerabilities, and Mitigations 22%
## 3.0 Security Architecture 18%
## 4.0 Security Operations 28%
## 5.0 Security Program Management and Oversight 20%

## General Security Concepts

## Threats, Vulnerabilities, and Mitigations
* Cross-site request forgery attacks work by submitting data to a web site (for example, by manipulating a URL) from an authenticated trusted user without that user’s knowledge. The malicious code that performs this attack could be executed by tricking the user to click a link in an e-mail message or on a web site. Cross-site request forgery attacks often use a client-side scripting language such as JavaScript to execute code, which then sends data to a trusting web site without the user knowing. Disabling JavaScript reduces this likelihood; however, some web sites may not function properly as a result. Web sites that allow user credentials to be saved enable attackers to exploit the trust a web site has for an authenticated user at any time.

* Pass the hash - Hashes are sent over the network instead of usernames and passwords. If a malicious user can retrieve the hash, such as from server memory, she could access other network resources as the authenticated user

* SSL stripping is considered an HTTPS downgrade attack, whereby a malicious user intercepts user HTTPS requests. The attacker makes an HTTPS connection to the requested site, but the client connection to the attacker, unknown to the client, is still HTTP, thus is not encrypted

## Security Architecture
* The 802.1x standard is used to first authenticate connecting computers using PKI (Public Key Infrastructure) certificates before allowing network access. Ethernet switches, wireless routers, and VPN concentrators are examples of devices that can forward 802.1x authentication requests to an authentication server.

* An SSL VPN enables the user’s web browser to connect securely to a VPN appliance over TCP port 443 to access internal network services. Site-to-site VPNs (always-on VPNs) can use SSL to link sites together.(IPSec VPNs no TCP)

* IPSec can be configured to use transport mode encryption, meaning all network traffic can be encrypted regardless of what type of network traffic it is.

## Security Operations
* Internet Control Message Protocol (ICMP) reports on network congestion and reachability. Utilities such as ping and tracert use ICMP as their transport mechanism

* Cross-site scripting attacks involve an attacker injecting malicious code to a web site that others then visit. The malicious code could then possibly run on a site visitor’s computer. Web site developers must validate submitted user data to ensure that malicious code is not being uploaded to the web site

* Physical port security -  Switches can utilize MAC address filtering to restrict which computers can plug into specific switch ports. 802.1x-compliant switches can authenticate connecting computers before allowing network access

## Security Program Management and Oversight
* Management buy-in and enforcement - For policies to be effective, management must approve and support them, including ensuring enforcement

* Risk = probability x loss
* ALE = SLE * ARO
* SLE = Value * EF


* TPM = ENCRYPT
* TLS TPM HSM?