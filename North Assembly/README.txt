NORTH ASSEMBLY
DOCUMENTATION ROOT

DOCUMENT ID: NA-ROOT
Type: INDEX (unversioned)
Status: ACTIVE
Classification: INTERNAL
Last Modified: October 1, 2026
Governing rule: NA-COR-001 (Document Control)

ABOUT THIS REPOSITORY

This repository is the controlled documentation system for North
Assembly. It contains corporate rules, legal drafts, product
records, operational standards, brand guidance, public material,
internal procedures, decision records, and historical
documentation.

The structure is intentionally numbered. Major areas are stable,
while product directories use a secondary numeric order so the
most important products remain easy to find. Adding or removing a
top-level area requires an ADR (ADR-0004).

DOCUMENT STRUCTURE

01 - CORPORATE
Company structure, responsibilities, document control,
recruitment rules, and decision records.

02 - LEGAL
Terms, privacy, cookies, acceptable use, security, intellectual
property, custom-application, support and commercial policies.
NA-LGL-008 Support Policy and NA-LGL-009 Commercial Terms are
placeholders and define nothing yet.
All legal documents are drafts pending legal review.

03 - PRODUCTS
Project registry (classification, owner, delegation level,
status) plus per-product documentation.
01 - Monix
02 - Telenet
03 - Datalog
04 - DraftPad
05 - CryptCast
06 - NA Command
07 - msg.term
08 - Meat

04 - OPERATIONS
Design, development, infrastructure, QA, security, and release
procedures.

05 - BRAND
North Assembly identity, visual standards, and marketing guidance.

06 - PUBLIC
Announcements, public communication, Discord material, and
website-content standards.

07 - INTERNAL
Internal communications, meetings, and team rules.

08 - ARCHIVE
Superseded, retired, and historical documentation, including the
Weird Stuff era and legacy brand material.

NAVIGATION

Start with this file when you need the repository structure.

Use the README.txt inside each numbered section as the local index
before opening individual documents.

Use DOCUMENT INVENTORY.txt for the complete controlled-document
list, including each document's ID and status.

Use 03 - PRODUCTS/README.txt as the project registry when you need
to know what exists, who owns it, and whether it can be delegated.

Use 01 - CORPORATE/Decisions/ for why a structural, organizational
or product decision was made, and for the Consistency Log that
tracks open contradictions.

For Monix technical material, use:
03 - PRODUCTS/01 - Monix/Documentation/README.txt

DOCUMENT STATUS

A file existing in this repository does not automatically make it
an active policy. The STATUS field in the document header
governs. The vocabulary is defined in NA-COR-001.

[MANDATORY]
Superseded documents must not be presented as current policy.

[MANDATORY]
Public legal documents must not be presented as effective legal
terms until the required identity, jurisdiction, contacts,
effective date, and other applicable details have been completed
and reviewed. Every document in 02 - LEGAL currently carries
STATUS: DRAFT and LEGAL REVIEW: REQUIRED.

[MANDATORY]
RESTRICTED and CONFIDENTIAL material must not be published in
this repository. See ADR-0006.

[MANDATORY]
When a document is moved or renamed, its content and status must
stay intact unless the change is deliberately recorded as a
revision.

BRAND TRANSITION

North Assembly is the current company identity. The previous
identity was Weird Stuff.

[MANDATORY]
Weird Stuff must not be used as the current organizational
identity in any active document.

[MANDATORY]
Historical references to Weird Stuff are preserved where they
document history — in 08 - ARCHIVE, in decision records, and in
documents that explicitly describe the name change. They are not
to be rewritten out of existence.

The previous WS brand asset is retained only under
08 - ARCHIVE/Legacy Brand for historical traceability and is not a
current brand asset.

See ADR-0001.

ORGANIZATION

The current roles, holders and vacancies are recorded in
01 - CORPORATE/Organization.txt (NA-COR-002), including which
positions are intentionally vacant and why.

Recruitment is governed by
01 - CORPORATE/Recruitment and Roles.txt (NA-COR-004).

LEGAL NOTE

Some legal identity and infrastructure details are intentionally
absent because they are private or have not been formally decided
yet. They appear as explicit placeholders and must never be filled
in by assumption.

This repository is a documentation system; it does not, by itself,
make a document legally binding on third parties. Public legal
material must be checked against the actual legal structure and
applicable law before publication.

The repository carries an all-rights-reserved notice (LICENSE at
the repository root): no licence is granted beyond viewing and
linking through the hosting service, and contributions are not
accepted (C-017).

ARCHIVING

Historical material should remain clearly separated from active
documentation. Legacy or superseded material belongs in
08 - ARCHIVE and must not be mistaken for current policy.

OPEN ITEMS

These are unresolved and recorded in
01 - CORPORATE/Decisions/Consistency Log.txt:

C-005  The public website still serves the previous identity's
       legal text while this repository holds North Assembly
       drafts.

C-008  "Vault" appears on the website but has no documented
       ownership in the project registry.

C-010  The public website still carries the previous identity's
       branding and an outdated people list.

C-014  Former-member identifiers remain in git history committed
       before 2026-10-01. Owner decision 2026-10-03: history is
       left as committed and the exposure is accepted
       (ADR-0007).

C-018  The legal set now contains frameworks for liability,
       indemnity, language, acceptance, appeals and
       notice-and-takedown, but every one of them still carries
       [PENDING] values and awaits legal review.

[MANDATORY]
None of these may be closed by assumption. They close only when
the underlying facts are confirmed and recorded.

END OF DOCUMENT
