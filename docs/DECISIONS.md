# Memory Tailor — Owner Decision Register

Last updated: 2026-10-14

This is the authoritative engineering-facing record of owner decisions. When an older audit recommendation conflicts with an APPROVED decision below, the approved decision wins.

## D-001 — Launch price and market
Status: APPROVED
Decision:
- Initial selling price: $49.99
- Initial sales market: United States only

## D-002 — Cosmetic template demo products
Status: APPROVED
Decision:
- Delete the Blocksy/Cosmetic template demo products.
- Retain the real Memory Tailor Custom 3D Pet Portrait Keychain product draft #1589.

## D-003 — Staging and recovery approach
Status: APPROVED
Decision:
- A separate staging environment is not a prerequisite at the current early development stage.
- Establish a clean backup/restore baseline before substantial changes.
- Reassess staging before live payments and real customer orders.

Rationale:
The project has not yet entered meaningful production commerce, so staging now adds process overhead without enough current-state value.

## D-004 — Customer photo upload and storage
Status: APPROVED
Decision:
- Customer pays first and a WooCommerce order is created.
- Customer receives a unique post-purchase upload link.
- Uploaded pet photos are associated with the corresponding WooCommerce order.
- Staff can review/manage uploads through the WordPress backend.
- Underlying customer files must use private/protected access rather than ordinary publicly exposed upload URLs.

## D-005 — Customer-facing contact
Status: APPROVED
Decision:
- General customer-facing contact: info@memorytailor.com
- Legal/operational policies will be drafted around the actual Memory Tailor workflow and reviewed before commercial launch.

## D-006 — Supplier/sample validation
Status: OPEN
Question:
Define the physical sample validation plan, supplier validation requirements, and maximum pre-launch validation spend.

## Pending later decisions
Additional decisions remain for final product specifications, upload-photo requirements, preview/revision policy, payment activation, tax, shipping coverage, refund/remake rules, AI/modeling workflow, supplier SLA, analytics, and controlled launch limits.
