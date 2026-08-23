# Security Policy

## Project status

This is a legacy and unsupported userscript. It modifies page-level network APIs and should not be assumed compatible with current ChatGPT behavior.

## Reporting a vulnerability

Do not publish exploit details, cookies, authorization headers, conversation content, account identifiers, or screenshots containing personal data in a public issue or pull request.

Use this repository's private vulnerability reporting page:

https://github.com/Fiskers/ChatGPT-DeMod/security/advisories/new

Include the affected commit, userscript manager and version, browser, reproduction steps, impact, and a minimal proof of concept with all sensitive data removed.

## Installation risks

Before installing any userscript:

- inspect the complete source and metadata;
- verify `@match`, `@include`, `@require`, `@resource`, `@connect`, `@downloadURL`, and `@updateURL`;
- disable automatic updates when you need to preserve reviewed fork code;
- avoid using sensitive accounts or conversations;
- remove the script immediately if unexpected network or page behavior occurs.

## Supported versions

No version is currently supported for production or security-sensitive use.
