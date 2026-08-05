**Incident report analysis**

**Instructions**

As you continue through this course, you may use this template to record your findings after completing an activity or to take notes on what you've learned about a specific tool or concept. You can also use this chart as a way to practice applying the NIST framework to different situations you encounter.

| Summary | Organizations observed a DoS attack for over 2 hours until it was resolved. Impacts on all internal network services unavailable throughout the attack.  An unconfigured firewall vulnerability was used by threat actors to flood ICMP packets in the internal network of the organization. The Cybersecurity team responded by stopping non-critical operations to allow traffic for critical operations and restoring them.  |  |  |
| :---- | :---- | ----- | ----- |
| Identify | The internal network was vulnerable with an unconfigured firewall. No configured IDS/IPS to filter traffic in the network. Absence of network monitor applications to analyze and trace behaviors and anomalies in the internal network. Authentication and accessibility limit configuration for resource utilization by personnel. Impacts affected all Critical and non-critical business operations. The affected network needs fast restoration of Critical operations to reduce organizational loss. |  |  |
| Protect | Firewall should be configured properly before enabling the processes to prevent this from happening again. A new firewall rule to limit the rate of incoming ICMP packets. IDS/IPS should be implemented to filter the traffic in the network. A network packet and traffic monitoring application should setup and  monitor behaviours in the internal network. Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets. |  |  |
| Detect | Network packets and behaviour monitoring tools. Continuous monitoring in incoming and outgoing traffic at every part of the whole internal network is mandatory to detect before and while threat actors act. |  |  |
| Respond | Action plan: Configure firewall rules to guard against common network attacks, especially by limiting incoming ICMP packet rates.  IDS/IPS implementing in the network to filter traffic. Detecting and acting on anomalous behavior A mandatory network monitoring and reporting team with network monitoring and analyzing tools with expertise in knowledge. Source IP address verification in firewall to check for spoofed IP address on incoming ICMP packets. Segmenting Networks in their operation needs , enabling backup for critical operations for business continuity. |  |  |
| Recover | Operations halted by the DoS attack are restored by clearing network traffic for business operation by assessing any problems or attacks faced in the future with help of fast incident response cybersecurity team with available information to investigate and restore operations faster. Post-incident review and lessons learned. Updating incident response playbooks. Communication with stakeholders during downtime. |  |  |

---

| Reflections/Notes: |
| :---- |

