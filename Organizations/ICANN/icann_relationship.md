# ICANN and Special-Use Domains: Understanding the Relationship

## Overview

This document clarifies the relationship between the Internet Corporation for Assigned Names and Numbers (ICANN) and special-use domain names like the proposed `.agent` domain. While ICANN plays a central role in the global Domain Name System (DNS), special-use domains follow a different path that primarily involves the Internet Engineering Task Force (IETF) and the Internet Assigned Numbers Authority (IANA).

## ICANN's Role in the Domain Name System

ICANN is responsible for coordinating the global DNS, including:

1. **Managing the DNS Root Zone**: Overseeing the authoritative database of top-level domains
2. **Accrediting Domain Registrars**: Approving organizations that can register domain names
3. **Developing Domain Name Policy**: Creating policies for domain registration and use
4. **New gTLD Program**: Managing the introduction of new generic top-level domains

ICANN's primary focus is on domains that are part of the global DNS hierarchy and are resolved through the conventional DNS infrastructure.

## Special-Use Domains vs. Conventional TLDs

Special-use domains differ fundamentally from conventional top-level domains:

| Characteristic | Conventional TLDs (e.g., .com, .org) | Special-Use Domains (e.g., .onion, .local, proposed .agent) |
|----------------|-------------------------------------|-------------------------------------------------------------|
| Resolution Mechanism | Global DNS | Alternative mechanisms (P2P, local protocols, etc.) |
| Approval Process | ICANN new gTLD program | IETF standardization and IANA registration |
| Delegation in Root Zone | Yes | No |
| Commercial Registration | Typically yes | No |
| Primary Purpose | Human-readable web addresses | Technical infrastructure needs |
| Governance | ICANN policies | Technical specifications in RFCs |

## The Path for Special-Use Domains

Special-use domains follow a standardization path through the IETF rather than ICANN's new gTLD process:

1. **IETF Standardization**: The domain's purpose and technical specifications are documented in an Internet-Draft, which goes through the IETF consensus process to become an RFC.

2. **IANA Registration**: Based on the published RFC, IANA adds the domain to the Special-Use Domain Names registry.

3. **No ICANN Application**: There is no application to ICANN's new gTLD program, as the domain is not intended for delegation in the DNS root zone.

4. **No DNS Delegation**: The domain is reserved to prevent conflicts but is not actually delegated in the DNS hierarchy.

## ICANN's Relationship to Special-Use Domains

While ICANN is not directly involved in approving special-use domains, there are important relationships:

1. **IANA Function**: ICANN currently performs the IANA functions under contract with the IETF, which includes maintaining the Special-Use Domain Names registry.

2. **Coordination**: ICANN and the IETF coordinate to ensure that special-use domains do not conflict with existing or planned TLDs.

3. **Policy Consideration**: ICANN's policy development may take special-use domains into account when considering new TLDs.

4. **Technical Advice**: ICANN's technical bodies may provide input during the IETF process for special-use domains.

## Implications for the .agent Domain Proposal

For the proposed `.agent` special-use domain:

1. **No ICANN Application Required**: The `.agent` domain does not require an application through ICANN's new gTLD program.

2. **Focus on IETF Process**: Efforts should focus on the IETF standardization process rather than ICANN engagement.

3. **IANA Registration**: After successful IETF standardization, IANA will register `.agent` in the Special-Use Domain Names registry.

4. **ICANN Awareness**: While not directly involved in approval, keeping ICANN informed of the proposal may be beneficial for coordination purposes.

## When ICANN Engagement Might Be Necessary

There are limited circumstances where engagement with ICANN might be relevant:

1. **Name Collision Analysis**: If there are concerns about potential collisions with existing DNS usage.

2. **Future TLD Plans**: If ICANN is considering `.agent` as a potential future TLD.

3. **Policy Implications**: If the special-use domain has broader policy implications for the DNS.

4. **Technical Coordination**: For coordination between DNS and the alternative resolution mechanism.

## Recommended Approach for .agent

Based on precedents like `.onion` and `.local`, the recommended approach for `.agent` is:

1. **Primary Focus on IETF**: Concentrate efforts on the IETF standardization process.

2. **Minimal ICANN Engagement**: Limited to informational updates rather than seeking approval.

3. **Technical Documentation**: Clearly document how `.agent` operates outside the conventional DNS.

4. **Precedent Reference**: Reference successful special-use domains like `.onion` in documentation.

## Conclusion

While ICANN plays a crucial role in the global DNS, special-use domains like the proposed `.agent` domain follow a different path through the IETF and IANA. Understanding this distinction is important for efficiently navigating the standardization process.

The `.agent` proposal should focus on the IETF process, with ICANN engagement limited to informational coordination. By following the established path for special-use domains, the proposal can avoid unnecessary complications and focus on the technical standardization necessary for implementation.
