# IANA Registration Guide for the .agent Special-Use Domain

## Overview

This guide outlines the process for registering the `.agent` special-use domain name with the Internet Assigned Numbers Authority (IANA). Unlike conventional top-level domains (TLDs), special-use domains follow a different registration path that requires IETF standardization before IANA registration.

## Understanding IANA's Role

The Internet Assigned Numbers Authority (IANA) is responsible for coordinating the DNS root, IP addressing, and other Internet protocol resources. For special-use domains:

- IANA maintains the "Special-Use Domain Names" registry
- IANA does not directly accept submissions for special-use domains
- Registration occurs only after IETF standardization via an RFC
- IANA implements the registration based on the published RFC

## Registration Process

The process for registering `.agent` as a special-use domain follows these steps:

1. **Complete the IETF Process**
   - Develop and submit an Internet-Draft
   - Work through the IETF consensus process
   - Achieve publication as an RFC
   
2. **IANA Review During RFC Process**
   - IANA reviews the document during the IETF Last Call
   - IANA confirms they can implement the requested actions
   - Any issues are resolved before RFC publication

3. **Automatic Registration After Publication**
   - Once the RFC is published, IANA automatically processes the registration
   - No separate application to IANA is required
   - IANA updates the Special-Use Domain Names registry

4. **Verification of Registration**
   - Check the IANA Special-Use Domain Names registry
   - Verify the entry contains correct information
   - Address any discrepancies if found

## Special-Use Domain Names Registry

The IANA Special-Use Domain Names registry is available at:
[https://www.iana.org/assignments/special-use-domain-names/special-use-domain-names.xhtml](https://www.iana.org/assignments/special-use-domain-names/special-use-domain-names.xhtml)

The registry includes the following information for each entry:

- **Domain Name**: The special-use domain (e.g., `.agent`)
- **Reference**: The RFC that defines the domain's special use
- **Registration Date**: When the entry was added to the registry

Additionally, each entry includes specific properties defined in RFC 6761:

- **Lookup**: Whether applications should look up these names in DNS
- **Reservation**: Whether the name is reserved in DNS
- **Other properties**: Additional behavior specifications

## IANA Considerations Section in the RFC

The RFC for `.agent` must include a specific "IANA Considerations" section that:

1. **Explicitly Requests Registration**:
   ```
   This document requests that IANA add the following entry to the
   Special-Use Domain Names registry:

   Domain Name: agent
   Reference: [this document]
   Registration Date: [date of registration]
   ```

2. **Specifies RFC 6761 Properties**:
   ```
   This document requests that IANA add the following entries to the
   "Special-Use Domain Names Properties" registry:

   Domain Name: agent
   Lookup: False
   Reservation: True
   Reference: [this document]
   ```

3. **Provides Clear Instructions**:
   ```
   The ".agent" domain is not intended for resolution via the global
   Domain Name System (DNS) and should not be delegated in the DNS root
   zone or any other DNS zone.
   ```

## Timeline Expectations

The timeline for IANA registration depends entirely on the IETF process:

- IANA review occurs during IETF Last Call (2 weeks)
- IANA implementation after RFC publication (typically 1-2 weeks)
- Total time from initial Internet-Draft to registration: 12-24 months

## Monitoring and Maintenance

After registration:

1. **Monitor the Registry**:
   - Periodically check the IANA registry for any changes
   - Ensure the entry remains accurate

2. **Address Any Issues**:
   - If issues arise, contact IANA through appropriate channels
   - Work through the IETF if substantive changes are needed

3. **Future Updates**:
   - Any changes to the registration require a new or updated RFC
   - Follow the same IETF process for modifications

## Contact Information

IANA does not accept direct submissions for special-use domains, but for general inquiries:

- **Email**: [iana@iana.org](mailto:iana@iana.org)
- **Website**: [https://www.iana.org/](https://www.iana.org/)
- **Registry Issues**: [https://www.iana.org/help/report-problems](https://www.iana.org/help/report-problems)

## Precedents and Examples

These existing special-use domains provide useful precedents:

1. **`.onion`** (RFC 7686)
   - Purpose: Anonymous services via Tor
   - Similar to `.agent` in using alternative resolution
   
2. **`.local`** (RFC 6762)
   - Purpose: Multicast DNS in local networks
   - Example of non-DNS resolution mechanism

3. **`.test`** (RFC 6761)
   - Purpose: Testing and documentation
   - Example of reservation without resolution

Reviewing these RFCs, particularly RFC 7686 for `.onion`, provides valuable guidance for the `.agent` registration.

## Conclusion

Registering `.agent` as a special-use domain with IANA is the final step in a longer IETF standardization process. By ensuring the Internet-Draft and resulting RFC contain proper IANA Considerations sections and following the IETF process diligently, the registration with IANA should proceed smoothly once the RFC is published.
