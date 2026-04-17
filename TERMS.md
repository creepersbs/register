# Terms of Service
[![Banner](https://raw.githubusercontent.com/creepersbs/.github/refs/heads/main/profile/mini-banner.png)](https://creepers.sbs)

---

## Acceptance of Terms

By **submitting a Pull Request, Issue, or any request** to register, manage,
or transfer a subdomain under the **`creepers.sbs`** or **`creepers.cloud`**
domains, you **explicitly confirm** that you have read, understood,
and agree to these Terms of Service.

This acceptance is mandatory **every time a Pull Request is submitted or updated** (via checkmark). 
If you do not agree with these Terms, **do not submit a request**.

---

## Relationship with the MIT License

The source code contained in this repository is licensed under the **MIT License**.

The MIT License applies **only to the source code** and **does not grant any rights**
to use the **creepers.sbs** or **creepers.cloud** services, domains, or infrastructure.

Use of the service is governed **exclusively** by these Terms of Service.

---

## Service Description

The **creepers.sbs** service is a **free subdomain service** operated by  
**CreeperHUB / Giocoliere** (referred to as **“CH”**).

Subdomains are requested via **GitHub Pull Requests**, reviewed **manually**,
and approved at the sole discretion of CH.

Once approved, the requester receives control over the DNS records
associated with the subdomain, including the ability to use
**custom Name Server (NS) records**, if requested.

---

## Request Process & Templates

Subdomain requests are made via Pull Requests using the official templates:

- **Single TLD request template** https://github.com/creepersbs/register/blob/main/domains/template.json

- **Complete request template (all supported TLDs)** https://github.com/creepersbs/register/blob/main/domains/complete.template.json
  
Requests not following the templates or containing false or incomplete information may be rejected.



### Strict PR Requirements
To ensure service stability, we enforce a **Zero-Manual-Fix Policy**.
Users are solely responsible for ensuring the PR is perfectly formatted:
- **Perfect JSON:** Requests must follow the templates exactly. Any syntax errors will result in the PR being rejected or deferred until corrected by the requester.
- **Correct Placement:** All files must be in the correct directory. We will no longer manually modify or move your files for you.
- **No Reservations:** Requests are only accepted for **already existing and functional** services. Pointing to `localhost`, `test`, `1.1.1.1`, `0.0.0.0`, or similar placeholder IPs is strictly forbidden.

Issues may be opened for questions or clarification:  
https://github.com/creepersbs/register/issues/new

---

## User Responsibility

You acknowledge that **you are solely responsible** for:

- DNS configuration and management
- Content hosted on the subdomain
- Any website, service, application, or server reachable through the subdomain
- Compliance with all applicable laws and regulations

### Anti-Alt Account Policy
Creating multiple accounts to bypass the registration limits is strictly prohibited. 
- Accounts will be scrutinized; if an account is found to be an "alt" or created solely for domain hoarding on creepers.sbs, the request will be cancelled. 
- Fraudulent requests create significant delays in our response times for the entire community.

CH **assumes no responsibility** for:

- Abuse or illegal activity
- DNS misconfiguration
- Downtime or service interruption
- Data loss
- Reputational or financial damage
- Any consequence arising from the use of the subdomain

---

## DNS & Name Server Usage

If you request or configure **custom NS records**:

- You fully manage the DNS zone using your own provider
- CH has **no technical control** over your DNS configuration
- Any misuse, error, or violation remains **entirely your responsibility**

CH reserves the right to revoke a subdomain if DNS usage violates these Terms.

---

## Restricted and Reserved Names

CH reserves the right to **update the reserved terms list at any time without prior notice**. 
You agree **not to request or use** the following under any `creepers.sbs` root domain:

1. **Country or continent codes** (e.g. `en.creepers.sbs`, `eu.creepers.sbs`)  
   → Allowed: `anything.en.creepers.sbs`

2. **Shop / store / ecommerce** names that may appear official

3. **Official Mimicry (Minecraft/Staff)** Since there are currently **no official creepers.sbs Minecraft servers**, names that imply official status are prohibited as root subdomains. This includes: `mc`, `play`, `smp`, `network`, `bedwars`, `staff`, `admin`.
   → Allowed: `mc.yourserver.creepers.sbs`

4. **Official or system-related names** (`about`, `status`, `whois`, `translate`, or similar)

5. **Any domain listed in the reserved domains list** https://github.com/creepersbs/register/tree/main/domains/reserved/list.json

6. **Social media names** that could impersonate official creepers.sbs / CH accounts

Violating requests may be rejected or removed without notice.

---

## Verification & Checks

CH reserves the right to **periodically verify** the usage of any registered subdomain.

Verification may include:
- Visiting the associated website
- Connecting to a game server

If a Minecraft server uses a whitelist, access must be granted to:
**`Giocoliere`**

---

## Removal & Takedown

CH may suspend or remove any subdomain if:

- These Terms are violated
- False or misleading information was provided
- The GitHub account or repository used for registration is deleted
- The subdomain is involved in abuse, scams, phishing, malware, or illegal activity
- A **verified third party** submits a takedown request

### Transparency Ledger (`/removed` folder)
We now maintain a public list of terms and domains removed for violations in the [`/removed`](https://github.com/creepersbs/register/edit/main/domains/removed) folder. Entries are logged as: 
- **Blacklisted name** - **Previous owner** - **Category: TOS/DMCA/OTHER** - **Requesting Party** - **Reason**

### Third-Party Identity Verification

For a third-party takedown request to be considered valid, the requesting party
**must prove their identity and standing**.

The requester must be **one of the following**:

- The legitimate copyright holder of the affected product or content
- A legally authorized representative of the copyright holder
- A **notable individual, company, or organization** whose name, brand, or product
  is being abused or impersonated
- A recognized **institution or authority** reporting a verified violation

In addition, the requester must provide **clear and verifiable proof** of the violation, such as:

- Evidence of copyright ownership or trademark rights
- Documentation or public records proving affiliation or authority
- A clear explanation of how the subdomain violates their rights or policies
- Any additional information reasonably required by CH

Requests that are **unverifiable, anonymous, frivolous, or abusive**
will be **ignored without response**.

CH reserves the right to reject any takedown request that does not meet these requirements or that cannot be reasonably verified.


---

## Usage Limits

- Each user may register up to **2 names total**
  across **`every TLD currently available`**.
- Claiming `name.creepers.tld` reserves all supported TLDs.
- Maximum allocation: **2 `.sbs` + 2 `.cloud` + 2 `.pro` + 2 `.lol`**.

### Legacy Users (Pre 02-24-2026)
Users who successfully performed a PR before **02-24-2026 (CET)** may retain **3 names** for the original TLDs (`.sbs` and `.cloud`). 
- If these legacy domains are removed for ToS violations or third-party requests, they **cannot be recovered**, and the user will revert to the standard 2-name limit.
- Legacy users are still limited to **2 names** for the newer TLDs (`.pro`, `.lol`).

**Limits may change at any time.** Look at "[changelogs](https://github.com/creepersbs/register/blob/main/changelogs)" to stay updated.

---

## Domain Lifecycle & Transfer

Subdomains are reserved indefinitely unless removed or transferred.

### Domain Transfer (User or Organization)

Transfers require:

1. An explicit request by the current owner
2. Contact via:
   - 📧 Email: [`hello@creeperhub.net`](mailto:hello@creeperhub.net)
   - 💬 Official Discord server: https://creepers.sbs/discord

3. The requester must:
   - Be a member of the Discord server
   - Have their **Discord username** listed in the registration file

4. Discord username changes must be reflected in the registration file

Discord is used as **additional identity verification** and does not replace GitHub ownership checks.

---

## Blacklisting

Banned domains are placed in the **blacklisted** folder and cannot be reused.

---

## Disclaimer

This service is provided **“as is”**, without warranties of any kind.

CH reserves the right to:
- Modify these Terms at any time
- Refuse, suspend, or revoke service without prior notice

Continued use of the service constitutes acceptance of the updated Terms.

---

**Last updated:** 04-17-2026
