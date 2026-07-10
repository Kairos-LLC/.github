> **⚠️ DRAFT — AI-GENERATED TEMPLATE — NOT LEGAL ADVICE ⚠️**
>
> This document was drafted by an AI assistant as a starting-point template. It has **not** been
> reviewed by a licensed attorney and **must not** be published, relied upon, or treated as
> legally binding in its current form. Kairos LLC must have this document reviewed and approved
> by qualified legal counsel before it is used in production, presented to users, or referenced
> in any binding agreement. Sections marked `[TBD — confirm with counsel]` or similar contain
> placeholders that require input from the business owner and/or an attorney before publication.

# Kairos Privacy Policy

**Last updated:** [Date — TBD, set upon legal review]

**Effective date:** [Date — TBD, set upon publication]

## 1. Introduction

Kairos LLC ("Kairos," "we," "us," or "our") provides a scheduling application built around a
simple principle: your schedule is your business. Kairos ("the App") is designed so that we —
the operators of the service — hold as little identifying information about you as possible.
This Privacy Policy explains what data the App collects, why, how long it is kept, and what
rights you have over it.

This policy applies to the Kairos mobile and web applications and any associated backend
services (collectively, the "Service"). It does not apply to third-party websites or services
that may be linked from within the Service.

If you do not agree with this Privacy Policy, please do not use the Service.

This Privacy Policy should be read together with the
[Kairos Terms of Service](./terms-of-service.md), which govern your use of the Service more
generally.

## 2. No Traditional Accounts

Kairos does not use traditional user accounts. Specifically:

- We do **not** ask for or require an email address to use the Service.
- We do **not** ask for or require a password.
- We do **not** operate a sign-up flow that collects your name, phone number, or other
  identifying contact information as a condition of using the Service.

Instead, Kairos uses a **recovery key** model, described below.

## 3. How Recovery Keys Work (and What That Means for Your Privacy)

When you first set up Kairos, the App generates a recovery key on your device. The recovery key
is a credential that you — not Kairos — hold and control. It is generated and encrypted locally
on your device and is used to identify and restore your schedule data, in place of a
username/password pair tied to your personal identity.

From a privacy standpoint, this means:

- Kairos does not require you to link the recovery key to your real-world identity (e.g., your
  legal name or email address) in order to use the Service.
- Because we do not collect identifying account information at signup, we have materially less
  personal data to lose, misuse, or be compelled to disclose than a typical account-based
  service.
- **You are responsible for safeguarding your recovery key.** Because Kairos does not maintain a
  traditional account-recovery process (e.g., "forgot password" tied to an email inbox we
  control), losing your recovery key may mean losing access to your schedule data. We do not
  store a copy of your recovery key in a form that would let us recover it on your behalf.
- Kairos stores only what is technically necessary to associate encrypted schedule data with
  your recovery key on our servers — we do not attach a name, email, or other direct identifier
  to that record unless you voluntarily provide one (for example, in optional profile fields, if
  offered by the App).

## 4. How Access Codes Work (and What That Means for Your Privacy)

Kairos allows you to share a view of your schedule with another person — for example, a
manager, coworker, or family member — using a **one-time, single-use, 6-character access code**.

- An access code grants **temporary, scoped access** to a specific shared schedule. It is not a
  persistent login and does not grant broader access to your account or other data.
- Access codes are single-use: once redeemed, a given code cannot be reused to gain repeated or
  ongoing access.
