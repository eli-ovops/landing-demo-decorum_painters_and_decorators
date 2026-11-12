# UKR-441 — Pre-code decision

> **v1.2 supersession — 2026-08-31:** FAIL — REDESIGN DIRECTION. Every earlier direction, asset plan and reviewer result in this file is historical only. The authority is the v1.2 public-intelligence and asset-harvest workflow. Current evidence is in CUSTOMER_PUBLIC_INTELLIGENCE.md and ASSET_INVENTORY.csv; no further customer-visible implementation may be accepted until a replacement v1.2 decision, image-processing record and independent pre-code review are complete.

## Current v1.2 decision — authoritative for this rebuild

### Authority, scope and skill route

- Target Market: United Kingdom. Current Offer: GBP £600 one-time static single page; payment milestones are unknown.
- Scope: local static Concept Preview only. No deployment, upload, login, outreach, form handling or production change.
- Authority read receipt, 2026-08-31: AGENTS.md SHA-256 ad669e4e4878677ba62a94b2639ac828959a9c1db43ac40aabac6fca0173ec83; PROJECT_CORE.md SHA-256 8ebb13ab6cc25d23fcb6a8b4ee93b3ab8d624d7cd4fb1dcc2adf632c8d5984b2.
- website-delivery-sop: maps local L0 scope, explicit non-scope and two-viewport independent acceptance to this file and QA.
- design-taste-frontend: maps the left-anchored hero, modest two-line display scale, mobile proof stacking and anti-centre-bias checks to demo/index.html.
- media-use: maps public-intelligence source segregation, asset inventory, original/derived separation, unique placement and ledger checks to the asset files and IMAGE_LEDGER.md.
- finesse-ui (redesign mode, 2026-08-31): used after visual feedback to audit the live composition. Its concrete changes are the left-bottom Hero anchor in `demo/index.html`, two-line mobile title sizing, removal of repeated non-essential section labels, and the responsive Proof-strip grid that changes 3 → 2 → 1 columns before clipping can occur. Frame-smith and finesse-brief were not used: this is neither a video deliverable nor a product/workbench-planning task.

### Customer public intelligence and asset coverage

| Category | Decision | Page mapping or exclusion |
|---|---|---|
| Official social pointer | Facebook page ID 526852720709746 is linked from the matching Aberdeen listing but current direct access is throttled. | Exclude assets; show no reproduced logo. |
| Third-party mirror photos | Two FindGlocal copies are preserved with source, hash and public-mirror provenance. | User-directed exception: use only as the two narrowly labelled local Proof cards; no broader customer-asset claim. |
| Region | Aberdeen and Aberdeenshire coverage is a dated source claim. | Hero regional cue and closing location line. |
| Services | Wall repair/redecoration, kitchen respray, Ames taping, wallpapering, exterior work and woodwork have dated public-source support. | Three service statements plus process/proof copy. |
| Evidence of current operation | 2026-06-22 recruitment and dated project posts. | Bottom proof uses recruitment/service specificity, not invented reviews. |
| Contact | Public phone 07949 364792. Email is not recoverable. | One tel CTA; no invented email/form. |
| Logo, reviews, full address, team/vehicle image | Not directly verifiable as usable official assets. | Omit. |

### Current Offer Purchase Thesis

For GBP £600, a single owned presentation can turn Decorum’s scattered Aberdeen/Aberdeenshire trade posts into a clear call-for-quote journey that distinguishes wall repair and preparation, kitchen resprays and Ames taping, while using the only verified public contact path. The hero will identify the trade without swallowing the work scene; the lower page will make the preparation-led value proposition legible before the telephone CTA.

### Design Read and dials

Reading this as: a local-trade Concept Preview for Aberdeen homeowners, with a precise, workshop-editorial language that keeps the room and the work visible rather than centring oversized type.

- DESIGN_VARIANCE: 6
- MOTION_INTENSITY: 3
- VISUAL_DENSITY: 5

### Two material directions

| Direction | Hero / rhythm | Real-asset role | Bottom 40% | Decision |
|---|---|---|---|---|
| A — Workshop journal | Left-bottom copy on a full-room surface-preparation scene; compact service filmstrip; vertical process ledger; split proof; room close. | Official assets unavailable, so unique constrained concept scenes carry only generic trade context; verified service language gives customer specificity. | Recruitment/service proof, preparation sequence and phone conversion. | Selected: directly fixes centred hero and proof overflow while keeping copy short. |
| B — Project-board grid | Narrow image rail with modular project cards, utilitarian nav and a top-right quote panel. | Would require several usable official project images to feel customer-owned. | Card-led selection and quote panel. | Rejected: official source-image access is blocked, so it would overstate a portfolio that cannot be shown honestly. |

