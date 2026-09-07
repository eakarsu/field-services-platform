# Feature status — Home & field services

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 224 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 5 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 6 | 0 | Native records/view |
| Time tracking | records | 3 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 3 | 0 | Native records/view |
| Activity & audit trail | audit | 0 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Route Optimization | records | 2 | 0 | Native records/view |
| Supply Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality Verification | records | 1 | 0 | Native records/view |
| Contract Pricing | records | 2 | 0 | Native records/view |
| Compliance Tracking | records | 1 | 0 | Native records/view |
| Crew Management | records | 2 | 0 | Native records/view |
| Work Orders | records | 1 | 0 | Native records/view |
| Equipment Management | records | 4 | 0 | Native records/view |
| Incident Reports | records | 1 | 0 | Native records/view |
| Scheduling | records | 2 | 0 | Native records/view |
| Expense Tracking | records | 2 | 0 | Native records/view |
| Checklists | records | 1 | 0 | Native records/view |
| Webhooks | integration | 3 | 0 | Provider request records only |
| Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Job Quotes & Estimation | records | 1 | 0 | Native records/view |
| Materials & Pricing | records | 1 | 0 | Native records/view |
| Building Code Compliance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Technician Management | records | 1 | 0 | Native records/view |
| Warranty Tracking | records | 1 | 0 | Native records/view |
| Service Contracts | records | 1 | 0 | Native records/view |
| Permits & Inspections | records | 1 | 0 | Native records/view |
| Supplier Management | records | 1 | 0 | Native records/view |
| History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material estimate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quote estimate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Schedule optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai job estimator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| code compliance automation | records | 1 | 0 | Native records/view |
| material waste prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| technician productivity tracking | records | 1 | 0 | Native records/view |
| aihistory js stub needs real implementation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| jobquotes without quote | records | 1 | 0 | Native records/view |
| schedules without schedule | records | 1 | 0 | Native records/view |
| code compliance without code | records | 1 | 0 | Native records/view |
| real integration with permit code databases onl | integration | 1 | 0 | Provider request records only |
| customer financing options credit payment plans | records | 1 | 0 | Native records/view |
| supply chain integration material ordering auto | integration | 1 | 0 | Provider request records only |
| limited photo documentation before after | records | 1 | 0 | Native records/view |
| accounting system integration quickbooks freshb | integration | 1 | 0 | Provider request records only |
| notifications module grep 0 | records | 1 | 0 | Native records/view |
| mobile app for techs | records | 1 | 0 | Native records/view |
| Service Catalog | records | 1 | 0 | Native records/view |
| Properties | records | 1 | 0 | Native records/view |
| Quotes & Estimation | records | 2 | 0 | Native records/view |
| Job Scheduling | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Chemical Inventory | records | 1 | 0 | Native records/view |
| Photo Documentation | records | 1 | 0 | Native records/view |
| Recurring Service Plans | records | 1 | 0 | Native records/view |
| Fleet Tracking | records | 1 | 0 | Native records/view |
| Equipment Maintenance | records | 2 | 0 | Native records/view |
| Safety Checklists | records | 1 | 0 | Native records/view |
| Insurance Certificates | records | 1 | 0 | Native records/view |
| Environmental Compliance | records | 1 | 0 | Native records/view |
| Training Records | records | 1 | 0 | Native records/view |
| Referral Tracking | records | 1 | 0 | Native records/view |
| Online Bookings | records | 1 | 0 | Native records/view |
| Reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Marketing Campaigns | records | 1 | 0 | Native records/view |
| Locations | records | 1 | 0 | Native records/view |
| Route Sheets | records | 1 | 0 | Native records/view |
| AI Quote Estimator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Chemical Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Weather Scheduler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Marketing Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Upsell Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Quote Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Route Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Weather Schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Equipment Maintenance Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Customer Churn Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic job orchestration | records | 1 | 0 | Native records/view |
| computer vision job estimation | records | 1 | 0 | Native records/view |
| crew mobile companion | records | 1 | 0 | Native records/view |
| seasonal demand forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| customer lifecycle optimization | records | 1 | 0 | Native records/view |
| equipment without equipment | records | 1 | 0 | Native records/view |
| crews without crew | records | 1 | 0 | Native records/view |
| customers without customer | records | 1 | 0 | Native records/view |
| contracts without contract | records | 1 | 0 | Native records/view |
| limited mobile app for crew 1 mobile reference no | records | 1 | 0 | Native records/view |
| real | records | 1 | 0 | Native records/view |
| integration with payment processing square stri | integration | 1 | 0 | Provider request records only |
| limited customer self | records | 1 | 0 | Native records/view |
| integration with accounting quickbooks freshboo | integration | 1 | 0 | Provider request records only |
| frontend severely underbuilt for 29 | records | 1 | 0 | Native records/view |
| AI draft workspace | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quote Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Follow-up Assistant | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Operations | records | 1 | 0 | Native records/view |
| Jobs | records | 2 | 0 | Native records/view |
| Dispatch | records | 1 | 0 | Native records/view |
| Schedule | records | 1 | 0 | Native records/view |
| Estimates | records | 1 | 0 | Native records/view |
| Software subscription | records | 1 | 0 | Native records/view |
| Payments & refunds | records | 1 | 0 | Native records/view |
| Inventory | records | 1 | 0 | Native records/view |
| Agreements | records | 1 | 0 | Native records/view |
| Technicians | records | 1 | 0 | Native records/view |
| AI Features | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settings | records | 1 | 0 | Native records/view |
| Today's Jobs | records | 1 | 0 | Native records/view |
| Truck Inventory | records | 1 | 0 | Native records/view |
| Address | records | 1 | 0 | Native records/view |
| Payment method | records | 1 | 0 | Native records/view |
| Order | records | 1 | 0 | Native records/view |
| Order item | records | 1 | 0 | Native records/view |
| Garment type | records | 1 | 0 | Native records/view |
| Service | records | 2 | 0 | Native records/view |
| Driver | records | 1 | 0 | Native records/view |
| Route | records | 1 | 0 | Native records/view |
| Pickup | records | 1 | 0 | Native records/view |
| Locker | records | 1 | 0 | Native records/view |
| Service price | records | 1 | 0 | Native records/view |
| Alteration | records | 1 | 0 | Native records/view |
| Alteration type | records | 1 | 0 | Native records/view |
| Subscription | records | 1 | 0 | Native records/view |
| Subscription plan | records | 1 | 0 | Native records/view |
| Coupon | records | 1 | 0 | Native records/view |
| Gift card | records | 1 | 0 | Native records/view |
| Machine | records | 1 | 0 | Native records/view |
| Location | records | 1 | 0 | Native records/view |
| Machine usage | records | 1 | 0 | Native records/view |
| Payment | records | 2 | 0 | Native records/view |
| Receipt | records | 1 | 0 | Native records/view |
| Staff | records | 1 | 0 | Native records/view |
| Notification | records | 2 | 0 | Native records/view |
| Estimate | records | 1 | 0 | Native records/view |
| Stain analysis | records | 1 | 0 | Native records/view |
| Chat history | records | 1 | 0 | Native records/view |
| Demand prediction | records | 1 | 0 | Native records/view |
| Quality issue | records | 1 | 0 | Native records/view |
| Driver location | records | 1 | 0 | Native records/view |
| Order tracking | records | 1 | 0 | Native records/view |
| Result | records | 1 | 0 | Native records/view |
| Garment lifecycle event | records | 1 | 0 | Native records/view |
| Whats app conversation | records | 1 | 0 | Native records/view |
| Churn score | records | 1 | 0 | Native records/view |
| Claim template | records | 1 | 0 | Native records/view |
| Damage claim | records | 1 | 0 | Native records/view |
| Claim access | records | 1 | 0 | Native records/view |
| Claim document | records | 1 | 0 | Native records/view |
| Claim document version | records | 1 | 0 | Native records/view |
| Claim review | records | 1 | 0 | Native records/view |
| Claim signature | records | 1 | 0 | Native records/view |
| Claim audit event | records | 1 | 0 | Native records/view |
| Claim export | records | 1 | 0 | Native records/view |
| Category | records | 1 | 0 | Native records/view |
| Business | records | 1 | 0 | Native records/view |
| Business photo | records | 1 | 0 | Native records/view |
| Business video | records | 1 | 0 | Native records/view |
| Business hours | records | 1 | 0 | Native records/view |
| Service area | records | 1 | 0 | Native records/view |
| Review | records | 1 | 0 | Native records/view |
| Review photo | records | 1 | 0 | Native records/view |
| Review response | records | 1 | 0 | Native records/view |
| Booking | records | 1 | 0 | Native records/view |
| Quote request | records | 1 | 0 | Native records/view |
| Quote | records | 1 | 0 | Native records/view |
| Favorite | records | 1 | 0 | Native records/view |
| Message | records | 1 | 0 | Native records/view |
| Lead | records | 1 | 0 | Native records/view |
| Business analytics | records | 1 | 0 | Native records/view |
| Advertisement | records | 1 | 0 | Native records/view |
| Chat session | records | 1 | 0 | Native records/view |
| Email verification token | records | 1 | 0 | Native records/view |
| Skill | records | 1 | 0 | Native records/view |
| Technician | records | 1 | 0 | Native records/view |
| Availability window | records | 1 | 0 | Native records/view |
| Work order | records | 1 | 0 | Native records/view |
| Dispatch assignment | records | 1 | 0 | Native records/view |
| Job event | records | 1 | 0 | Native records/view |
| Change order | records | 1 | 0 | Native records/view |
| Refund | records | 1 | 0 | Native records/view |
| Inventory item | records | 1 | 0 | Native records/view |
| Inventory reservation | records | 1 | 0 | Native records/view |
| Customer communication | records | 1 | 0 | Native records/view |
| Offline command | records | 1 | 0 | Native records/view |
| Provider connection | records | 1 | 0 | Native records/view |
| Webhook event | integration | 1 | 0 | Provider request records only |
| Outbox event | records | 1 | 0 | Native records/view |
| External operation | records | 1 | 0 | Native records/view |
| Legal documents | records | 1 | 0 | Native records/view |
| Leads | records | 1 | 0 | Native records/view |
| Crew | records | 1 | 0 | Native records/view |
| Trucks | records | 1 | 0 | Native records/view |
| Storage | records | 1 | 0 | Native records/view |
| Claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Elevator reservation window | records | 1 | 0 | Native records/view |
| real time gps customer eta notifications | records | 1 | 0 | Native records/view |
| vision based damage assessment claim photos | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| customer portal with ar pre move | records | 1 | 0 | Native records/view |
| market rate pricing engine weather fuel | records | 1 | 0 | Native records/view |
| insurance partner integrations auto issue coi | integration | 1 | 0 | Provider request records only |
| referral upsell agent packing supplies cleaning | records | 1 | 0 | Native records/view |
| vision based damage assessment from | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| pre move questionnaire deep analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| market rate pricing optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive demand pre positioning of | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| customer sentiment dashboard across surveys | records | 1 | 0 | Native records/view |
| real time gps tracking for | records | 1 | 0 | Native records/view |
| customer portal move tracker | records | 1 | 0 | Native records/view |
| insurance liability policy management | records | 1 | 0 | Native records/view |
| payment processing module stripe ach | integration | 1 | 0 | Provider request records only |
| webhooks for partners storage packing | integration | 1 | 0 | Provider request records only |
| multi vendor logistics marketplace | records | 1 | 0 | Native records/view |
| ar pre move visualization | records | 1 | 0 | Native records/view |
| Evidence | records | 1 | 0 | Native records/view |
| Servicecrewai mobile work | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 224 feature pages were visited in the browser; 222 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 38 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

38 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
