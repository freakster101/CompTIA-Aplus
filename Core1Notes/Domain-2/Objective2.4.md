Objective 2.4 - Common Network Configuration Concepts

DNS Records

A Record

Definition: A DNS record that maps a hostname to an IPv4 address.
Example: Mapping www.company.com to 192.168.1.10.

AAAA Record

Definition: A DNS record that maps a hostname to an IPv6 address.
Example: Mapping www.company.com to 2001:db8::1.

Canonical Name (CNAME)

Definition: A DNS record that creates an alias for another hostname.
Example: Mapping mail.company.com to server.company.com.

Mail Exchanger (MX)

Definition: A DNS record that identifies the mail server for a domain.
Example: Directing company.com email to mail.company.com.

Text (TXT)

Definition: A DNS record used to store text-based information about a domain.
Example: Publishing domain verification information for Microsoft 365.

---

Spam Management

DomainKeys Identified Mail (DKIM)

Definition: An email authentication method that verifies a message was sent by an authorized server.
Example: A mail server signing outgoing emails with a cryptographic signature.

Sender Policy Framework (SPF)

Definition: An email authentication method that specifies which servers can send email for a domain.
Example: Allowing only Microsoft 365 servers to send email for company.com.

Domain-based Message Authentication, Reporting, and Conformance (DMARC)

Definition: An email security policy that uses SPF and DKIM to validate email messages.
Example: Rejecting spoofed emails pretending to come from company.com.

---

DHCP

Lease

Definition: A temporary assignment of an IP address to a network device.
Example: A laptop receiving an IP address for eight days.

Reservation

Definition: A DHCP configuration that always assigns the same IP address to a specific device.
Example: Reserving 192.168.1.50 for a network printer.

Scope

Definition: The range of IP addresses a DHCP server can assign.
Example: A DHCP scope of 192.168.1.100 to 192.168.1.200.

Exclusions

Definition: IP addresses within a scope that DHCP will not assign.
Example: Excluding 192.168.1.1 through 192.168.1.20 for servers.

---

Virtual LAN (VLAN)

VLAN

Definition: A logical grouping of devices that creates separate network segments on the same physical network.
Example: Placing the Finance Department on a separate VLAN from Sales.

---

Virtual Private Network (VPN)

VPN

Definition: A secure encrypted connection that allows remote access to a private network.
Example: An employee securely connecting to the company network from home.
