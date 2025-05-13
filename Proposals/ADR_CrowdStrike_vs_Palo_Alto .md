
# ADR Title: Selection of Endpoint Security Platform: CrowdStrike vs Palo Alto Networks

## Context

DBAG is evaluating endpoint protection platforms to enhance our cybersecurity posture, particularly in the context of Zero Trust Architecture (ZTA), remote work, and cloud-first strategies. The key drivers include:

- **Functional**: Endpoint detection and response (EDR), extended detection and response (XDR), threat intelligence, and integration with existing SIEM tools.
- **Non-functional**: Ease of deployment, centralized management, scalability, and vendor support.

Both **CrowdStrike** and **Palo Alto Networks** are leading vendors in this space. CrowdStrike is known for its lightweight agent and unified console, while Palo Alto brings deep firewall expertise and broader network security capabilities.

### Options

| Option | Pros | Cons |
|--------|------|------|
| **CrowdStrike Falcon** | - Strong EDR/XDR capabilities<br>- Lightweight agent<br>- Unified console<br>- Fast deployment<br>- High user satisfaction (4.7/5) | - Limited native firewall capabilities<br>- Higher cost for full suite |
| **Palo Alto Cortex XDR** | - Strong firewall integration<br>- Broader network security suite<br>- Good for hybrid environments<br>- Strong ZTA alignment | - More complex setup<br>- Fragmented UI across products<br>- Slightly lower user rating (4.6/5) |

## Consequences

- **Positive**: Choosing CrowdStrike simplifies endpoint security management with a single-agent architecture and faster deployment. It aligns well with our cloud-first and remote work strategy.
- **Negative**: We may need to integrate third-party firewall solutions or retain existing Palo Alto firewalls for full network protection.

If Palo Alto were chosen, we’d benefit from tighter firewall integration but at the cost of a steeper learning curve and potentially slower rollout.

## Stakeholders

- Security Architecture Team  
- IT Operations  
- Enterprise Architecture  
- Compliance & Risk  
- End-User Support

## Notes (Optional)

- CrowdStrike’s strong brand and media presence may also aid in stakeholder buy-in.
- Palo Alto may still be retained for perimeter firewall services even if CrowdStrike is selected for endpoint protection.

## Conclusion

After careful evaluation, **CrowdStrike Falcon** was chosen as the preferred endpoint security platform. The decision was based on its ease of deployment, unified architecture, and alignment with the organization's cloud-first strategy. CrowdStrike's lightweight agent and fast deployment capabilities make it an ideal choice for our remote work environment, ensuring robust security without compromising performance.
