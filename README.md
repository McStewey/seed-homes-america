# Seed Homes America

Unpublished architectural brochure review, October 12, 2026.

Open `index.html` for an offline-capable layout review, or serve this directory with any static HTTP server. The live local review URL is http://127.0.0.1:8765/ while the preview process runs. No build, package installation, framework, API keys or backend are required. Suitable for a later GitHub Pages deployment after source visibility and content review. Nothing has been published.

## Included

- Custom SVG America logo inspired by the Canadian leaf-and-home mark; a proposed mark for review, not a supplied official logo.
- Cinematic featured-home presentation for Studio, Fairview and Haven, scroll transition from full architectural image to a paired plan panel on desktop, stacked mobile presentation, conceptual fold controls, finished-home section and Seed story.
- Six model detail dialogs, sorting, source brochure links and source plan viewer.
- Contractor model/category/document selectors and original Drive previews. Existing sharing settings are unchanged. No construction PDF copies are bundled.
- Wade Stewart and Casey Colton's confirmed contact links; inquiry email preparation via the visitor's email app and a local text download. No automatic sending, storage, analytics or form backend.
- Reduced-motion CSS, reduced-motion fold behavior, native keyboard controls, focus return from modal, skip link, labeled inputs and mobile menu.

## Source choices and open issues

Following the user's direction to use the supplied folders, marketing areas come from the individual brochures in the SEED Info folder, rather than the earlier local lineup or Canadian homepage:

| Model | Brochure area | Brochure layout information |
|---|---:|---|
| Studio | 420 sq ft | Open living space and 1 bathroom; selected drawing has no separate bedroom |
| Parkview | 588 sq ft | 1 or 2 bedroom options, 1 bathroom |
| Nook | 820 sq ft | 2 bedrooms, 1 bathroom |
| Fairview | 918 sq ft | 2 bedrooms, 1.5 bathrooms, optional office |
| Cove | 1,100 sq ft | 2 bedrooms, 2 bathrooms, optional office, flex room shown |
| Haven | 1,188 sq ft | 2–3 bedroom options, 2 bathrooms, bonus room/office claims in brochure |

These are source-attributed marketing values, not an independent dimensional certification. Sources conflict: the selected Studio drawing is approximately 24 by 17 feet and the Haven drawing explicitly says 1,179 sq ft. Fairview's brochure office is absent from the selected technical layout. The site does not claim these drawings and renderings show an identical revision. Resolve applicable model revisions before replacing the source notes with final U.S. specifications.

Architectural imagery was extracted from the supplied `SEED-Homes-Curb-Appeal-Lineup-6-Models.pdf` and cropped above its baked-in captions, retaining the original rendering pixels. No AI alterations were made. Renderings show illustrative landscaping, decks and finishes; they are not inclusion schedules.

Fairview's visual marketing plan comes from its brochure. Technical layouts were visually inspected for Studio (SH00015 rev 1, July 22 2024), Fairview (SH00110 rev 1, January 21 2025), and Haven (SH01-ARC-00165 rev H, January 14 2026). Studio and Haven sheets contain private client/site details; they remain remote originals behind existing Drive controls. Other selected technical documents are inventoried references, not individually engineering-reviewed. Site reports, ERP reports, energy site reports and the Kraft Creek package are excluded.

Before public deployment, replace project-specific layouts with approved public marketing plans and review every document link for permitted audience and applicability. Leaving a Drive link in a public page can reveal its existence even though permissions remain unchanged. Do not deploy this review package unchanged.

The fold demonstration is deliberately conceptual, not a model-specific assembly simulation. The Canadian homepage and ModMax visual design were inspected. The manufacturer-linked Kerry Tarnow video initially stalled, then played crane-assisted folding footage; it does not validate the site's demonstration geometry. No ModMax partnership/endorsement, pricing, financing, service region, performance guarantee or warranty claim is made.

## Sources

- Supplied Drive root: https://drive.google.com/drive/folders/1vBmP98idQetLO47rYU-gTnpzirrLZYhD
- Model brochures: https://drive.google.com/drive/folders/1GSNBwRyZcQ3uWhRmPY72YaMbewMIbdYh
- Canadian brand/story/video reference: https://seed-homes.com/
- Manufacturer-linked video: https://www.youtube.com/watch?v=usKL9C9bGlw
- Secondary visual reference: https://www.modmax.com/
- Individual brochure and drawing links are preserved in `app.js` and `documents.js`.

The old generic Website Seed Planning document was disregarded.

## Validation

