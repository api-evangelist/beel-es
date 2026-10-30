# beel-es

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

BeeL (beel.es) provides a cloud‑based invoicing platform for Spanish businesses, offering the VeriFactu API that automates invoice creation, submission to the AEAT, and integration with Stripe. The service includes SDKs, CLI tools, sandbox testing, and AI‑assisted agents, supporting multi‑NIF, recurring invoices, and compliance features. Documentation, pricing, and support are publicly available.

**Areas:** invoicing · Spain · API · fintech · SaaS

## beel-es on APIs.io

Everything profiled for beel-es is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/beel-es/](https://apis.io/providers/beel-es/)** — or go straight to one of the APIs or properties below.

### APIs (54)

- [beel-es Account Companies API](https://apis.io/apis/beel-es/beel-es-accountcompanies-api/) — Listing and creating the NIFs of an account, under `/v1/accounts/{account_id}/companies`. Operating on one NIF is the `Company` resource.
- [beel-es Account Email Domains API](https://apis.io/apis/beel-es/beel-es-accountemaildomains-api/) — The domains an account sends its emails from, addressed by `/v1/accounts/{account_id}/email-domains`. The account in the path is the only source of context,…
- [beel-es Account Emails API](https://apis.io/apis/beel-es/beel-es-accountemails-api/) — The sent-email history of an account, addressed by `/v1/accounts/{account_id}/emails` and `/v1/accounts/{account_id}/email-indicators`. The account in the…
- [beel-es Account Imports API](https://apis.io/apis/beel-es/beel-es-accountimports-api/) — Onboarding managed accounts in bulk from a file, addressed by `/v1/accounts/imports`. The file is declarative and the import is re-runnable: each pass…
- [beel-es Account Request Logs API](https://apis.io/apis/beel-es/beel-es-accountrequestlogs-api/) — Canonical form of the request logs, addressed by `/v1/accounts/{account_id}/request-logs`. The account in the path authorizes the call; the logs returned…
- [beel-es Accounts API](https://apis.io/apis/beel-es/beel-es-accounts-api/) — Account provisioning for partners managing multiple accounts and NIFs. The whole onboarding flow — provisioning, claim tokens and usage — works with either…
- [beel-es Account Webhooks API](https://apis.io/apis/beel-es/beel-es-accountwebhooks-api/) — Outbound webhook subscriptions as a sub-resource of the account itself, addressed by `/v1/accounts/{account_id}/webhooks`. The account in the path is the…
- [beel-es Company API](https://apis.io/apis/beel-es/beel-es-company-api/) — The company as a resource of its own, addressed by `/v1/companies/{company_id}`. The NIF in the path is the only source of context: the account that owns it…
- [beel-es Company Activations API](https://apis.io/apis/beel-es/beel-es-companyactivations-api/) — Switching a company on or off in Test or Live, as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/activations`. The NIF in…
- [beel-es Company Branding API](https://apis.io/apis/beel-es/beel-es-companybranding-api/) — The invoice branding of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/logo` and…
- [beel-es Company Customer Imports API](https://apis.io/apis/beel-es/beel-es-companycustomerimports-api/) — Importing customers into a company, addressed by `/v1/companies/{company_id}/customers/imports`. The origin of the file travels in the body as `source`, so…
- [beel-es Company Customers API](https://apis.io/apis/beel-es/beel-es-companycustomers-api/) — The customers of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/customers`. The NIF in the path is the only…
- [beel-es Company Custom Fields API](https://apis.io/apis/beel-es/beel-es-companycustomfields-api/) — The invoice custom fields of a company, addressed by `/v1/companies/{company_id}/custom-fields`: labels a company adds to its invoices, such as a store, a…
- [beel-es Company Email Configuration API](https://apis.io/apis/beel-es/beel-es-companyemailconfiguration-api/) — The email configuration of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/email-configuration`. It sets the…
- [beel-es Company Fiscal Summary API](https://apis.io/apis/beel-es/beel-es-companyfiscalsummary-api/) — The fiscal summary of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/fiscal-summary`. The NIF in the path is…
- [beel-es Company Invoice Delivery API](https://apis.io/apis/beel-es/beel-es-companyinvoicedelivery-api/) — Delivery, bulk operations and exports of a NIF's invoices (send, deliveries, batches, exports, PDF archive), under…
- [beel-es Company Invoice Lifecycle API](https://apis.io/apis/beel-es/beel-es-companyinvoicelifecycle-api/) — State transitions and scheduling of a NIF's invoices (issue, void, corrective, status, schedule), under…
- [beel-es Company Invoices API](https://apis.io/apis/beel-es/beel-es-companyinvoices-api/) — The invoices of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/invoices`. The NIF in the path is the only…
- [beel-es Company Payment Connections API](https://apis.io/apis/beel-es/beel-es-companypaymentconnections-api/) — The payment provider connections of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/payment-connections`. The…
- [beel-es Company Payment Events API](https://apis.io/apis/beel-es/beel-es-companypaymentevents-api/) — The payment events of a company connection, addressed by `/v1/companies/{company_id}/payment-connections/{connection_id}/events`. The NIF in the path is the…
- [beel-es Company Products API](https://apis.io/apis/beel-es/beel-es-companyproducts-api/) — The product/service catalog of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/products`. The NIF in the path is…
- [beel-es Company Proforma API](https://apis.io/apis/beel-es/beel-es-companyproforma-api/) — Converting a NIF's proforma into a fiscal invoice (`POST /v1/companies/{company_id}/invoices/{invoice_id}/convert-to-invoice`). The rest of the proforma…
- [beel-es Company Recurring Invoices API](https://apis.io/apis/beel-es/beel-es-companyrecurringinvoices-api/) — The recurring invoice templates of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/recurring-invoices`. The NIF…
- [beel-es Company Representation API](https://apis.io/apis/beel-es/beel-es-companyrepresentation-api/) — The AEAT fiscal representation of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/representation`. The NIF in…
- [beel-es Company Series API](https://apis.io/apis/beel-es/beel-es-companyseries-api/) — The invoice series of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/series`. The NIF in the path is the only…
- [beel-es Company Tax Configuration API](https://apis.io/apis/beel-es/beel-es-companytaxconfiguration-api/) — The tax configuration of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/tax-configuration`. The NIF in the path…
- [beel-es Company Veri Factu Configuration API](https://apis.io/apis/beel-es/beel-es-companyverifactuconfiguration-api/) — The VeriFactu configuration of a company as a sub-resource of the company itself, addressed by `/v1/companies/{company_id}/verifactu-configuration`. The NIF…
- [beel-es Configuration Preferences API](https://apis.io/apis/beel-es/beel-es-configurationpreferences-api/) — User language preferences
- [beel-es Configuration Tax API](https://apis.io/apis/beel-es/beel-es-configurationtax-api/) — Tax configuration and tax type catalogs
- [beel-es Configuration Veri Factu API](https://apis.io/apis/beel-es/beel-es-configurationverifactu-api/) — VeriFactu compliance configuration
- [beel-es Customer Import API](https://apis.io/apis/beel-es/beel-es-customer-import-api/) — Bulk creation, CSV import, and Holded import operations
- [beel-es Customer Templates API](https://apis.io/apis/beel-es/beel-es-customer-templates-api/) — Templates and sample files for customer imports
- [beel-es Customers API](https://apis.io/apis/beel-es/beel-es-customers-api/) — Customer management
- [beel-es Emails API](https://apis.io/apis/beel-es/beel-es-emails-api/) — History of emails the system has sent on your behalf (invoices, verification, onboarding, etc.). Read-only.
- [beel-es Email Template Variables API](https://apis.io/apis/beel-es/beel-es-emailtemplatevariables-api/) — The variables the email templates accept, addressed by `/v1/email-template-variables`. The catalogue is the same for every credential and takes no identifier.
- [beel-es Identity API](https://apis.io/apis/beel-es/beel-es-identity-api/) — Who am I (`GET /v1/me`): the authenticated principal — credential type, environment it operates on and the permissions it holds — so a client can adapt what…
- [beel-es Invitations API](https://apis.io/apis/beel-es/beel-es-invitations-api/) — Member invitations — invite people to the account and revoke pending invites (multi-NIF). Like members, invitations are **shared between Test and Live**:…
- [beel-es Invoice Customization API](https://apis.io/apis/beel-es/beel-es-invoicecustomization-api/) — The PDF templates a NIF can be rendered with, each one with a readable, translated name. The same for every account.
- [beel-es Invoice Delivery API](https://apis.io/apis/beel-es/beel-es-invoicedelivery-api/) — Invoice delivery, bulk operations and exports
- [beel-es Invoice Lifecycle API](https://apis.io/apis/beel-es/beel-es-invoicelifecycle-api/) — Invoice state transitions and scheduling
- [beel-es Invoices API](https://apis.io/apis/beel-es/beel-es-invoices-api/) — Invoice CRUD operations
- [beel-es Invoice Series API](https://apis.io/apis/beel-es/beel-es-invoiceseries-api/) — Invoice series management
- [beel-es Me API](https://apis.io/apis/beel-es/beel-es-me-api/) — Preferences of the authenticated principal (`PATCH /v1/me`), such as the language BeeL uses to talk to the account.
- [beel-es Members API](https://apis.io/apis/beel-es/beel-es-members-api/) — Account member management (multi-NIF). Members and their company grants are **shared between Test and Live**: a collaborator is the same person, with the…
- [beel-es NIF API](https://apis.io/apis/beel-es/beel-es-nif-api/) — Tax ID validation against AEAT tax registry
- [beel-es Products API](https://apis.io/apis/beel-es/beel-es-products-api/) — Product and service catalog management
- [beel-es Proforma API](https://apis.io/apis/beel-es/beel-es-proforma-api/) — A proforma is a non-fiscal commercial document, a formal quote you send a customer before invoicing. It lives on the same `/invoices` resource as any other…
- [beel-es Provisioning API](https://apis.io/apis/beel-es/beel-es-provisioning-api/) — Lifecycle view for accounts you provisioned: track their activation state and manage the access level you hold over them.
- [beel-es Public Company Representations API](https://apis.io/apis/beel-es/beel-es-publiccompanyrepresentations-api/) — **Deprecated.** VeriFactu representation flow for digital signature and AEAT registration, in its account-nested form. Use `CompanyRepresentation`…
- [beel-es Recurring Invoices API](https://apis.io/apis/beel-es/beel-es-recurringinvoices-api/) — Recurring invoice template management and automated invoice generation. Create templates that automatically generate invoices on a schedule. Supports…
- [beel-es Request Logs API](https://apis.io/apis/beel-es/beel-es-requestlogs-api/) — Read-only access to the API request logs generated by your own API keys (live + test). Inspect method, path, status, timing, and full request/response…
- [beel-es Tax Types API](https://apis.io/apis/beel-es/beel-es-taxtypes-api/) — The tax regimes, percentages, withholdings and exemption reasons BeeL accepts. The same for every credential, and readable before the first NIF exists.
- [beel-es Templates API](https://apis.io/apis/beel-es/beel-es-templates-api/) — Downloadable file templates. They are fixed files, the same for every credential, and belong to no account and no NIF.
- [beel-es Webhooks API](https://apis.io/apis/beel-es/beel-es-webhooks-api/) — Outbound webhook subscriptions for real-time event notifications. Register HTTPS endpoints to receive event payloads when key actions occur (e.g. VeriFactu…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Beel Es Webhooks](https://apis.io/asyncapis/beel-es/beel-es-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Beel Es Agentic Access](https://apis.io/agentic-access/beel-es/beel-es-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CreateCorrectiveInvoiceRequest](https://apis.io/schemas/beel-es/beel-es-create-corrective-invoice-request/)
- [CreateInvoiceRequest](https://apis.io/schemas/beel-es/beel-es-create-invoice-request/)
- [PatchRecurringInvoiceRequest](https://apis.io/schemas/beel-es/beel-es-patch-recurring-invoice-request/)
- [RecurringInvoiceResponse](https://apis.io/schemas/beel-es/beel-es-recurring-invoice-response/)
- [UpdateInvoiceRequest](https://apis.io/schemas/beel-es/beel-es-update-invoice-request/)
- [UpdateRecurringInvoiceRequest](https://apis.io/schemas/beel-es/beel-es-update-recurring-invoice-request/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Beel Es Context](https://apis.io/jsonld/beel-es/beel-es-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [beel-es API Rules](https://apis.io/rules/beel-es/beel-es-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Beel Es Authentication](https://apis.io/security/beel-es/beel-es-authentication/)
- [Beel Es Domain Security](https://apis.io/security/beel-es/beel-es-domain-security/)
- [Beel Es Vulnerability Disclosure](https://apis.io/security/beel-es/beel-es-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Beel Es Scopes](https://apis.io/scopes/beel-es/beel-es-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Beel Es Plans Pricing](https://apis.io/plans/beel-es/beel-es-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://beel.es/)
- [Documentation](https://docs.beel.es/)
- [API reference](https://docs.beel.es/invoices/createCompanyInvoice)
- [Pricing](https://beel.es/precios)
- [Support](https://beel.es/contacto)
- [Changelog](https://docs.beel.es/changelog)
- [Blog](https://beel.es/blog)

## API Evangelist rating

**Kin Score 62.4** — strong · rubric 0.25.0 · scored 2026-10-30

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 71.0 |
| Contract governance | 79.1 |
| Operational transparency | 42.1 |
| Developer ergonomics | 63.6 |
| Access clarity | 38.9 |

**Agent readiness 82.5** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | yes |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 32.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/beel-es/](https://apis.io/providers/beel-es/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for beel-es: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/beel-es/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
