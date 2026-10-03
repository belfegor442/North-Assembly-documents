NORTH ASSEMBLY
PROJECT REGISTRY AND PRODUCT DOCUMENTATION

DOCUMENT ID: NA-PRD-INDEX
Type: INDEX AND REGISTRY (unversioned)
Status: ACTIVE
Classification: INTERNAL
Last Modified: October 1, 2026
Related: NA-COR-002, NA-COR-004, ADR-0003

PURPOSE

This file is the project registry: the single list of what North
Assembly builds, what state it is in, who owns it, and whether it
can be delegated. Individual product folders hold the detail.

[MANDATORY]
The project list, statuses, owners and delegation levels recorded
here are the source of truth. Other documents reference this
registry instead of restating it.

[MANDATORY]
A project is not active merely because a folder exists.

============================================================
REGISTRY
============================================================

Classification:  NA INTERNAL | NA PRODUCT | NA PUBLIC |
                 EXPERIMENTAL | ARCHIVED
Delegation:      NONE | LIMITED | SUPPORTED | OPEN |
                 NOT APPLICABLE
Owner:           recorded per project; [REQUIRES CONFIRMATION]
                 where no owner has been assigned

ID              PROJECT      CLASS        STATUS
NA-PRD-MON      Monix        NA PRODUCT   ACTIVE DEVELOPMENT
NA-PRD-TEL      Telenet      [PENDING]    PENDING DEFINITION
NA-PRD-DAT      Datalog      [PENDING]    PENDING DEFINITION
NA-PRD-CRY      CryptCast    [PENDING]    PENDING DEFINITION
NA-PRD-DRA      DraftPad     ARCHIVED     RETIRED
NA-PRD-CMD      NA Command   NA INTERNAL  NOT DOCUMENTED
NA-PRD-MSG      msg.term     NA INTERNAL  NOT DOCUMENTED
NA-PRD-MEA      Meat         [UNKNOWN]    NOT DOCUMENTED

ID              PROJECT      OWNER                 DELEGATION
NA-PRD-MON      Monix        [REQUIRES CONFIRM]    LIMITED (proposed)
NA-PRD-TEL      Telenet      [PENDING]             NOT APPLICABLE
NA-PRD-DAT      Datalog      [PENDING]             NOT APPLICABLE
NA-PRD-CRY      CryptCast    [PENDING]             NOT APPLICABLE
NA-PRD-DRA      DraftPad     [PENDING]             NOT APPLICABLE
NA-PRD-CMD      NA Command   [UNKNOWN]             NONE (proposed)
NA-PRD-MSG      msg.term     [UNKNOWN]             NONE (proposed)
NA-PRD-MEA      Meat         [UNKNOWN]             [UNKNOWN]

ID              PROJECT      DOCUMENTATION
NA-PRD-MON      Monix        FULL (18 documents)
NA-PRD-TEL      Telenet      PLACEHOLDER (2 documents)
NA-PRD-DAT      Datalog      PLACEHOLDER (2 documents)
NA-PRD-CRY      CryptCast    PLACEHOLDER (2 documents)
NA-PRD-DRA      DraftPad     PLACEHOLDER, ARCHIVED (2 documents)
NA-PRD-CMD      NA Command   PLACEHOLDER (1 document)
NA-PRD-MSG      msg.term     PLACEHOLDER (1 document)
NA-PRD-MEA      Meat         PLACEHOLDER (1 document)

NOT IN THE REGISTRY

Vault — a project of this name appears on the public website. It is
NOT recorded as a North Assembly project here because ownership has
not been confirmed. [REQUIRES CONFIRMATION]
Tracking: C-008 in the Consistency Log.

belfegor442.github.io — the public website. Treated as NA PUBLIC
infrastructure; it is maintained in its own repository and is not
documented here beyond this reference.

============================================================
DELEGATION LEVELS
============================================================

NONE
Not suitable for delegation. Architecture, core engineering,
internal infrastructure, systems programming, internal tooling and
organization-specific knowledge normally sit here.

LIMITED
Assigned work under direct supervision by the CEO or Director.

SUPPORTED
A collaborator leads the work; CEO or Director available on
request.

OPEN
Any member may contribute (documentation, small fixes).

[MANDATORY]
Delegation levels are proposals until the CEO confirms them. A
value marked (proposed) must not be treated as decided.

[MANDATORY]
Delegation levels feed recruitment: a position may only be created
when a registry row shows work that justifies it (NA-COR-004).

============================================================
RECRUITMENT LINK
============================================================

Each registry row answers: does this project currently justify a
Developer or Designer position?

[MANDATORY]
If no row shows delegable work, the corresponding position stays
VACANT in NA-COR-002.

============================================================
DOCUMENT RULE
============================================================

Product documentation should describe the product as it actually
exists or clearly identify planned, pending, or developmental
material. Product definition belongs in Product Overview and
Product Specification documents; implementation details belong in
technical documentation.

[MANDATORY]
Planned functionality must never be presented as existing
functionality.

[MANDATORY]
A product's status in this registry must match the status in its
own documents. A mismatch is logged in the Consistency Log.

============================================================
PRODUCT ORDER
============================================================

01 - Monix       Observability and diagnostics for Windows.
02 - Telenet     Placeholder; purpose not yet defined.
03 - Datalog     Placeholder; purpose not yet defined.
04 - DraftPad    Retired; historical record only.
05 - CryptCast   Placeholder; purpose not yet defined.
06 - NA Command  Internal organizational tooling.
07 - msg.term    Terminal-oriented communication component.
08 - Meat        Existence known; purpose not documented.

END OF DOCUMENT
