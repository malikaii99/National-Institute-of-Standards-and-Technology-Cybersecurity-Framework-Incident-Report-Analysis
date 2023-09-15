# National-Institute-of-Standards-and-Technology-Cybersecurity-Framework-Incident-Report-Analysis
My assignment involves utilizing this security incident as a foundation for devising a strategy to enhance a company's network security in accordance with the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF).
<h1>Description</h1>
In this task, I leveraged the knowledge I have acquired regarding networks to conduct an analysis of a network incident. My analysis is based on the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF), and the outcome is the creation of an incident report. The NIST CSF is a voluntary framework that encompasses standards, guidelines, and best practices designed to effectively manage cybersecurity risks. For a quick review, please refer to the provided reading on NIST frameworks and the five functions integral to the NIST CSF framework.

Developing a high-quality cybersecurity incident report and employing the CSF methodology can contribute to building trust and enhancing security practices within a organization. The CSF is adaptable and can be applied across a diverse range of scenarios. The ability to discern which security measures align with specific business requirements will empower you to make informed decisions when it comes to selecting the most suitable network security options available.
<h2>Scenario</h2>
Review the scenario below.

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

- <a> To address this security event, the network security team implemented: </a>
  - A new firewall rule to limit the rate of incoming ICMP packets
  - Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
  - Network monitoring software to detect abnormal traffic patterns
  - An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

<h3>Incident Report Analysis</h3>

The cybersecurity unit within a company probed into a security incident that disrupted the internal network for a duration of two hours. The disruption transpired due to a malicious actor flooding the network with ICMP packets by exploiting an inadequately configured firewall. The DDoS attack affected numerous devices within the network.

Upon identifying the attack, the network security team implemented several precautionary measures to tackle the issue. These included implementing a new firewall rule to restrict the rate of incoming ICMP packets, conducting source IP address verification on the firewall to identify spoofed IP addresses in incoming ICMP packets, employing network monitoring software to detect abnormal traffic patterns, and utilizing an IDS/IPS system to filter certain ICMP traffic based on suspicious characteristics.

A number of these protective measures were designed to prevent future ICMP packet flooding incidents.

The incident management team responded by blocking incoming ICMP packets, temporarily taking all non-critical network services offline, and reinstating critical network services. This action resulted in normal internal network traffic being unable to access any network resources. Furthermore, all incidents were reported to upper management and, if applicable, to appropriate legal authorities.

To recuperate from a DDoS attack initiated by ICMP flooding, restoring access to network services to a state of normal functioning is crucial. In future occurrences of external ICMP flood attacks, firewall restrictions can be utilized to prevent the attack. This can be followed by suspending all non-critical network services to diminish internal network traffic. The subsequent step involves prioritizing the restoration of critical network services. Finally, once the surge of ICMP packets has subsided, non-critical network systems and services can be gradually brought back online.

In summary, the company encountered a security incident where all network services suddenly ceased functioning. The cybersecurity team determined that a distributed denial of service (DDoS) attack had taken place, characterized by an overwhelming influx of ICMP packets. In response, the team promptly blocked the attack and suspended non-critical network services to prioritize the restoration of critical ones.
