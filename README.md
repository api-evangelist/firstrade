# Firstrade

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

Firstrade Securities is a commission-free online brokerage offering trading in stocks, ETFs, options, mutual funds, and fixed income securities with no account minimums and no inactivity fees. Founded to serve self-directed investors, Firstrade provides $0 commissions across all major asset classes including options (with $0 contract fees).

## API Access

Firstrade does not publish an official public REST API. Programmatic account access is available through the **Plaid** financial data aggregation platform, which supports:

- **Assets** — Consolidated account balance summaries and asset reports (JSON and PDF)
- **Balance** — Current and available account balances
- **Transactions** — Up to 24 months of transaction history
- **Investments** — Retirement, brokerage, and crypto holdings

Developers integrate via [Plaid's API](https://plaid.com/institutions/firstrade/) using Plaid Link for customer consent-based authentication.

## Trading Products

- Stocks (NYSE, AMEX, Nasdaq, OTC)
- ETFs (2,200+ available)
- Options (OptionsWizard analytics tool included)
- Mutual Funds (11,000+ available)
- Fixed Income (Treasury bonds, municipal bonds, CDs, agency bonds)

## Account Types

Individual, Joint (WROS and Tenants in Common), Custodial (UTMA/UGMA), Trust, Traditional IRA, Roth IRA, Rollover IRA, SEP IRA, SIMPLE IRA, Coverdell ESA, and margin accounts.

## Pricing

- $0 commissions on stocks, ETFs, options, and most mutual funds
- $0 options contract fees
- No account minimums
- No inactivity fees
- SEC transaction fee: $20.60 per million dollars on eligible sell transactions
- Options Regulatory Fee: $0.02375 per contract

## Links

- [Website](https://www.firstrade.com/)
- [Trading Products](https://www.firstrade.com/trading)
- [Pricing](https://www.firstrade.com/trading/pricing)
- [Help Center](https://help.firstrade.com/)
- [Plaid Integration](https://plaid.com/institutions/firstrade/)
- [Open Banking Tracker](https://www.openbankingtracker.com/provider/firstrade)
