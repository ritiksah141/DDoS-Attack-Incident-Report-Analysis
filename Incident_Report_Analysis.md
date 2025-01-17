# Incident Report Analysis

## Incident Report Overview

| Section      | Details                                                                                                                                                                |
|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Summary**  | The company experienced a security event when all network services suddenly stopped responding. The cybersecurity team found the disruption was caused by a distributed denial of service (DDoS) attack through a flood of incoming ICMP packets. The team responded by blocking the attack and stopping all non-critical network services, so that critical network services could be restored. |
| **Identify** | - A malicious actor or actors targeted the company with an ICMP flood attack.  <br> - The entire internal network was affected.  <br> - All critical network resources needed to be secured and restored to a functioning state. |
| **Protect**  | - The cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packets.  <br> - An IDS/IPS system was implemented to filter out some ICMP traffic based on suspicious characteristics. |
| **Detect**   | - Source IP address verification was configured on the firewall to check for spoofed IP addresses on incoming ICMP packets.  <br> - Network monitoring software was implemented to detect abnormal traffic patterns. |
| **Respond**  | - For future security events, the cybersecurity team will:  <br> - Isolate affected systems to prevent further disruption to the network.  <br> - Restore any critical systems and services disrupted by the event.  <br> - Analyze network logs for suspicious and abnormal activity.  <br> - Report all incidents to upper management and appropriate legal authorities, if applicable. |
| **Recover**  | - To recover from a DDoS attack by ICMP flooding:  <br> - Restore access to network services to a normal functioning state.  <br> - Block external ICMP flood attacks at the firewall.  <br> - Stop all non-critical network services to reduce internal network traffic.  <br> - Restore critical network services first.  <br> - Once the flood of ICMP packets has timed out, bring all non-critical network systems and services back online. |

---

## Reflections/Notes

- **Lessons Learned**: This incident reinforced the importance of proactive network monitoring and robust firewall configurations to mitigate DDoS attacks.  
- **Improvements for Future**: Implementing additional training for staff on identifying potential threats and refining incident response protocols.  
- **Tools and Frameworks**: Using the NIST Cybersecurity Framework to systematically address vulnerabilities proved invaluable in streamlining the response and recovery process.  
- **Actionable Steps**: 
  - Conduct regular audits of network configurations to identify misconfigurations.  
  - Upgrade firewall systems to include advanced DDoS protection.  
  - Review and update the organization's incident response plan every six months.  

---