Passed: JavaScript syntax checks; HTTP 200; no broken loaded local images; all six model dialogs; featured-model switching; descending model-area sort; contractor model/category filtering; accurate selected source URL; unavailable-package empty states; Drive PDF loading in this session; native plan zoom controls; fold range reaching expanded state; mobile menu opening and closing; mobile width 390 px without horizontal overflow; and an actual inquiry text-file download with success feedback. Desktop and mobile screenshots accompany this package.

Reduced-motion behavior was reviewed in CSS and JavaScript, not tested with an emulated OS preference. Browser console inspection showed no errors at the inspected stage. This is functional review, not a complete accessibility audit. The email/telephone targets were checked; no email or call was sent. After contacts and source values changed, all six dialogs and rendered area/contact targets were checked again.

Google Fonts are requested with local serif/sans-serif fallbacks. Google Drive requires network access and may require sign-in for other visitors. Private/incognito access was not tested and sharing was not expanded.


## Revised review
Navigation now uses separate Home, Homes, Contractors, U.S. Info and Contact views. Home cycles the six supplied architectural renderings with a pause control and reduced-motion support. Contractors retains the exterior-to-plan study and adds six consistent model resource panels, each with a boxed category control. Parkview, Nook and Cove show supplied brochures pending technical packages. Canadian website links and origin-story copy have been removed from visitor-facing pages. The side-view folding illustration stages floor lowering before accordion wall movement; it remains conceptual, not verified installation geometry. No publishing or Drive permission changes.

Each contractor model now defaults to Model brochure, with available general layouts and technical disciplines following. The opening exterior study also starts with its model brochure.

Opening model tour alternates warmer/lighter and darker/cooler renderings: Haven, Cove, Fairview, Nook, Parkview, Studio, then repeats. Manual selection keeps playback position aligned.
The opening tour now intersperses a six-model collage after each pair of contrasting individual homes.
Opening individual images and collage tiles preserve the full supplied frame rather than cropping to fill. Desktop places the architecture beside the introduction; mobile keeps a full-width view below the copy. Zoom motion removed.

The opening has been shortened, with each model title placed directly on the image and the exploration action over the lower edge. Full architectural framing is preserved.

Folding study now ends with a roof placement stage after floor lowering and wall unfolding. Roof geometry and placement remain illustrative, not model-specific installation instructions.

## Why SEED copy sources
Opening story replaces Considered spaces / Everyday possibility. Headline adapted from supplied SEED Homes Pitch Deck.pdf and SEED_Final_Investor Deck.pdf mission language: the world changed; housing did not. Product narrative cross-checked against Homes by SEED 2026, steel frame system sheet, local SEED-DECK-8.6 quality page 15, and seed-homes.com story (research only, no visitor link). No Canadian origin or affiliate claims added. Older deck numeric fire/wind assertions were not carried into visitor copy because underlying assembly tests and site-specific engineering were not established. No investor financials published.

Large heading spacing refined across Homes, Contractors, Why SEED, Info, Contact and folding study. Removed forced breaks where they wasted heading width, tightened section padding, and arranged Why SEED heading beside its short story on desktop.

## Public preview
Published to GitHub Pages at the user's request. This remains a design review; source document permissions are unchanged.


## Custom Homes
Standalone Forged Steel Custom Homes section. All imagery is local; no outbound Forged website links, remote images or embedded website. Uses the user-supplied Forged Industrial Collection draft (16 pages) for the industrial homestead story and four concept images. Embedded original image pixels were extracted and cropped to remove brochure borders and typography; no AI regeneration needed. Ranch I, Ranch II, Ranch III and Mod Industrial names follow the draft. Draft dimensions are omitted pending final design confirmation. The existing supplied website provided the local interior concept. All inquiries stay with Wade/Casey. No ratings, warranties, approvals, price or delivery promises added.

### Updated collection comparison
Compared Forged Collection_8-13-26.pdf (23 pages) with the Industrial Collection draft and current site. Selected its clean original sunset ranch image for the feature, added Two Story Ranch and Bunkhouse concepts to extend the gallery to six, added its illustrative two-floor layout to the local viewer, and replaced the interior feature with a warmer lakeside living image. The origin story follows its tree-fort inspiration and barn utility themes. Images were extracted directly from embedded PDF assets without regenerated architecture. Three-bedroom and two-/three-bedroom descriptions are concept options from pages 9/10 and 13, not confirmed product specifications. Commercial material is outside this residential section. Marketing performance claims were not expanded into certified ratings or promises.