### Full-page visual storyboard and implementation map

| Section / selector | Commercial task and verified basis | Visual carrier and layout | Desktop / mobile rule | Rights / motion |
|---|---|---|---|---|
| Hero .hero | Identify Aberdeen decorators and phone quote path. | One unique full-room concept scene; text sits left-bottom, max two display lines. | Copy width 42 percent desktop; 100 percent mobile, no centred block. | Concept only; static. |
| Services .services | Separate wall repair, kitchen respray and Ames taping. | Three distinct, non-reused service scenes in a staggered grid. | One large plus two small desktop; stacked mobile. | Concept only; static. |
| Method .method | Make preparation the reason for the finish. | One preparation scene beside a three-step process. | Side-by-side desktop; image then steps mobile. | Concept only; static. |
| Proof .story | Explain trade specificity without pretending a portfolio. | Two unique close views plus a responsive three-item service strip. | CSS grid minmax; strip wraps to one column before clipping. | Concept only; hover feedback only. |
| Closing .closing | Give a clear route to a free quote. | One unique finished-room scene plus Aberdeen/Aberdeenshire line. | Left-aligned closing copy; CTA remains in view. | Concept only; static. |

Anti-template constraints: no centre-anchored hero; no headline over three desktop lines; no equal three-card grid as the primary section; no invented testimonials, customer jobs or employee photography; no repeat-image crops; no lower-page oversized generic CTA.

Shown in Demo: business name, Aberdeen/Aberdeenshire, three core services, preparation-led explanation, public telephone route and a small Independent concept preview marker.

Reserved for Final Delivery: approved official brand mark, confirmed project gallery, verified email/address, full service coverage, customer-approved claims and any booking integration.

PRE-CODE GATE: AWAITING INDEPENDENT V1.2 REVIEW.

### Fact-expansion amendment — 2026-08-31

Reading this as: a local-service Concept Preview for Aberdeen homeowners, with a calm, preparation-led editorial language and an asymmetric room-first composition.

- `DESIGN_VARIANCE = 6`, `MOTION_INTENSITY = 3`, `VISUAL_DENSITY = 6`. The page remains static apart from user-initiated hover feedback.
- The purpose is not to make the Demo longer. It is to surface every suitable non-recruitment public fact that currently helps an owner recognise the breadth of Decorum's work: Aberdeenshire coverage; exterior work; coving; wood painting, glossing and staining; wallpaper removal and repair; kitchen resprays; Ames taping; gas-box and garage-door spray detail; and a free quotation invitation.
- Page map: Hero regional line becomes `Aberdeen & Aberdeenshire`; a new compact scope band groups interior/exterior, wall and wallpaper work, woodwork/coving, and sprayed/detail finishes; Story copy names wallpaper-removal repair, Ames taping and detail spraying; closing becomes an explicit free-quote path.
- Exclusions remain unchanged: no logo, email, street address, hours, reviews, awards, customer photos, van/team imagery, third-party mirror photographs, or customer-facing claims drawn only from a recruitment listing. Recruitment is treated only as evidence of current operation, not customer-facing marketing copy.
- Skills receipt: `website-delivery-sop` keeps this L0 local-only and no-deploy change; `design-taste-frontend` limits the extra facts to an asymmetric, visual scope band rather than a text dump; `media-use` confirms no new customer image is introduced because the available project photos remain third-party reposts.

PRE-CODE GATE FOR FACT-EXPANSION: PASS — independent review, 2026-08-31. Recruitment-only facts remain excluded.

### Real-project Proof amendment — 2026-08-31

- **User-directed scope change:** use the two locally preserved public project photographs in this local static Concept Preview. This direction is limited to the current Demo; it does not reclassify FindGlocal as Decorum's official website, establish direct Facebook retrieval, or verify customer authorisation.
- **Visual selection:** `IMG-REAL-01` is a narrow, darkened proof card titled `Wall repair` / `Wallpaper removal & preparation`. Its visible condition is treated as an in-progress repair record, never a finished-room result. `IMG-REAL-02` is the wider, softly overlaid proof card titled `Kitchen respray` / `Cabinet finish detail`; it is the dominant factual visual because its olive cabinetry belongs naturally in the existing palette.
- **Composition guardrail:** the Hero, three service scenes, preparation beat and closing-room scene stay in their existing distinct roles. Only the two former conceptual Proof cards are replaced. The portrait photos remain framed in the asymmetrical proof diptych, with a restrained site-colour overlay and no artificial before/after, retouching or generated extension.
- **Provenance and privacy:** both files remain marked as public third-party mirror copies with `CUSTOMER AUTHORIZATION: NOT VERIFIED`. Neither contains a person, visible street address or customer name. The original file, source URL, hash and local-only limitation remain in `ASSET_INVENTORY.csv` and `docs/IMAGE_LEDGER.md`.
- **Storyboard replacement:** the `Proof / work language` row in the current storyboard changes from two original concepts to these two distinct customer-attributed public project records, labelled only with their evidenced service type. No other customer-asset decision changes.

