# Product Architecture

Business X-Ray is split into three layers.

## Layer 1 — Public Experience

The public website, landing pages and lead generation experience.

Owned primarily by:

- `bx-theme`
- selected shortcodes/blocks from `bx-platform`

Core public experiences:

- Homepage
- 60 Second X-Ray
- Free Business X-Ray assessment
- Business X-Ray landing page
- Pricing / pilot offer
- Booking page
- Report preview
- Case studies
- FAQ

## Layer 2 — Operator Experience

The admin and consultant dashboard used to manage the Business X-Ray process.

Owned primarily by:

- `bx-platform`

Core operator areas:

- Dashboard
- Businesses
- Contacts
- Assessments
- Reports
- Recommendations
- Tasks
- Timeline
- Settings

## Layer 3 — Client Experience

The secure client-facing view of progress, reports, recommendations and action plans.

Owned primarily by:

- `bx-platform`
- theme templates from `bx-theme`

Core client areas:

- Business Health overview
- Reports
- Action plan
- Progress timeline
- Meeting notes
- Documents

## Product Principles

- The theme never owns business logic.
- The platform never depends on one theme.
- Shortcodes/blocks are presentation bridges, not the source of truth.
- Data should be portable.
- Recommendations must remain explainable.
- Every major action should be logged.
