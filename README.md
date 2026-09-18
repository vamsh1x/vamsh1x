# Hi there, I'm Vamshi Angothu 👋

Site Reliability Engineer working in the identity space — currently at **TCS** on contract with **Humana**. I live in the world of **ForgeRock / Ping Identity**: PingAM, PingIDM, PingDS, and PingGateway, keeping production identity systems healthy.

## What I do
- Production troubleshooting for identity management: reconciliation failures, sync drift, orphaned links, correlation conflicts (`FOUND_ALREADY_LINKED` and friends)
- Data-driven root cause analysis — I read the audit/recon data and find out what actually broke
- Controlled bulk remediation with dry runs and rollback records, never cowboy scripts on prod
- Python tooling around IDM REST APIs: paged queries, retry/backoff, rate limiting

## Python + data analysis

Python is my main tool. I do data analysis in Jupyter notebooks:

- Import IDM/ForgeRock data into notebooks and run identity resolution — finding duplicate and fake profiles
- Pull millions of records from the IDM database with GET calls based on a CSV input and required fields, using concurrent threads, then analyze the data
- Pull Splunk data into Jupyter using the Splunk Python SDK for log and event analysis
- Pull Twilio data and analyze it — OTP send costs, and finding bugs in ForgeRock AM authentication trees that cause huge OTP sends
- Root cause analysis is my specialty: read the data, find what actually broke

## Featured project
**[forgerock-data-toolkit](https://github.com/vamsh1x/forgerock-data-toolkit)** — a production data-remediation toolkit for PingIDM / ForgeRock IDM. Finds the data problems that break reconciliations (duplicate correlation values, orphaned links, sync drift), explains the likely root cause, and applies fixes safely with dry-run-by-default execution and a rollback journal.

## Toolbox
Python · REST APIs · ForgeRock / Ping Identity (AM, IDM, DS, IG) · OAuth2 / OIDC / SAML · Linux · Jupyter · pandas · Splunk SDK · Twilio APIs · troubleshooting production systems

---

📍 Louisville, KY · 🏢 TCS (Humana)

If you run Ping Identity or ForgeRock in production and your reconciliations are misbehaving, my toolkit repo is a good place to start.