- We log the minimum information necessary to issue, validate, and expire access codes (such as
  the code's creation time, expiration, and redemption status). We do not use access codes to
  build advertising profiles or to track recipients across other services.
- Anyone who redeems your access code will be able to view the specific scheduling information
  the code was scoped to grant. Only share access codes with people you intend to have that
  access.

## 5. What Data We Collect

Kairos is built to collect the minimum data needed to provide scheduling functionality. The
categories of data we store are:

- **Schedule data**, including:
  - Schedule patterns and recurring shift cycles
  - Overrides to the regular schedule (e.g., `vacation`, `extra_shift`, `on_call`)
  - Job role (e.g., a label describing the position or function associated with a schedule)
- **Recovery-key-linked identifiers**: a technical identifier associated with your recovery key,
  used to locate and sync your encrypted schedule data. This identifier is not, by itself, tied
  to your real-world identity.
- **Access-code metadata**: creation time, expiration, scope, and redemption status of access
  codes you generate, as described in Section 4.
- **Basic technical/operational data** reasonably necessary to operate the Service (e.g., error
  logs, crash reports, or similar diagnostic data), to the extent generated by standard app and
  server operation.

### What we do **not** collect

Kairos does not collect the following, and this policy will be updated if that ever changes:

- We do not collect your precise or approximate **location**.
- We do not access your device **contacts**.
- We do not require an **email address, phone number, or password** to use the Service.
- We do not collect **special-category personal data** (such as health, biometric, racial or
  ethnic origin, religious belief, or similar sensitive categories) beyond what a user might
  voluntarily and incidentally include in a free-text field they control (e.g., a shift label),
  which we do not review, analyze, or use for any purpose beyond displaying it back to the user
  and authorized access-code recipients.

## 6. How We Use Data

We use the data described in Section 5 solely to:

- Provide, operate, and maintain the scheduling functionality of the Service;
- Sync your schedule data across your own devices via your recovery key;
- Enable schedule sharing via access codes, as scoped and time-limited by you;
- Diagnose and fix technical problems with the Service;
- Comply with legal obligations, where applicable.

We do not use your schedule data to build advertising profiles, and we do not use it for any
purpose unrelated to providing the Service.

## 7. No Sale of Data; No Third-Party Data Sharing for Marketing

Kairos does not sell your personal data or schedule data to third parties. We do not share your
data with third parties for their own marketing or advertising purposes.

We may share data with service providers who help us operate the Service (for example, cloud
hosting or infrastructure providers) solely to the extent necessary to provide the Service, and
subject to obligations that limit their use of that data to providing services to us.

We may disclose data if required to do so by law, subpoena, or other legal process, or if we
believe in good faith that disclosure is necessary to protect the rights, property, or safety of
Kairos, our users, or the public, consistent with applicable law.

## 8. Data Retention

- **Schedule data** tied to a recovery key is retained for as long as the recovery key remains
  in use, or until you delete it as described in Section 9.
- **Access codes** are retained only as long as necessary to serve their one-time, scoped
  purpose, plus a limited period for abuse-prevention and diagnostic logging, after which
  redeemed or expired codes are deleted or anonymized.
- Because we do not hold a recoverable copy of your recovery key, data associated with a lost
  recovery key that goes unused for an extended period may be deleted as part of routine data
  hygiene. [Specific retention windows — TBD, confirm with counsel and engineering before
  publication.]

## 9. Your Rights and Deletion

You have the right to:

- **Delete your data.** Because your identity in Kairos is tied to your recovery key rather than
  a centrally managed account, deleting your recovery key and requesting deletion (see contact
  information below) removes the associated schedule data from our systems, subject to limited
  backup/legal retention windows described in Section 8.
- **Access your data.** You can view your own schedule data directly within the App at any time.
- **Request a copy or deletion of data** associated with your recovery key by contacting us using
  the information in Section 12. Because we do not collect identifying contact information by
  default, you may need to demonstrate control of the relevant recovery key to complete a
  deletion request.

Depending on your jurisdiction, you may have additional rights under applicable data protection
law (such as the right to restrict or object to certain processing). [Jurisdiction-specific
rights language — TBD, confirm with counsel, e.g., for GDPR/CCPA applicability.]

## 10. Data Security

We use reasonable technical and organizational measures designed to protect your data, including
encryption of recovery-key-derived credentials and schedule data as described above. However, no
method of transmission or storage is completely secure, and we cannot guarantee absolute
security.

## 11. Children's Privacy

The Service is not directed to children under the age of 13 (or the minimum age required by
applicable local law), and we do not knowingly collect data from children under that age. [Age
threshold and COPPA/equivalent analysis — TBD, confirm with counsel.]

## 12. Changes to This Policy

We may update this Privacy Policy from time to time. If we make material changes, we will take
reasonable steps to notify users (for example, via an in-app notice) before the changes take
effect.

## 13. Contact Us

For privacy-related questions, requests, or to exercise the rights described in Section 9,
please contact:

**[privacy@kairos.app — TBD]**

[Mailing address and/or other contact details — TBD, confirm with counsel/business owner before
publication.]

---

*This Privacy Policy is a draft template pending attorney review. Do not rely on it as final or
legally binding until it has been reviewed and approved by qualified legal counsel.*
