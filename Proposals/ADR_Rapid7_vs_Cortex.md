
# ADR Title: Selection of Threat Detection and Response Platform: Rapid7 InsightIDR vs Palo Alto Cortex XDR

## Context

DBAG is evaluating threat detection and response platforms to enhance our cybersecurity posture, particularly in the context of Zero Trust Architecture (ZTA), remote work, and cloud-first strategies. The key drivers include:

- **Functional**: Extended detection and response (XDR), threat intelligence, log management, and integration with existing SIEM tools.
- **Non-functional**: Ease of deployment, centralized management, scalability, and vendor support.

Both **Rapid7 InsightIDR** and **Palo Alto Cortex XDR** are leading vendors in this space. Rapid7 is known for its advanced analytics and enriched alerting capabilities, while Palo Alto brings deep firewall expertise and broader network security capabilities.

### Options

| Option | Pros | Cons |
|--------|------|------|
| **Rapid7 InsightIDR** | - Advanced analytics features<br>- Strong log management<br>- Enriched alerting capabilities<br>- Fast deployment<br>- High user satisfaction (4.8/5) | - Higher cost<br>- Initial setup challenges<br>- Needs improved UI for non-technical users |
| **Palo Alto Cortex XDR** | - Strong firewall integration<br>- Broader network security suite<br>- Good for hybrid environments<br>- Strong ZTA alignment | - More complex setup<br>- Fragmented UI across products<br>- Slightly lower user rating (4.6/5) |

## Consequences

- **Positive**: Choosing Rapid7 InsightIDR provides superior threat identification and detailed threat insights, aligning well with our advanced analytics needs.
- **Negative**: The higher cost and initial setup challenges may require additional training and support.

If Palo Alto Cortex XDR were chosen, we’d benefit from tighter firewall integration but at the cost of a steeper learning curve and potentially slower rollout.

## Stakeholders

- Security Architecture Team  
- IT Operations  
- Enterprise Architecture  
- Compliance & Risk  
- End-User Support

## Notes (Optional)

- Rapid7’s strong analytics and alerting capabilities may also aid in stakeholder buy-in.
- Palo Alto may still be retained for perimeter firewall services even if Rapid7 is selected for threat detection and response.

## Conclusion

After evaluating both options, **Rapid7 InsightIDR** was selected due to its advanced analytics features, strong log management, and enriched alerting capabilities, despite the higher cost and initial setup challenges.
