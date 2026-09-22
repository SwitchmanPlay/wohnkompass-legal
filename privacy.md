---
layout: default
title: Privacy policy
permalink: /privacy/
---

# Privacy Policy

Last updated: 22 September 2026

This policy explains how the Telegram bot **WohnKompass** ("we", "the bot")
processes personal data under the EU General Data Protection Regulation
(GDPR) and the Austrian Data Protection Act (DSG).

## 1. Controller

Danylo Prokhorenko, Brigittenauer Laende 224-228, 1200 Vienna, Austria
Email: adamsmith6787@gmail.com · in the bot: `/support`

We have not appointed a data protection officer.

## 2. What data we process

**Telegram account data** (when you start the bot): Telegram user ID and
chat ID, username, first name, the language you choose, time of registration
and last activity.

**Account and subscription data:** tier (Free / Premium / Premium Buy),
paid-until date and how it was obtained (purchase, trial, promo code,
referral, admin grant), trial flag, applied discount or promo code, promo
code redemptions, who referred you and whom you referred, where you came
from (start-link parameter), whether you joined our channel (if the bot
requires this, Telegram tells us your membership status), reminder and
nudge flags, digest preferences (e.g. night digests), block status.

**Saved searches ("watches"):** name, rent or buy, property types, city,
districts/postcodes, price and size range, rooms, furnished, move-in date,
alert threshold, pause/mute state and your **free-text wishes**.

**Applicant profile (optional, Premium):** name, age, occupation, income
band, smoker (yes/no), pets, guarantor (yes/no), move-in date and a short
self-description. Please do not enter sensitive data (health, religion,
ethnic origin etc.) in free-text fields.

**Matches and AI results:** which listings matched which search, AI fit
score, short reasoning, red-flag warnings, delivery status; AI-drafted
application messages you requested (cached per listing).

**Payment data:** for Telegram Stars: Telegram's charge ID, amount in Stars,
purchased product, time. For crypto (Heleket): order ID, invoice ID, amount,
currency, number of days, status, payment link, creation and payment time.
We never receive card, bank or wallet credentials.

**Support messages:** text and photos you send via `/support`, our reply,
timestamps, your username.

**Usage events:** which rate-limited action you used and when (for quotas
and abuse protection).

**Technical logs:** server logs with timestamps, user IDs and error details.

