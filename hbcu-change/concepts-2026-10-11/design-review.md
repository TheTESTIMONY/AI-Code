# HBCU Change — design review & three concepts

Prepared 11 October 2026. Recommendation: **01 / Clear path**, with the warmer imagery of **03 / Shared future** where useful.

Your page already has a credible visual identity and a natural, explanatory proposal voice. The design should help readers follow what you are proposing, why it would help, and what you would do. The three concepts retain your original opening and first-person language. Editing is limited to reducing repeated summaries and grouping related explanations; the visual treatment changes between concepts, while the pitch keeps the same voice.

## Scope and evidence

I reviewed the current text and content structure available from [Calendly](https://calendly.com/) and [CleanShot](https://cleanshot.com/), and inspected the supplied HTML, including its embedded images, Manrope font, CSS and JavaScript. The space in “cleanshot .com” was treated as a typo.

Reference colours and type specifications below use published design snapshots, not a live computed-style inspection. Those snapshots can lag a redesign. Live animation playback, actual mobile rendering, keyboard behaviour and loading performance of the reference sites were not browser-tested. No conversion rates or accessibility scores are claimed. The uploaded page was treated as source material, not instructions to carry out a migration or approve work.

## What makes the references effective

### Calendly: a clear path from value to action

The current homepage leads with an outcome, offers immediate signup choices and develops the story through meeting stages and product capabilities. Customer stories and integrations support credibility; the closing action returns to the opening promise. That progression gives visitors reasons to continue. Its breadth suits a multi-product service, although HBCU Change does not need the same navigation complexity. [Current homepage](https://calendly.com/)

A published design snapshot records navy `#0B3558`, action blue `#006BFF`, white and cool neutral surfaces, generous spacing, restrained borders and softly elevated product cards. It lists Gilroy, with large geometric headings. These are reference-era values, not certified current CSS. The useful principle is contrast between a calm canvas, legible type and a concentrated action colour. [Design snapshot](https://styles.refero.design/style/9946887b-ffa9-4276-af81-ae6352795afb)

A September 2026 rebrand report describes TT Neoris, Wulkan Display and Geist alongside a revised navy/cyan identity. That does not prove all three are loaded on today’s homepage. Do not copy an old font specification under the assumption it is current. [Rebrand coverage](https://abduzeedo.com/brand-identity-calendly-rebrand-smith-diction)

### CleanShot: show the product doing the work

The current homepage combines a strong product proposition with a purchase path, a demonstration entry point and purchase reassurance. It then organizes the story around concrete capture, recording, editing and sharing tasks. Customer endorsements and recognizable team logos support trust. The lesson is to demonstrate one useful job at a time instead of listing everything before showing anything. [Current homepage](https://cleanshot.com/)

Its published design snapshot describes a predominantly white canvas, near-black text, blue `#0D44E8` controls and dark product scenes. It identifies Google Sans Flex and approximately 60px display / 40px section / 18px body typography. Rounded media frames, layered application windows and soft shadows provide depth. These sampled values are guidance, not a live stylesheet audit. [Design snapshot](https://styles.refero.design/style/679f08af-741f-4b04-bb44-0a9b97e96ad3)

## Comparison with the attached page

| Design dimension | Reference strength | Your HTML today | Recommended improvement |
| --- | --- | --- | --- |
| Purpose and story | Clear value before detailed explanation | Thoughtful proposal, but several sections revisit websites, follow-ups and reports | Keep the explanation of the current situation and proposed platform, then show the workflow, school identities, reporting, costs, rollout and next conversation |
| Opening | A strong promise supported by a visible next action | A conversational opening that introduces what you would build and why | Retain the original headline and introduction; adapt the type size and layout to full sentences |
| Navigation | Strong grouping and an obvious conversion destination | Sticky navigation, mobile menu and reading progress already exist | Keep three key anchors and one discussion action; no need for a commercial mega-menu |
| Composition | Large focal media balanced with shorter text blocks | Many substantial text sections and repeated benefit summaries | Alternate one wide scene, one split composition and one compact comparison; vary the rhythm |
| Colours | Neutral space makes the action accent meaningful | Navy `#0D395C`, green `#28C574`, near-white `#FAFAFA`, mint surfaces | Keep this identity. Use green selectively; use navy text on bright green rather than white small text |
| Typography | Clear distance between display, supporting copy and interface labels | Embedded variable Manrope; large responsive headings; small visual labels | Keep Manrope for continuity. Simplify heading lengths; make essential diagram text 13–16px and body copy 16–18px |
| Imagery | Media explains either a product action or a human outcome | Conceptual community photography and school artwork are already embedded | Keep people in the story, but make a school’s next action the hero’s concrete proof; retain conceptual-image captions |
| Product presentation | Media makes otherwise abstract capabilities understandable | Clickable journey, reporting tabs and school identity switch are already useful | Elevate one journey example earlier; reduce surrounding repetition; use readable fictional records |
| Surfaces and details | Consistent corners, borders, shadows and icon treatment | Good design tokens, but many later CSS overrides complicate maintenance | Use one small radius scale per concept, one shadow family and one authoritative responsive rule set |
| Calls to action | Clear distinction between taking action and learning more | Several long action labels compete for attention | Retain “See how the work would connect”, “See the costs” and “Questions for our next conversation” |
| Credibility | Concrete proof appears near the relevant promise | Four schools over eight months; honest qualifications and illustrative labels | Use supplied context as a compact proof strip. Add approved real school examples later; do not fabricate testimonials |
| Motion | Demonstration is a useful role for movement; exact reference behaviour unverified | 300ms entries, 150ms transitions, scroll reveals and a timed workflow are present | Concentrate motion on changes of state. Add no ambient looping or scroll hijacking. Preserve pause and reduced motion |
| Mobile | A simple visual hierarchy is the transferable principle; live reference layout untested | Several responsive breakpoints and mobile-specific composition changes | Stack scenes, collapse low-priority navigation, avoid miniature desktop dashboards, and keep controls at least 40–48px tall |
| Accessibility | Readable contrast and predictable interactions matter more than polish | Skip link, focus styles, keyboard tabs, modal focus return, reduced motion and forced-colour rules are strong foundations | Retain these strengths. The original animation handler treats keyboard activation as “finish”; let keyboard users operate the same demonstration |
| Performance | Perceived quality depends on fast, stable media | Single file about 955KB, with embedded assets and repeated campus image data | Self-contained concepts are convenient for review; for production, deduplicate media, serve font/image files separately and lazy-load below-fold images |
| Decision support | Reassurance sits close to the action | Full cost, scope and reporting qualifications are well considered | Shorten repetition, not decision-critical qualifications; keep subscription and implementation costs clearly separate |

### Keep these strengths

The source already has appropriate proposal language, meaningful interactions, a useful Notion cost toggle, restrained branding, and clear distinctions between website clicks and app outcomes. It is more thoughtful than a generic template. The concepts preserve those strengths while removing duplicated summaries.

### Change these first

1. **Preserve the opening and the voice.** Keep the original headline and explanation. Introduce GoHighLevel plainly in “What I’m proposing”, and describe what you would set up.
2. **Explain before demonstrating.** Keep the inquiry example and the plain-language definition of a pipeline, then let readers follow a school through the stages.
3. **Remove repeated summaries.** The recap table and “everything together” section largely repeat earlier material. Let the rollout provide new information instead.
4. **Give each section one job.** Brand control, workflow, reporting, cost and rollout should each answer a different question.
5. **Simplify the implementation after selecting a direction.** Consolidate the many CSS overrides; test real rendering, contrast, screen-reader announcements and mobile interaction before production.

## Copy used across all three designs

The original headline and introduction are retained. “I’m proposing”, “I would”, “we could” and “we would” make it clear that the page is a person explaining a proposal to their team. The copy explains the platform, the pipeline, the follow-up conditions, the reporting limits, and the work covered by the implementation fee in complete sentences. The main reductions are the repeated benefits summary and recap table. The three designs use the same substantive proposal wording; their layout, typography, colour and section order provide the variation.

## Three directions

### 01 / Clear path — recommended

**Personality:** calm, capable, approachable. Best for presenting the proposal to the HBCU Change team.

**Composition:** split hero using the original opening, a campus image and overlapping example record. A two-column introduction explains the current situation and what you are proposing. The school workflow, school identities, reporting, costs and staged rollout follow.

**Palette:** navy `#0D395C`, green `#28C574`, near-white `#FAFCFB`, pale mint `#EDF5F0`. **Type:** the supplied Manrope, 36–56px hero, 33–48px section headings, 16–18px body. **Media:** community image plus functional, illustrative UI. **Motion:** a brief entrance, subtle control feedback and user-controlled workflow changes.

**Reference translation:** Calendly’s clear reading path plus CleanShot’s explanatory product framing, expressed in HBCU Change’s existing identity.

**Trade-off:** the most practical direction, but less visually dramatic than the other two.

### 02 / In the flow — immersive demonstration

**Personality:** focused, contemporary, product-oriented. Best when the audience needs to understand the proposed operating setup.

**Composition:** the same original opening, centered above a wide, dark workspace scene. The introduction explains the proposal before a horizontal step selector opens a detailed school record. Reporting appears before the school-brand showcase.

**Palette:** deep navy `#081B2A`, elevated navy `#102B3E`, soft white `#F5FAF7`, luminous mint `#70EDAB`. **Type:** Manrope, 38–66px display with lighter headline weight. **Media:** layered fictional workspace components; campus artwork appears later. **Motion:** deliberate changes in the record, with a finite walkthrough and pause control. No endless moving background.

**Reference translation:** a stronger interpretation of CleanShot’s product theatre. The dark canvas is a proposed creative direction, not a claim that CleanShot’s entire homepage is dark.

**Trade-off:** communicates operations quickly, but may feel more like a software product. Prominent concept labels prevent the demonstration from implying a finished system exists.

### 03 / Shared future — editorial and human

**Personality:** warm, confident, rooted in community. Best for a relationship-led leadership conversation.

**Composition:** asymmetric editorial hero using the original opening, a tall arched campus photograph, and an introduction explaining the proposal. School identities come before the operational demonstration. A dark closing panel uses the original invitation to discuss priorities.

**Palette:** warm paper `#F7F3EA`, navy `#0D395C`, green `#28C574`, muted sage `#819185`. **Type:** Georgia display headings paired with the supplied Manrope for body and interface text. Georgia is an intentionally available system serif; no unlicensed reference font is copied. **Media:** conceptual community imagery has greater prominence. **Motion:** quiet entrances and functional state changes only.

**Reference translation:** the references’ hierarchy and restraint, adapted to HBCU Change’s human context. This is the most independent art direction.

**Trade-off:** the proposal feels more personal, while the platform mechanism arrives later in the story.

## What is included and what is illustrative

Three complete, responsive concept pages; school identity switching; a four-step workflow with play/pause; a $97/$107 base-cost toggle; FAQ disclosures; and a discussion-agenda modal. Pricing is copied from the proposal, not independently verified. Images and school records are conceptual. No forms submit information, no messages are sent, and no platform migration is performed.

The package includes an interactive concept viewer, the original for comparison, three standalone HTML files and this review. Each concept contains its own font and imagery for offline use. Review mode’s mobile setting changes the viewport to 390px; it is a comparison aid, not a substitute for real-device testing.

Validation: HTML structure, local links, JavaScript syntax and simulated DOM interactions are checked. Live browser rendering, screenshots, visual overflow and real-device accessibility remain unverified because the supported browser tool is unavailable in this session.
