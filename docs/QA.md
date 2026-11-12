# QA — UKR-441 local concept

**Verification date:** 2026-08-31  
**Scope:** local static concept only; no deployment, public release, contact action or customer-system access.

## Owner checks

| Check | Result | Evidence / note |
| --- | --- | --- |
| Pre-code gate | PASS | Independent Reviewer PASS after the source, asset and similarity remediation. |
| Fact-expansion review | PASS | Independent Reviewer, 2026-08-31: all added customer-visible claims have non-recruitment public support; no third-party project photo or unknown asset was introduced. |
| Fact-expansion Desktop render | PASS | Chrome 1440×900 screenshot: `../evidence/screenshots/fact-expansion-desktop.png`; Hero, regional cue and free-quote CTA fit. |
| Fact-expansion Mobile render | PASS | Chrome 390×844 screenshot: `../evidence/screenshots/fact-expansion-mobile.png`; Hero copy and CTA actions remain fully visible. |
| Final polish mobile render | PASS | CDP device emulation at 390×844; full-page evidence `../evidence/screenshots/polish-mobile-full-current-390.png`. `scrollWidth = clientWidth = 390`; independent Reviewer found no crop or horizontal overflow through Services, Method, Proof and Closing. |
| Real-project Proof pre-code gate | PASS | Independent Reviewer, 2026-08-31: the two public FindGlocal reposts retain third-party provenance and local-only boundary; their limited service labels do not overstate a finished result. |
| Real-project Proof desktop render | PASS — owner visual check | CDP 1440×900 device metrics; full-page evidence `../evidence/screenshots/real-proof-desktop-cdp-1440.png`. `scrollWidth = clientWidth = 1440`; the wall-repair record is contained in the narrow proof panel and the kitchen-respray detail carries the wide panel without changing the Hero or service rhythm. |
| Real-project Proof mobile render | PASS — owner visual check | CDP 390×844 mobile device metrics; full-page evidence `../evidence/screenshots/real-proof-mobile-cdp-390.png`. `scrollWidth = clientWidth = bodyScrollWidth = 390`; the two proof photos stack in source order and labels remain visible. Earlier headless-window captures are retained as diagnostic artifacts only because they did not apply true mobile device metrics. |
| Desktop render | PASS | Chrome headless screenshot: `../evidence/screenshots/desktop-1440x900.png` (1440×900). Hero, navigation, CTA and original concept image visibly render. |
| Mobile render | RE-RUN REQUIRED | Independent review found right-edge clipping in the first 390×844 capture. CSS was remediated with a mobile-safe headline size, word wrapping and `overflow-x: hidden`; capture must be replaced before acceptance. |
| Horizontal overflow | RE-RUN REQUIRED | Same independent finding; no acceptance claim until the replacement 390×844 rendering is inspected. |
| CTA and navigation | REMEDIATED — RE-REVIEW REQUIRED | Three internal anchors resolve to existing section IDs. The external CTA now accurately says `Open public business profile`, not an owned contact page; no form, tracking or mail action is present. |
| Console / load | PASS | Chrome loaded and emitted both screenshots. No page JavaScript error was emitted; platform display-link messages were from headless Chrome, not page code. |
| Keyboard / focus | PASS — static interaction review | menu button and navigation links have keyboard-focus rules; menu toggles `aria-expanded`; controls retain native keyboard activation. |
| Reduced motion | PASS | `prefers-reduced-motion: reduce` removes transitions and smooth scrolling. No autoplay or automatic animation exists. |
| CLIENT-VISIBLE INTERNAL-TEXT GATE | PASS | Scan of `demo/` found no banned governance, AI, asset-rights, placeholder or draft wording. Customer-visible identity is limited to `Independent concept preview`. |
| Business fidelity | PASS — owner check | Checked against `BUSINESS_FIDELITY_MAP.md`: services, location and free-quote framing are evidence-backed. The two Proof photos have source, hash and deliberately narrow labels; no reviews, certifications, personnel, prices, guarantees or fabricated claims are present. |
| Static boundary | PASS | One HTML file, local image and minimal menu JS only. No CMS, database, login, payment, form, tracking or network dependency. |

## Bottom 40% commercial check

- New business information: the preparation standard and the kitchen-respray route turn sparse feed updates into a tangible quote-discussion path.
- Visual return: the asymmetric proof pair makes wall repair and kitchen respray visibly concrete; it avoids a before/after or completed-project claim.
- Repetition: contact appears once as the final action; no oversized generic CTA series or duplicated contact block.
- Specificity: closing copy retains Aberdeen/Aberdeenshire and verified decorating/respray/preparation scope.
- Narrative: service understanding → working standard → specialist offer → public contact route.

**BOTTOM 40% COMMERCIAL QA = PASS (Owner self-check).**

## Required independent result

`INDEPENDENT VISUAL ACCEPTANCE = PASS — 2026-08-31.` Independent Reviewer checked the current CDP 390×844 and 1440×900 full-page renders, the proof labels, fidelity map and ledger: no P0/P1, no horizontal crop, and no exaggerated project-result or source statement.  
`CLIENT-SHOWABLE DEMO = PASS — local static Concept Preview only; pending user acceptance. No deployment, publication or outreach is implied.`

## Actual Demo Minutes

`Actual Demo Minutes: 64` (research handoff excluded; includes pre-code gates, original concept image, implementation and local verification). `SOP COST REVIEW = TRIGGERED` because elapsed time exceeded 60 minutes; no scope was expanded.

## Remaining risks

1. `CUSTOMER AUTHORIZATION: NOT VERIFIED` remains an internal risk. Two public third-party reposts are shown only under the user's local Concept Preview direction; all other current imagery remains concept atmosphere.
2. The public business email was intentionally not embedded because the source extractor obscures the address; the reviewed public contact route is used instead.
3. No deployment, sending, public accessibility or user acceptance has occurred.
