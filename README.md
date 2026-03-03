# OfficeX

Official Claude Code skill for the [OfficeX](https://officex.app) platform REST API.

## What is OfficeX?

OfficeX is a membership-based app store — "Netflix meets Costco for business apps". Users buy credits ($0.03 each), apps charge credits via reserve/settle, and vendors earn payouts at $0.01/credit.

## Using the Skill

Install the skill in Claude Code:

```bash
claude install-skill OfficeXApp/officex
```

The skill activates automatically when you work with the OfficeX API — making HTTP calls, building apps, implementing billing, managing users/installs/wallets, handling webhooks, or embedding apps in iframes.

## What's Included

- **SKILL.md** — Complete API reference covering all OfficeX REST endpoints, authentication, credit billing (reserve/sip/settle), webhook events, iframe embedding, agent context integration, referral links, and billing patterns with code examples.

## Environments

| Env | API Base |
|---|---|
| **Staging** | `https://staging-backend.cloud.officex.app/v1` |
| **Production** | `https://cloud.officex.app/v1` |

## Links

- **App Store:** https://officex.app
- **Developer Portal:** https://officex.app/store/en/developer/
- **GitHub:** https://github.com/OfficeXApp
