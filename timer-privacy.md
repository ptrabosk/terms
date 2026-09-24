# Offsight Timer Privacy Policy

Effective date: September 24, 2026

Offsight Timer is an internal workforce extension for authorized Attentive personnel. It tracks time spent working a single Zendesk ticket across Zendesk and Attentive, writes calculated Effort to Zendesk, and sends completed timer-session records to an Attentive-controlled operational service.

## Information handled

Offsight Timer handles:

- the primary Chrome profile email, solely to confirm that it belongs to the correct domain;
- the agent's user ID;
- Ticket IDs, company IDs, ticket status, assignment, and availability signals;
- Work URLs associated with a timer session;
- timer start/stop timestamps, work-domain duration, idle duration, prompt decisions, and diagnostic event timing;
- session-scoped context needed to perform Effort writeback.

The extension does not collect a Google password or Google OAuth access token. It does not retain HTTP request or response bodies as timer-session data.

## How information is used

Information is used only to authenticate authorized workforce access, operate and recover the timer, calculate Effort, prevent duplicate session processing, troubleshoot failed operational effects, and maintain internal work records.

## Storage and transmission

Active state and retry information are stored in Chrome extension storage on the user's device. Completed timer sessions are transmitted over HTTPS to the existing Attentive timer API and stored in the associated operational database. Effort is written directly to the system through the authenticated session.

Local and server records are retained according to Attentive's applicable workforce, operational, security, and legal retention requirements. Pending, failed, or ambiguous operations may be retained until they are reconciled. Authorized administrators can coordinate access, correction, or deletion requests under applicable company policy.

## Sharing and prohibited uses

Timer data is not sold, used for advertising, or used for lending or credit decisions. It is not transferred to third parties except where necessary to operate Zendesk and Attentive services, protect security, comply with law, or complete an approved corporate transaction.

Human access is limited to authorized operational, support, security, legal, and compliance purposes under company policy.

## Chrome Web Store Limited Use

The use of information received from Chrome APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements. Information obtained through Chrome permissions is used only to provide or improve the extension's single user-facing purpose.

## Security

Personal and sensitive information is transmitted using HTTPS. Access to operational systems is restricted through company access controls. The extension requests only permissions needed for its timer, recovery, authentication, prompt, and writeback functions.

## Questions and requests

Authorized users should contact their administrator or the applicable internal Privacy, Security, or IT support channel for questions, access requests, corrections, or deletion requests.