**Listing data from third parties:** the bot reads public listing pages of
real-estate portals (willhaben.at, immobilienscout24.at, immowelt.at,
immobilien.derstandard.at, wg-gesucht.de) and stores title, description,
price, size, location hint, photo URLs and link. Listings may contain
personal data of advertisers (e.g. an agent's name). See section 5.

## 3. Purposes and legal bases

| Purpose | Legal basis |
|---|---|
| Running the bot: saving searches, matching, sending alerts and digests, AI scores and drafts you request, applicant profile | Art. 6(1)(b) GDPR (contract) |
| Selling and managing subscriptions, promo codes, referrals, trials | Art. 6(1)(b) GDPR |
| Keeping payment records for tax and accounting | Art. 6(1)(c) GDPR with § 132 BAO, § 212 UGB |
| Support requests | Art. 6(1)(b) GDPR; otherwise Art. 6(1)(f) |
| Abuse prevention, rate limits, security, error logs, backups | Art. 6(1)(f) GDPR (legitimate interest in a secure, stable service) |
| Aggregated market statistics (e.g. median rent per district) | Art. 6(1)(f) GDPR; statistics contain no user data |
| Collecting and processing public listings | Art. 6(1)(f) GDPR (interest of home seekers and ours in finding published offers) |
| Optional features you switch on (e.g. applicant profile, channel membership check) | Art. 6(1)(a) GDPR (consent) where required; withdrawable at any time |

You are not obliged to provide data, but without a Telegram account and a
saved search the service cannot work.

## 4. Recipients and processors

- **Telegram** ([TELEGRAM ENTITY - verify in Telegram's current privacy
  policy, e.g. Telegram FZ-LLC, Dubai, UAE]) -
  delivers all messages and processes Telegram Stars payments. Telegram's own
  privacy policy applies: <https://telegram.org/privacy>.
- **Hosting provider:** Hetzner Online GmbH, Industriestr. 25, 91710 Gunzenhausen, Germany, data centre in Helsinki, Finland (EU/EEA) - runs the server,
  database and backups on our behalf (data processing agreement, Art. 28 GDPR).
- **AI model providers** (Premium features only): to compute a fit score,
  red flags or an application draft we send the listing text, listing photo
  URLs, your search criteria and free-text wishes and, for drafts, your
  applicant profile. We do not send your Telegram ID, username or chat
  history. Providers (as of 2026-09-20): OpenRouter, Inc.
  (openrouter.ai, USA) and the OpenAI-compatible model brokers a6api
  (api.a6api.com) and hdd.sb (ai.hdd.sb), which pass the request on to the
  respective model provider (among others xAI, OpenAI, DeepSeek). Ask us by
  e-mail for the current list.
- **Heleket** (Heleket (heleket.com) - currently inactive, no payments are offered) - only if you pay with
  crypto; receives order ID and amount. Transactions on a public blockchain
  are visible to everyone and cannot be deleted by us or Heleket.
- Authorities, courts or tax advisers where required by law.

**Transfers outside the EU/EEA.** Telegram, some AI providers and possibly
Heleket are located outside the EU/EEA (e.g. USA, UAE). Where no adequacy
decision exists (for the USA: only for companies certified under the EU-US
Data Privacy Framework), we rely on the European Commission's Standard
Contractual Clauses (Art. 46(2)(c) GDPR). For the connection to Telegram,
which you use on your own initiative, the transfer is also necessary to
perform the contract (Art. 49(1)(b) GDPR). A copy of the safeguards is
available on request.


## 5. Data about advertisers (Art. 14 GDPR)

Listings are collected only from pages the portals publish openly. We do not
log into portals and do not contact advertisers. Listing data is used to
show the offer to home seekers and, in anonymised form, for price
statistics. Advertisers can object at any time (see section 8); we will then
exclude the listing.

## 6. Retention

| Data | Retention |
|---|---|
| Account, searches, profile, matches, drafts | until you delete them or use `/deleteme`; searches of users inactive for 45 days are paused, accounts inactive for 24 months are deleted |
| Listings pool (and linked matches, AI scores) | 90 days after the listing was last seen |
| Aggregated price statistics | indefinitely (no personal data) |
| Usage events | 7 days |
| Support messages | 12 months after the request is closed |
| Referral and promo redemption records | as long as your account exists |
| Record of free days received, after `/deleteme` (only a pseudonymised hash of your Telegram ID, no other data; only if you received a trial, campaign days or a referral bonus) | 24 months from deletion - prevents the same free days being claimed again by deleting and re-joining (Art. 6(1)(f) GDPR) |
| Payment records (Stars and crypto) | 7 years from the end of the calendar year (§ 132 BAO), even after `/deleteme` |
| Server logs | rotated automatically, at most 30 days |
| Database backups | 30 days, then overwritten |



## 7. AI and automated decisions

The AI fit score, red flags and drafts are **advisory only**. They do not
produce legal effects or similarly significant effects on you (Art. 22 GDPR).
You decide which listings to pursue and whether to send a draft. AI output
can be wrong.

## 8. Your rights

You have the right to access (Art. 15), rectification (Art. 16), erasure
(Art. 17), restriction (Art. 18), data portability (Art. 20) and to
**object** to processing based on legitimate interest (Art. 21). You can
withdraw consent at any time with effect for the future (Art. 7(3)).

- Delete everything at once: send `/deleteme` in the bot. Payment records
  we must keep by law are retained (see section 6).
- Edit or delete searches and your profile directly in the bot.
- For everything else: adamsmith6787@gmail.com or `/support`.

You may lodge a complaint with the Austrian Data Protection Authority
(Datenschutzbehörde), Barichgasse 40-42, 1030 Vienna, <dsb@dsb.gv.at>,
<https://www.dsb.gv.at>, or with the authority in your EU country of
residence.

## 9. Security

Access to the server is restricted to the operator. Connections to Telegram,
portals, AI and payment providers are encrypted (TLS). Bot tokens and API
keys are kept out of the code. Backups are stored [ENCRYPTED / ON THE SAME
SERVER - specify]. No system is completely secure; we will notify you and
the authority of breaches as required by Art. 33-34 GDPR.

## 10. Cookies and tracking

The bot sets no cookies and uses no tracking or advertising tools. Our legal
pages are static pages hosted at GitHub, Inc., 88 Colin P. Kelly Jr. Street, San Francisco, CA 94107, USA (GitHub Pages) - for these legal pages only; the host may
process your IP address in server logs.

## 11. Changes

We may update this policy when the service changes. The date at the top shows
the current version; we will announce material changes in the bot.
