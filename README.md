# SafeRelease

**SafeRelease** is an independent concept prototype for safer, more accountable student dismissal at schools.

Live demo: https://backtakg.github.io/SafeRelease/

## What is included

- Student directory with sample records
- Authorised guardian records and verification status
- Pickup pass creation with a six-digit demo code and QR preview
- Staff-side pickup code verification
- Explicit identity-check confirmation before recording a handover
- Single-use pass behaviour in the browser demo
- Pickup-change request review
- Timestamped handover history and CSV export
- School workflow settings
- Responsive desktop and mobile layouts

## Run locally

Open `index.html` in a modern browser. No build step or backend is required.

The demo uses browser local storage. Sample records are fictional and are restored with **Settings → Reset demo data**.

## Important: demo only

This repository is not affiliated with any school or school ERP provider. It is not connected to a live student database, SMS provider, identity provider, school ERP, or production authentication service. Do not enter real student or guardian information.

A production system would require, at minimum:

- Authenticated staff accounts and role-based permissions
- Server-side, cryptographically secure, expiring and single-use pickup tokens
- Server-side validation and tamper-resistant audit logs
- Verified guardian identity and school-approved authorisation workflows
- Secure backend storage, encryption, backups and retention controls
- Consent, privacy, safeguarding and incident-response procedures
- Integration with the school's existing student information system

The QR library is loaded from a public CDN; the six-digit code remains usable if QR rendering is unavailable.

## Product concept

Inspired by international school-dismissal and student-safety workflows, SafeRelease explores an add-on module for school ERP platforms. It is a proposal for discussion and validation, not a claim that a particular provider lacks these capabilities.
