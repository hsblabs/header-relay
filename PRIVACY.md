# Header Relay Privacy Policy

Last updated: 2026-07-10

## Purpose

Header Relay is a Chrome extension for API development and testing. It helps developers check how browser-based HTTP requests behave when fixed or captured headers are attached.

## Host Permissions

The extension requests `<all_urls>` host permission so developers can choose any local, staging, internal, or test origin as a target. Header capture and attachment are limited by the enabled profile's Target Origins and Excluded Paths.

## Data Stored Locally

Profiles, captured header values, session state, and audit logs are stored locally in the browser extension storage and IndexedDB areas for this extension. Captured header values are shown in plain text in the popup and management UI so developers can verify the actual values used on requests.

## Limited Use Disclosure

Header Relay uses browser permissions and locally stored data only to provide and improve its single purpose: capturing configured HTTP response header values and relaying configured request headers for developer-selected target origins. The extension does not use this data for advertising, creditworthiness, lending, or unrelated purposes.

## Data Sharing

The extension does not transmit profile settings, captured headers, audit logs, or browsing data to external servers. Network requests are only the pages and APIs you open in the browser while using your configured profiles.

## No Human Access

The developer does not receive, inspect, sell, or share your profile settings, captured header values, audit logs, or browsing activity. All such data remains in the local Chrome profile unless you choose to export or disclose it yourself.

## Audit Log Retention

Audit logs are capped at the 1000 most recent entries and entries older than 7 days are removed automatically. Logged URLs are stored as origin and pathname only; query strings and fragments are dropped so tokens in URLs are not retained. You can remove all audit logs at any time with Clear logs in the Audit Logs section of the management screen.

## User Control

You can disable a profile, remove target origins, clear captured values, or uninstall the extension to stop capture and attachment behavior.
