# n8n Google Contacts Backup — client case study

**Project type:** Sanitized client case study
**Evidence source:** completed Upwork contract, client-rated 5.0
**Status:** delivered

Automated, scheduled backup of a client's Google Contacts, built in n8n.

---

## Problem

Google Contacts has no native version history a non-technical owner can rely on.
One bad bulk edit, one bad import, or one sync from a device that had a stale copy,
and the address book a business runs on is changed with no way back. The client
wanted the list captured on a schedule so that a bad day is recoverable.

## Scope delivered

A workflow in n8n that reads the Google Contacts account and writes a backup copy
on a recurring schedule, without the owner having to remember to do it.

## Tools

n8n · Google Contacts · scheduled workflow trigger

## Outcome

Delivered and accepted. The contract closed with a **5.0** client rating on
Upwork, and this project is listed as a Profile Highlight there.

## Implementation notes

Implementation details — the specific node chain, credentials, schedule and
destination — are intentionally omitted because the production workflow belongs
to the client and is private. Nothing about the client's account, data or
credentials appears in this repository.

## Privacy

No client name, no contact records, no OAuth credentials, no workflow export.

## Related

- [contact-dedupe-mcp](https://github.com/skmalikllc/contact-dedupe-mcp) — my open-source tool for the cleanup step that usually follows a contacts export
- [icloud-google-contacts-sync](https://github.com/skmalikllc/icloud-google-contacts-sync)
- [automation-portfolio](https://github.com/skmalikllc/automation-portfolio)
