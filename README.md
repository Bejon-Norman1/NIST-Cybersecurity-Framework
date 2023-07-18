# Introduction

 The scenario presented by Google involves a network incident within the organization's infrastructure. In response, I will conduct a thorough analysis using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF) as a guiding framework. This analysis will culminate in the creation of an incident report that showcases my expertise in incident response and highlights my ability to apply industry best practices.

 # Goal
 
 The primary objective of this analysis is to assess the network breach and its implications. Through a systematic evaluation, I will determine the scope of the incident, identifying the specific vulnerabilities that were exploited. By leveraging the NIST CSF, which encompasses the Identify, Protect, Detect, Respond, and Recover components, I will comprehensively evaluate the incident and its associated risks.

 # Scenario
 
 You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

-To address this security event, the network security team implemented: 

-A new firewall rule to limit the rate of incoming ICMP packets

-Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

-Network monitoring software to detect abnormal traffic patterns

-An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

