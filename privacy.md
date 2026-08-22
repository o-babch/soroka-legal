---
title: Soroka Privacy Policy
permalink: /privacy/
---

# Soroka Privacy Policy

_Effective 2026-08-08. Published at
<https://o-babch.github.io/soroka-legal/privacy/> (this file is the source; the
page is regenerated from it)._

Soroka is an expense tracker for households, published by Oleksii Babchenko
(sole developer, Spain). This policy says what data Soroka handles, where it
lives, and what you can do about it. The short version: your receipts and
expenses are yours, they stay in the EU, nothing is sold, and there is no
advertising.

## What Soroka collects

**Account.** When you sign in with Google or Apple, Soroka receives a stable
account identifier, your display name, and your email address. With Apple you
can hide your email; Soroka works the same either way and never uses the email
for anything except showing you which account you are signed in with. No
password is ever created or stored.

**Your household's data.** Expenses you enter or photograph: amounts, dates,
merchant names, item lines, categories, notes, the receipt image itself, and
your shopping list. This is the product - Soroka stores it so you and the
household members you invite can see it.

**Receipt images and AI reading.** When you photograph or share a receipt,
the image is reduced in size, stripped of camera metadata (including location),
and sent for automated reading by Google's Gemini model in an EU region, under
an agreement that does not allow Google to train on it. The image stays stored
with the expense so you can always check the original.

**Crash reports.** If the app crashes, a technical report (stack trace, device
model, OS version) goes to Sentry, hosted in the EU. Crash reports do not
contain your expenses or receipts.

**What Soroka does not collect.** No bank connection exists, by design - Soroka
never asks for bank credentials and never sees your accounts. No advertising
identifiers, no analytics profiles, no location, no contacts.

## Where it lives

All servers and storage are in the European Union: the API and database in
AWS eu-central-1 (Frankfurt), receipt images in Cloudflare R2 (EU jurisdiction),
AI processing in Google Cloud's EU region, crash reports in Sentry's EU region.

## Who can see what

Members of your household see the household's shared expenses and the shopping
list. An expense you mark as personal ("only me") is visible only to you - it
is filtered on the server, not just hidden in the app.

Nobody else sees your data. It is not sold, not shared for advertising, and not
used to train AI models. The service providers named above process it only to
run Soroka.

## Your rights

Both live in the app, under Settings:

- **Export**: one file with your profile and everything you can see in your
  household, plus links to your receipt images.
- **Delete account**: erases your sign-in, name, and email permanently. Shared
  expenses stay with the household (deleting them would rewrite your partner's
  books); they are shown as belonging to a former member. If you are the last
  member, the household and all its receipts are deleted outright.

If you cannot use the app, you can also **request account deletion by email**
at the contact below; deletion requests are honored the same way and confirmed
back to you.

You can also ask anything about your data at the contact below - GDPR gives you
the rights of access, rectification, erasure, restriction, portability, and
objection, and the right to complain to a supervisory authority (in Spain, the
AEPD).

## Retention

Data is kept while your account exists. Deleting your account removes your
identity immediately and permanently; a household's data lives as long as the
household has members.

**Receipt images** are kept for three years from the expense date - the length
of the EU legal guarantee period - and then removed automatically, unless you
marked the receipt as kept ("Keep this receipt" in the app), in which case it
stays as long as the household does. The expense itself, its amounts and items
are never removed by this; only the image expires. The app states this policy
in Settings and shows a receipt's removal date before it happens.

**Cases you send for review**: when an AI reading fails, you can choose to send
that one receipt (its image or pasted text) and the failed result to the
developer to improve recognition. This happens only after you confirm a dialog
that says so. A case kept as test data is stored outside your household's
storage and is therefore not removed by account deletion - the dialog says
this too. To have a sent case removed, email the address below with the
approximate date.

## Children

Soroka is not directed at children under 16 and does not knowingly collect
their data.

## Changes

If this policy changes in a way that matters, the app will say so before the
change applies.

## Contact

Oleksii Babchenko - <alekseykpi@gmail.com>.
