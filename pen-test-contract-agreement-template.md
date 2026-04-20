# Penetration Testing Contract Agreement

**This Penetration Testing Contract Agreement ("Agreement") is entered into as of [DATE] by and between:**

- **Client:** [CLIENT COMPANY NAME], a [STATE/COUNTRY] [entity type, e.g., corporation], with its principal place of business at [CLIENT ADDRESS] ("Client")
- **Service Provider:** [PROVIDER COMPANY NAME], a [STATE/COUNTRY] [entity type], with its principal place of business at [PROVIDER ADDRESS] ("Provider")

---

## 1. Scope of Work

### 1.1 Authorized Systems
The Provider is authorized to perform penetration testing activities **only** on the following systems, networks, and assets:

| Asset / System | IP Range / URL | Description |
|---|---|---|
| [System Name] | [IP / URL] | [Brief description] |
| [System Name] | [IP / URL] | [Brief description] |

### 1.2 Testing Types
The following types of testing are authorized under this Agreement (check all that apply):

- [ ] Network Penetration Testing (External)
- [ ] Network Penetration Testing (Internal)
- [ ] Web Application Penetration Testing
- [ ] Mobile Application Penetration Testing
- [ ] Social Engineering / Phishing Simulation
- [ ] Wireless Network Assessment
- [ ] Physical Security Assessment
- [ ] Other: [SPECIFY]

### 1.3 Out-of-Scope Items
The following systems, networks, and activities are **explicitly excluded** from this engagement:

- [Out-of-scope system or activity]
- [Out-of-scope system or activity]
- Third-party systems or infrastructure not owned or leased by the Client, unless written authorization from the third party has been obtained.

---

## 2. Authorization

### 2.1 Written Authorization
The Client hereby grants the Provider written authorization to conduct security testing activities as defined in Section 1. This Agreement serves as the formal written authorization required to conduct the penetration test.

### 2.2 Authorized Representatives
The following individuals are authorized to approve changes to the scope or provide instructions to the Provider during the engagement:

| Name | Title | Contact |
|---|---|---|
| [Name] | [Title] | [Email / Phone] |

### 2.3 Emergency Contact
In the event of a critical finding or disruption to systems, the Provider will immediately contact:

- **Primary Contact:** [Name], [Phone], [Email]
- **Secondary Contact:** [Name], [Phone], [Email]

---

## 3. Rules of Engagement

### 3.1 Testing Window
- **Start Date:** [START DATE]
- **End Date:** [END DATE]
- **Permitted Testing Hours:** [e.g., 09:00–17:00 local time / 24x7 / specify]

### 3.2 Testing Approach
- **Methodology:** [e.g., Black-box / Grey-box / White-box]
- **Testing will be conducted:** [Remotely / On-site / Both]

### 3.3 Prohibited Actions
The Provider **must not** perform the following without prior written approval:

- Denial-of-service (DoS) or distributed denial-of-service (DDoS) attacks against production systems.
- Destruction, alteration, or exfiltration of Client data beyond what is necessary to demonstrate a finding.
- Social engineering against Client employees without explicit prior written consent.
- Physical access attempts to Client facilities without explicit prior written consent.
- Testing of any systems not explicitly listed in Section 1.1.

### 3.4 Data Handling
- All data accessed or collected during the engagement will be treated as confidential.
- Sensitive data (e.g., PII, credentials) discovered during testing will be documented by reference only and **will not** be exfiltrated (i.e., unauthorized removal or copying of data) or retained beyond what is necessary to produce the deliverables.
- All data collected during testing will be securely destroyed within [NUMBER] days after delivery of the final report.

---

## 4. Deliverables

The Provider will deliver the following upon completion of the engagement:

- **Executive Summary Report** – A high-level summary of findings suitable for non-technical stakeholders.
- **Technical Report** – Detailed findings including vulnerability descriptions, evidence (screenshots, payloads), risk ratings, and remediation recommendations.
- **Risk Rating Framework:** [e.g., CVSS, DREAD, or custom]
- **Report Delivery Date:** [DATE]
- **Report Format:** [e.g., PDF, Word]

Optional deliverables (if agreed upon):

- [ ] Remediation re-test after fixes are applied
- [ ] Presentation of findings to stakeholders
- [ ] Raw tool output / logs

---

## 5. Fees and Payment

### 5.1 Engagement Fee
The Client agrees to pay the Provider a total fee of **$[AMOUNT]** for the services described in this Agreement, payable as follows:

| Milestone | Amount | Due Date |
|---|---|---|
| Deposit (upon signing) | $[AMOUNT] | [DATE] |
| Final payment (upon report delivery) | $[AMOUNT] | [DATE] |

### 5.2 Additional Fees
Any work performed outside the agreed scope will require a written change order and may result in additional fees at the Provider's standard rate of **$[RATE] per hour**.

### 5.3 Expenses
[Specify whether travel, lodging, or other expenses are included or billed separately.]

---

## 6. Confidentiality

### 6.1 Mutual Confidentiality
Both parties agree to keep all information shared during this engagement strictly confidential. This includes, but is not limited to:

- Client system architecture, vulnerabilities, and security posture.
- Provider methodologies, tools, and proprietary techniques.
- The existence and terms of this Agreement.

### 6.2 Duration
Confidentiality obligations under this Agreement shall remain in effect for **[NUMBER] years** following the termination or expiration of this Agreement.

### 6.3 Exceptions
Confidentiality obligations do not apply to information that:

- Is or becomes publicly known through no breach of this Agreement.
- Is required to be disclosed by law or court order (with prompt written notice to the other party).
- Was independently developed without use of confidential information.

---

## 7. Limitation of Liability

### 7.1 Provider Liability
The Provider's liability to the Client for any claims arising under this Agreement shall not exceed the total fees paid by the Client under this Agreement.

### 7.2 No Warranty
The Provider does not warrant that the penetration test will identify all vulnerabilities present in the Client's environment. The results represent a point-in-time assessment and should not be construed as a guarantee of security.

### 7.3 Consequential Damages
In no event shall either party be liable for indirect, incidental, special, or consequential damages arising out of or related to this Agreement, even if advised of the possibility of such damages.

---

## 8. Indemnification

The Client agrees to indemnify, defend, and hold harmless the Provider and its employees, contractors, and agents from any third-party claims, damages, or expenses arising from:

- Client's misrepresentation of ownership or authorization over the systems tested.
- Client's failure to notify relevant third parties (e.g., ISP, cloud providers) as required.

---

## 9. Compliance and Legal

### 9.1 Legal Compliance
The Client represents that it has the legal right and authority to authorize penetration testing of all systems listed in Section 1.1, including any cloud-hosted or co-located infrastructure subject to third-party terms of service.

### 9.2 Third-Party Notifications
The Client is responsible for notifying any relevant third parties (e.g., internet service providers, cloud platform providers, managed service providers) of the planned testing to comply with applicable terms of service and laws.

### 9.3 Governing Law
This Agreement shall be governed by and construed in accordance with the laws of the State/Country of **[JURISDICTION]**, without regard to its conflict of law provisions.

### 9.4 Dispute Resolution
Any disputes arising under this Agreement shall first be subject to good-faith negotiation. If unresolved, disputes shall be submitted to binding arbitration in **[LOCATION]** under the rules of **[ARBITRATION BODY, e.g., AAA]**.

---

## 10. Term and Termination

### 10.1 Term
This Agreement is effective as of the date first written above and continues until the deliverables described in Section 4 have been delivered and accepted, or until terminated as provided herein.

### 10.2 Termination for Convenience
Either party may terminate this Agreement upon **[NUMBER]** days' written notice. In the event of termination, the Client shall pay for all work performed through the termination date.

### 10.3 Immediate Termination
Either party may terminate this Agreement immediately if the other party materially breaches this Agreement and fails to cure such breach within **[NUMBER]** days of written notice.

---

## 11. General Provisions

### 11.1 Entire Agreement
This Agreement constitutes the entire agreement between the parties with respect to its subject matter and supersedes all prior agreements, representations, and understandings.

### 11.2 Amendments
Any amendments to this Agreement must be made in writing and signed by authorized representatives of both parties.

### 11.3 Severability
If any provision of this Agreement is found to be unenforceable, the remaining provisions shall continue in full force and effect.

### 11.4 Independent Contractor
The Provider is an independent contractor and not an employee, partner, or agent of the Client.

---

## 12. Signatures

By signing below, the authorized representatives of both parties agree to the terms and conditions of this Agreement.

**CLIENT**

| | |
|---|---|
| Signature: | ___________________________________ |
| Printed Name: | ___________________________________ |
| Title: | ___________________________________ |
| Date: | ___________________________________ |

**SERVICE PROVIDER**

| | |
|---|---|
| Signature: | ___________________________________ |
| Printed Name: | ___________________________________ |
| Title: | ___________________________________ |
| Date: | ___________________________________ |

---

*This template is provided for informational purposes only and does not constitute legal advice. Consult a qualified attorney before using this document in an actual engagement.*
