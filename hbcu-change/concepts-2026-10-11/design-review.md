# HBCU Change — design review & three concepts

Reference research prepared 11 October 2026; implementation revised 12 October 2026. Recommendation: **01 / Clear path**, with the warmer imagery of **03 / Shared future** where useful.

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
| Navigation | Strong grouping and an obvious conversion destination | Sticky navigation, mobile menu and reading progress already exist | Use a short anchor menu and a clearly named discussion action; no need for a commercial mega-menu |
| Composition | Large focal media balanced with shorter text blocks | Many substantial text sections and repeated benefit summaries | Alternate one wide scene, one split composition and one compact comparison; vary the rhythm |
| Colours | Neutral space makes the action accent meaningful | Navy `#0D395C`, green `#28C574`, near-white `#FAFAFA`, mint surfaces | Keep this identity. Use green selectively; use navy text on bright green rather than white small text |
| Typography | Clear distance between display, supporting copy and interface labels | Embedded variable Manrope; large responsive headings; small visual labels | Retain the wording; distinguish the concepts through Outfit, Satoshi with Manrope fallback, and Newsreader with Geist. Keep explanatory text readable |
| Imagery | Media explains either a product action or a human outcome | Conceptual community photography and school artwork are already embedded | Use the supplied campus illustration consistently, then show a school’s next action through an explicitly illustrative record |
| Product presentation | Media makes otherwise abstract capabilities understandable | Clickable journey, reporting tabs and school identity switch are already useful | Elevate one journey example earlier; reduce surrounding repetition; use readable fictional records |
| Surfaces and details | Consistent corners, borders, shadows and icon treatment | Good design tokens, but many later CSS overrides complicate maintenance | Use one small radius scale per concept, one shadow family and one authoritative responsive rule set |
| Calls to action | Clear distinction between taking action and learning more | Several long action labels compete for attention | Retain “See how the work would connect”, “See the costs” and “Questions for our next conversation” |
| Credibility | Concrete proof appears near the relevant promise | Four schools over eight months; honest qualifications and illustrative labels | Retain supplied context in the explanatory copy. Add approved real school examples later; do not fabricate testimonials or add hero proof badges |
| Motion | Demonstration is a useful role for movement; exact reference behaviour unverified | 300ms entries, 150ms transitions, scroll reveals and a timed workflow are present | Use the requested GSAP scroll treatments with global pause and static reduced-motion endpoints. Keep typography strips pausable and native scrolling intact |
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

## Three revised directions

### Clear path — recommended

A full-width conversational headline leads into an asymmetric campus scene. A dense introduction explains the current situation, the platform, and what I would set up. The school journey expands horizontally on desktop; reporting uses a pinned heading and the rollout cards stack as the reader scrolls. Outfit pairs navy `#0D395C` with restrained green `#246B46` on cool, pale green surfaces. This remains the clearest direction for discussing the proposal with the team.

### In the flow — immersive demonstration

A wide opening sits above an editorial split of explanatory copy and a campus scene. The dark navy `#102B37` canvas remains consistent throughout, with pale mint `#9ECBAC` accents. Satoshi loads from Fontshare when connected; embedded Manrope preserves an offline fallback. Image scale/fade and word-by-word scroll emphasis support the demonstration. The horizontal school journey and a pausable strip of actual work categories make this the most animated direction.

### Shared future — editorial and human

A centred, expansive opening and large campus illustration lead into an asymmetric explanation. Newsreader display type pairs with Geist body text on warm paper `#F4F2E9`, with restrained green `#38694D`. Small images sit within school-identity typography. The school selector remains vertical; reporting headings pin and rollout cards stack on suitable desktop screens. The closing stays in the warm palette. This is the most editorial direction.

## Included behaviour and review limits

All three retain the original headline, first-person proposal voice, school identity switching, a four-step example with play/pause, and the $97/$107 cost comparison. FAQs are now visible question-and-answer rows. The discussion agenda is an in-page carousel with an optional full list. No form sends information and no system migration occurs.

The package includes an interactive comparison viewer, the unchanged original, three standalone concept pages, this reference analysis, revision self-review, privacy/review notes, a 404 page, and dependency notices. Core imagery, JavaScript and fallback fonts are embedded. Studio alone optionally requests its Satoshi font from Fontshare.

The viewer’s 390px mode is a comparison aid. Automated DOM interactions, GSAP lifecycle, palette contrast calculations and headline font metrics passed. Browser screenshots, real rendered overflow, screen-reader experience and real-device performance remain unverified because the supported browser tool was unavailable. See the revision self-review for exact evidence and limits.