PRE-CODE GATE FOR REAL-PROJECT PROOF: PASS — independent review, 2026-08-31. P0/P1: none. The rejected AI repair image remains excluded.

## Scope and boundary

- **Role:** execution owner; local L0 static Cold Demo only.
- **Allowed:** files beneath this directory, local browser verification and original concept imagery.
- **Not allowed:** customer-account access, outreach, email sending, deployment, upload, payment, tracking, forms, CMS, server code or third-party dependencies.
- **Delivery state:** local concept preview; not a customer-approved, public or production website.

## £600 Purchase Thesis

Decorum’s current identifiable presence is a stream of short social posts. A focused one-page site can turn its verified Aberdeen/Aberdeenshire decorating, kitchen respray, wallpaper-removal repair and Ames taping work into a rapid, owned service-and-proof journey ending in a direct quote conversation—an addition that cannot be achieved by reordering an individual social post.

### Customer fact and asset coverage

| Fact / asset | Evidence | Demo use | Truth / rights boundary |
| --- | --- | --- | --- |
| Aberdeen and Aberdeenshire coverage | 22 Jun 2026 hiring post | location line and closing copy | verified business claim |
| Painting & decorating, Ames taping, wallpapering | 22 Jun 2026 hiring post; 10 Jun / 29 May project posts | service architecture | verified services only |
| Kitchen respray and repair-led preparation | 1 Jun / 10 Jun 2026 posts | featured service and process language | no claim of a specific customer project in the visual |
| Free quote invitation | 10 Jun / 29 May posts | mailto CTA label | public business channel; no form or tracking |
| Client imagery | no permission located | original atmospheric concept images | must not represent Decorum work, staff or premises |

Source: https://www.findglocal.com/GB/Aberdeen/526852720709746/Decorum-Painters-And-Decorators (checked 2026-08-31). No customer logo or social photography will be reused.

### Client-visible fact / asset decisions

| Item | State | Decision and boundary |
| --- | --- | --- |
| Business name | `USE — public source / customer authorisation not verified` | Text only; no invented legal entity. |
| Aberdeen / Aberdeenshire | `USE — current business post` | Served area only; no unsupported postcode or neighbourhood promise. |
| Painting & decorating; Ames taping; wallpapering; kitchen respray; repair-led preparation | `USE — current business posts` | Three service routes; no prices, duration, warranty or performance claims. |
| Public business email | `USE — public listing / deliverability unknown` | One `mailto:` quote CTA, no form, tracking or subscription. |
| Phone | `USE — public listing` | Visible text only in this concept; no click action until independently confirmed. |
| Logo, brand colour, typeface | `NOT VERIFIED` | No reconstruction, invented mark or claim of official identity. |
| Customer photography, social-post photography, projects, testimonials, ratings, accreditations, warranties | `DO NOT USE` | No reuse or visual implication; no review stars, badges or named jobs. |
| Owner, legal entity, exact hours, coverage radius, booking/payment route | `UNAVAILABLE / DO NOT USE` | Excluded from copy and navigation. |
| Original hero atmosphere | `USE — original concept / not business proof` | `IMG-01` only; no implication it is Decorum work. |

## Current UK reference principles (not copied)

| Reference | Current verification / applicable placement | Adopted abstract principle | Explicitly not copied |
| --- | --- | --- | --- |
| https://hampsteadpaintingcompany.co.uk/gallery | opened 2026-08-31; gallery categories and quote action visible; informs `.service-grid` hierarchy | make service paths legible before asking for contact | layout, brand and wording |
| https://justdecorating.co.uk/gallery.html | opened 2026-08-31; services, gallery and consultation route visible; informs `.method` | show preparation alongside the service list | grid, images, copy and taxonomy |
| https://www.jc-decorators.co.uk/gallery/ | opened 2026-08-31; project categories and case-study path visible; informs `.proof` | distinguish specialist work from broad decorating | imagery, awards, testimonials, case copy and page structure |

