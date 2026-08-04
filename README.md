# Eligible (eligible)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Eligible provides insurance billing APIs for healthcare businesses, enabling the integration of insurance billing experiences into healthcare applications. The platform supports eligibility verification, coverage discovery, claims submission and tracking, payment estimation, enrollment, and remittance processing across a large network of US payers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/eligible/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Billing, Eligibility, Healthcare, Insurance, Claims

## Timestamps

- **Created:** 2024-07-02
- **Modified:** 2026-04-28

## APIs

### Eligible Coverage API
The Coverage API performs real-time insurance eligibility and benefits verification for a patient against a payer. Clients submit provider NPI, payer ID, and member identity information and receive structured benefit details including plan status, copays, coinsurance, deductibles, and out-of-pocket maximums.

**Human URL:** [https://eligible.com/](https://eligible.com/)

#### Tags:

 - Coverage, Eligibility, Healthcare, Insurance

#### Properties

- [Documentation](https://eligible.com/)

### Eligible Claims API
The Claims API supports submission, tracking, and status checking of professional and institutional healthcare claims to payers across the Eligible network. The API also provides claim acknowledgement, rejection, and remittance retrieval workflows for healthcare billing applications.

**Human URL:** [https://eligible.com/](https://eligible.com/)

#### Tags:

 - Claims, Billing, Healthcare, Insurance

#### Properties

- [Documentation](https://eligible.com/)

### Eligible Payment Estimation API
The Payment Estimation API calculates expected patient out-of-pocket amounts for a service before it is rendered, combining benefit details from a coverage check with provider contracted rates and accumulators. The API helps providers offer transparent cost estimates and collect patient responsibility at the point of service.

**Human URL:** [https://eligible.com/](https://eligible.com/)

#### Tags:

 - Payment Estimation, Cost Transparency, Healthcare, Billing

#### Properties

- [Documentation](https://eligible.com/)

### Eligible Enrollment API
The Enrollment API manages the trading partner enrollment workflow that providers must complete with payers in order to exchange eligibility, claims, and remittance transactions through Eligible. The API supports submission, tracking, and status retrieval of enrollment requests.

**Human URL:** [https://eligible.com/](https://eligible.com/)

#### Tags:

 - Enrollment, Trading Partner, Healthcare, Insurance

#### Properties

- [Documentation](https://eligible.com/)

### Eligible Payers API
The Payers API exposes the directory of insurance payers supported by Eligible, including payer identifiers, names, supported transaction types, enrollment requirements, and webhook capabilities. Clients use this API to select payers and check the status of supported transactions.

**Human URL:** [https://eligible.com/](https://eligible.com/)

#### Tags:

 - Payers, Directory, Healthcare, Insurance

#### Properties

- [Documentation](https://eligible.com/)

## Common Properties

- [Website](https://eligible.com/)
- [Documentation](https://eligible.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
