Incident Report Analysis: DDoS Attack

Summary

The company experienced a security event when all network services suddenly stopped responding. The cybersecurity team found the disruption was caused by a Distributed Denial of Service (DDoS) attack through a flood of incoming ICMP packets. The team responded by blocking the attack and stopping all non-critical network services so that critical network services could be restored.

Identify

A malicious actor targeted the company with an ICMP flood attack. The entire internal network was affected. All critical network resources needed to be secured and restored to a functioning state.

Protect

The cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets and deployed an IDS/IPS system to filter suspicious ICMP traffic.

Detect

The cybersecurity team configured source IP address verification on the firewall to identify spoofed IP addresses on incoming ICMP packets and implemented network monitoring software to detect abnormal traffic patterns.

Respond

For future security events, the cybersecurity team will isolate affected systems to prevent further disruption to the network. They will attempt to restore any critical systems and services that were disrupted by the event. The team will then analyze network logs to identify suspicious or abnormal activity. All incidents will be reported to upper management and appropriate legal authorities when applicable.

Recover

To recover from a DDoS attack caused by ICMP flooding, access to network services must be restored to a normal functioning state. Future mitigation measures include blocking external ICMP flood attacks at the firewall and reducing internal network traffic by temporarily stopping non-critical services. Critical services should be restored first. Once the ICMP flood traffic has subsided, all remaining non-critical systems and services can be brought back online.