## Design Read and dials

**Design Read:** a trust-first, craft-led local-service landing page for Aberdeen homeowners and property managers, using a crisp workshop editorial language—deep charcoal, mineral white, one safety-orange action color and oversized practical typography.

- `DESIGN_VARIANCE = 7`: an asymmetric paint-swatch rail and offset proof composition avoid a generic trade-site grid.
- `MOTION_INTENSITY = 3`: purposeful hover, focus and reveal transitions only; no automatic animation.
- `VISUAL_DENSITY = 5`: enough service and process specificity to support a quote decision without a long catalogue.

## Two substantive directions

### Direction A — The Finish Ledger (selected)

- **Hero:** editorial split: strong left-side service promise and CTA; single right-side original atmosphere image framed by a vertical “Aberdeen / Aberdeenshire” paint-mark rail.
- **Rhythm:** evidence strip → service triad → tactile preparation/process ribbon → singular kitchen-respray proof moment → direct closing.
- **Bottom 40%:** makes the preparation standard and the scope of the quote conversation explicit, then gives one contact path.
- **Why selected:** it lets the owner see that social-post craft is being transformed into a credible, owned sales narrative, rather than just shown in a prettier gallery.

### Direction B — The Room Turnaround Journal (rejected)

- **Hero:** full-bleed scene with staggered “before / prepare / finish” journal modules.
- **Rhythm:** case-study-style reading path with alternating project notes and service captions.
- **Bottom 40%:** an enquiry-led checklist of room types and project stages.
- **Why rejected:** it would imply individual project stories and before/after evidence that cannot be safely or fully substantiated with authorized client imagery.

## Implementation map

| Area | Customer-specific content | Design responsibility | Implementation |
| --- | --- | --- | --- |
| Hero | Decorum, Aberdeen/Aberdeenshire, Painting & Decorating | five-second trade/location recognition | `demo/index.html` `.hero` |
| Service triad | Interior decoration, kitchen respray, preparation & repair | separate the specialist offer from general work | `.service-grid` |
| Method strip | prepare / protect / finish | makes workmanship legible without invented certification | `.method` |
| Proof moment | verified kitchen respray and wallpaper-removal repair capability | explains why a quote should start with a conversation | `.proof` |
| CTA / footer | free-quote language and a public mailto link | one clear non-data-collecting conversion path | `.contact`, `footer` |

### Motion and accessibility plan

Motion-design decision: `MOTION_INTENSITY = 3`, no automatic animation. Transitions are 160–220ms, `cubic-bezier(.2,0,0,1)`, for button press, nav focus and image lift only. `prefers-reduced-motion` removes transforms and transitions. This is a Corporate/Craft motion personality: responsiveness, not decoration.

## Anti-template commitments

- No centered gradient hero, three identical cards, stock customer claims, counters, review stars, fake form or map.
- No copied trade-site layout, images, brands, project stories, awards or testimonials.
- One asymmetric hero visual; each following section uses a different layout family.
- The only customer facts are those listed above; all visual images are original, non-assertive atmosphere.

## Skills receipt

| Skill | Artifact / direct effect | Status |
| --- | --- | --- |
| `website-delivery-sop` | Full DS-002B V2.5 receipt: SHA-256 `5b70133e7a155a713c130d07d883afffbd1f57eaa7bfc7c2e2c3dfc9f9bb926a`, mtime `2026-08-09T16:00:52Z`; role, L0 boundary and P0–P3 QA boundary recorded here | PRE-CODE MAPPED |
| `design-taste-frontend` | Design Read, dials, two directions, anti-template rules and implementation map determine `.hero`, `.service-grid`, `.method`, `.proof`, `.contact` | PRE-CODE MAPPED |
| `media-use` | `resolve.md` informed local frozen-asset/ledger handling; no provider, install, sign-in or customer asset reuse was permitted; IMG-01 is a single ledgered original concept asset | PRE-CODE MAPPED |
| `motion-design` | Corporate/Craft interaction plan and reduced-motion fallback map to CSS focus, hover and active states; no automatic animation | PRE-CODE MAPPED |

## Pre-code reviewer record

### Cross-demo similarity check

Comparison controls: `client_uk_jl_and_tm_cleaning/demo_2026-08-24` and `client_flowers_by_kodie`, chosen as two recent local-service decision records. They are controls, never sources.

