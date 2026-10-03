NORTH ASSEMBLY
SUPERSEDED DOCUMENTS — PROVENANCE

DOCUMENT ID: NA-ARC-SUPERSEDED
Type: INDEX (unversioned)
Status: ACTIVE
Classification: INTERNAL
Last Modified: October 1, 2026
Related: NA-ARC-INDEX, ADR-0001, ADR-0002

PURPOSE

This file records where the material in this directory came from
and what replaced it. The archived files themselves are preserved
as they were and carry no added headers.

CORPORATE v1.1/

  Source: repository state at commit 783bc54 (2026-09-29).
  Captured: 2026-10-01, immediately before the October 2026
  rewrite of the corporate documents.

  Organization v1.1 (superseded 2026-10-01).txt
    Recorded the previous roster. Replaced by NA-COR-002 v2.0.
    Reason: the roster did not reflect the current structure
    (ADR-0002).

  Manual Corporativo v1.1 (superseded 2026-10-01).txt
    Replaced by NA-COR-003 v2.0. Reasons: it restated the roster
    instead of referencing it, listed a retired product as current,
    promised two policies that did not exist, and retained two
    references to the previous organizational identity.

  Document Control v1.1 (superseded 2026-10-01).txt
    Replaced by NA-COR-001 v2.0. Reasons: five status values were
    defined while at least nine were in use, and STATUS and
    CLASSIFICATION were conflated.

WEIRD STUFF ERA/

  Source: repository history. Two states of the previous tree are
  kept side by side:

  A. Seven legal files with English filenames carry the previous
     identity in their headers (WEIRD STUFF, Version 1.0) and come
     from their last existing revisions (commit 90097f4 and
     earlier).

  B. The corporate files, the seven legal copies with Spanish
     filenames (headers already rebranded, NORTH ASSEMBLY Version
     1.1), and the section README come from commit 54b26f2, the
     last state of the previous tree. The root README comes from
     the state just before the tree was reorganized (commit
     783f3ad).

  Captured: 2026-10-01, recovered from repository history under
  C-015.

  Set A shows the texts as they existed before the rebrand to
  North Assembly (ADR-0001). Set B shows the same tree just
  before the October 2026 rewrite, when the headers had already
  been rebranded but the files still lived under the previous
  directory names. Both predate the eight-section restructure
  (ADR-0004).

  [MANDATORY]
  Neither set is effective law. Set A is the previous identity's
  drafts; set B is superseded by the current drafts in 02 - LEGAL
  and exists only to show what the October 2026 rewrite changed.

LEGAL v1.0 PUBLISHED ON WEBSITE/

  Source: belfegor442.github.io, docs/Legal/, as served publicly
  on 2026-10-01.

  Captured: 2026-10-01.

  Why this copy exists: this text was publicly presented as the
  site's legal terms under the previous identity. It differs from
  the current drafts in this repository. Tracked as C-005 in the
  Consistency Log.

  [MANDATORY]
  This copy is historical. It is not an effective legal document
  and must not be republished as one.

RULES

[MANDATORY]
Files in this directory are byte-preserved from their source.
Corrections are never made in place; a correction would be a new
document with its own record.

EXCEPTION RECORDED 2026-10-01

Two recorded exceptions apply to the files above, both under
ADR-0007:

1. PERSONNEL REDACTION. The roster sections of the two Corporate
   v1.1 documents and the two Weird Stuff era corporate documents
   named former members. Those identifiers are replaced with:

     [REDACTED - former member, see ADR-0007]

   Structure, roles, dates and every other line are unchanged.
   Personal-data protection takes precedence over byte fidelity.

2. LINE-BREAK REPAIR. Twelve files recovered from commit 54b26f2
   had lost their line breaks during the original recovery. They
   were re-extracted from the same commit and verified byte-size
   identical to the stored blobs (C-015).

[MANDATORY]
Identifiers committed to repository history before October 1,
2026 are not affected by these fixes. Their removal would require
rewriting history. Owner decision 2026-10-03: history stays as
committed and the exposure is accepted (ADR-0007, Consistency Log
C-014).

[MANDATORY]
Files in this directory are superseded. None of it may be quoted
as current policy, current structure, or current legal terms.

END OF DOCUMENT