| Check | UKR-441 selected direction | JL and TM Cleaning | Flowers by Kodie | Result |
| --- | --- | --- | --- | --- |
| Recognition | Aberdeen decorating / respray / preparation | Merthyr cleaning | Debenham florist | PASS |
| Hero asset role | original finish-atmosphere image and paint rail | proof-first work pair | botanical still life | PASS |
| Hero posture | trade craft + quote conversation | service evidence | occasion choice | PASS |
| Service architecture | three unequal craft routes | home/move/workplace | bouquet/tribute/gift-shop | PASS |
| Proof type | fact-led process; no customer photo | authenticated work evidence | local shop identity | PASS |
| Rhythm | hero → method → specialist proof → contact | work → service index → contact | occasion route → shop note → email | PASS |
| Bottom 40% | prep standard and single quote route | availability-led closure | shop-note email closure | PASS |
| Visual system | charcoal/mineral/orange workshop editorial | light proof system | ink-blue garden ledger | PASS |
| Motion | no auto motion; tactile transitions only | static | tactile only | PASS |
| Contact | mailto only | direct contact route | mailto only | PASS — shared primitive, not material pattern |

**Similarity result: 0/10 material-pattern hits.**

**Reviewer revision request addressed 2026-08-31. Pending independent re-review. Do not edit customer-visible HTML/CSS/JS until this becomes PASS.**

## Direction-level rebuild — Full-page Visual Storyboard

**Status:** `FAIL — REDESIGN DIRECTION` replaces the prior one-image architecture. The rebuilt page must create five non-repeating visual beats; no two primary sections may be text-only.

| Beat / section | Visual task and composition | Fact mapping | Asset / rights boundary | Mobile crop / motion purpose |
| --- | --- | --- | --- | --- |
| Hero space | Existing wide, quiet prepared interior; copy left, space/right | Aberdeen decorating and finish-led craft | IMG-01 original concept, not Decorum work | right-side room remains visible; no auto motion |
| Service field | Three unequal full-bleed images: wallpaper, paint detail, kitchen cabinet surface | wallpapering, preparation, kitchen respray | IMG-02/03/04 original concepts, no person/property claim | each becomes an editorial vertical panel; hover only |
| Prep method | Horizontal process still: mask, sand, protect, roll | repair-led preparation and Ames taping | IMG-05 original concept, no named materials/project | crop stays on tools and surfaces; no auto motion |
| Proof / work language | A two-image diptych: wall/woodwork detail and kitchen spray finish | Decorum’s verified service types, not a claimed customer result | IMG-06/07 original concepts; labelled only by surrounding generic service language | portrait cards stack; no before/after claim |
| Closing space | Calm, completed-but-unidentifiable interior with an open contact panel | free-quote invitation | IMG-08 original concept; no completed Decorum project claim | picture becomes a low-height final frame; CTA stays readable |

**Visual distribution rule:** Hero, service, method, proof and closing each receive one unique asset or asset pair. The same file must never serve more than one placement. All generated images remain internal `concept imagery` in the ledger and never appear with an on-page AI/rights disclaimer.

## Rebuild reference check — full-page visual sequencing

| UK reference | Full-page visual lesson retained | Deliberately not copied |
|---|---|---|
| [Hampstead Painting Company gallery](https://hampsteadpaintingcompany.co.uk/gallery) | Alternates work imagery with concise service context rather than relying on a single hero. | Its branding, project images, copy and gallery layout. |
| [Just Decorating gallery](https://justdecorating.co.uk/gallery.html) | Lets multiple rooms and surface details carry the service understanding. | Its image selection, testimonials and page styling. |
| [JC Decorators gallery](https://www.jc-decorators.co.uk/gallery/) | Uses an image-led project rhythm before a contact decision. | Its navigation, imagery, copy and brand expression. |

### Rebuild selection

The selected composition is a five-beat editorial sequence: full-bleed recognition hero, asymmetric service triptych, preparation split, before/during/after proof collage, and a separate closing-room CTA. It creates five distinct visual jobs and four layout families. Each file has a unique placement and is recorded in `docs/IMAGE_LEDGER.md`.

### Skills receipt — rebuild

- `website-delivery-sop`: its visual-completion and independent-QA gates triggered this direction-level restart and the required full-page evidence.
- `design-taste-frontend`: drove the editorial sequencing, asymmetric service card hierarchy, restrained palette and mobile reflow instead of a repeated generic card template.
- `media-use`: drove the local asset ledger, unique filenames/hashes, non-representation restrictions and no-reuse placement plan.
- `imagegen`: produced the seven section-specific original concept visuals added for the rebuilt storyboard.

Motion intensity remains 3: user-triggered hover and focus feedback only; no automatic animation is used, so `motion-design` is not applicable.
