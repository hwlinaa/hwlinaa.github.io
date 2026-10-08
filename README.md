# David Hin Wang Lin

Static trilingual academic website adapted from Jon Barron’s supplied source template, with format and wording references from Jacky Li’s website.

## Standard
- 800px maximum reading width; Lato with Chinese system-font fallbacks, 1rem body (16px at the default browser setting), 1.6 line-height (1.65 for Chinese), 2rem name and 1.5rem section headings. Publication metadata stays at .875rem. A 184px desktop contents column plus 32px gap sits beside the reading column at viewport widths of at least 1080px.
- Original blue links (#1772d0); dark-orange hover/focus (#9d4b00) with underlining and a visible keyboard focus ring. Their white-background contrast ratios are 4.82:1 and 6.10:1. Research images remain 160px and all paper rows use the same white background.
- Full author lists with Hin Wang Lin in bold. Equal-contribution marks only when verified.
- Slash-separated resource links. No middle-dot separators or personal copyright footer.
- Footer: Webpage template adapted from Jon Barron and Jacky Li.
- Additions: Traditional and Simplified Chinese pages, grouped Education with HKUST logo, responsive layout and keyboard focus.
- No analytics, JavaScript dependencies or build step. CV is withheld pending revision.

## Files
- index.html: English homepage
- zh.html: Traditional Chinese homepage
- zh-hans.html: Simplified Chinese homepage
- style.css: template fonts and proportions, with documented responsive and accessibility refinements
- robots.txt: crawl instructions and sitemap location
- sitemap.xml: the three public language pages
- CV source and PDF are archived outside the publication directory pending revision.

Preview: `python3 -m http.server 8000 --bind 127.0.0.1`

## Asset provenance
- Template: https://jonbarron.info/ and user-supplied jonbarron.github.io-master source.
- Additional format and wording reference: https://jackyli-hkust.github.io/ and user-supplied web archive; both template references are credited in the footer.
- Portrait: user-supplied 1759303492237.png, selected on 2026-10-07; copied without image alteration.
- YLMASS crest: user-supplied image, added on 2026-10-08 without pixel alteration; displayed using the shared institution logo sizing.
- HKPF logo: https://upload.wikimedia.org/wikipedia/commons/2/2b/HKPF_logo.png (user-selected source, 2026-10-07; original PNG)
- Hong Kong Disneyland logo: https://news.hongkongdisneyland.com/app/themes/hkdlnews/assets/dist/images/hkdl-logo-color.svg (official newsroom; original SVG).
- HKUST logo: https://geco.hkust.edu.hk/files/image_2.png (replacement selected by the user on 2026-10-07; original transparent PNG)
- HKAGE logo: https://www.hkage.edu.hk/uploads/image/202403/e19ff02464500ca5a76fd79ad4588539.png (official homepage logo; the current local PNG omits the empty right margin).
- Universpirit logo: user-supplied images.png, added on 2026-10-07 without alteration.
- PierGuard: figure extracted from the author-provided final publication; DOI 10.1109/TASE.2025.3570694.
- Coastal: https://arxiv.org/html/2410.02345v1/Fig/mission_architecture.png
- MINER-RRT*: https://arxiv.org/html/2406.00706v2/Fig/show2_first.png
- WaveLander: https://arxiv.org/html/2607.01281v1/Fig/Full_visual.png
- SLOC: figure extracted from the author’s local manuscript dated 2026-03-07. This author-supplied manuscript figure has not been independently matched to the final published version.
- Figures retain their original content. Full unpublished manuscripts and private credentials are not included.

## Metadata verification
Author order checked against arXiv and HKUST Research Portal on 2026-10-07. PierGuard equal contribution follows the final IEEE PDF footnote; WaveLander equal contribution follows arXiv v1. WaveLander acceptance follows the author’s records. Source links are provided with each publication.

## Status
Public static website for https://hwlinaa.github.io/, maintained on the main branch of hwlinaa/hwlinaa.github.io (2026-10-07). The repository contains only the public static site, its assets and maintenance notes; private CV evidence and local previews remain outside it.

## Editorial review, 2026-10-07
- Keep the approved Jon Barron layout; standardize service label dimensions without adding a new visual system.
- Introduction identifies research affiliation, technical focus, co-founded business and education work; a short invitation names concrete collaboration topics.
- Use natural Hong Kong Traditional Chinese. Preserve official institution and project names.
- Added user-provided GitHub, LinkedIn and Universpirit links. No CV file is included in the publication directory.
- Current Science Talent Society role is President; earlier Chairperson terms are separate. Civil Policy Address role is Advisor since 2023-03, not an uninterrupted drafting-member title.
- Omit the unsupported “Hong Kong’s first” competition claim. Awards follow the core evidence index, including E08, E20 and E21.
- E21 lists Lin as project leader; the user chose to omit the role and display only the team gold award on 2026-10-07. The underlying evidence record is unchanged.
- Sources: user bio and portrait; main CV and core evidence index; official institute, laboratory and company sites. Research affiliations follow the user's statement; no separate institute appointment is claimed.

- Added Professional Experience after Education: HKPF Key Points and Search Division drone-team summer internship (2022-07 to 2022-08, through PMP), and HK Disneyland full-time internship in Technology and Digital (2019-06 to 2020-05). Dates and personal roles follow the main CV and user confirmation. Public sources support department names only, not personal responsibilities.
- Added NaviHK Tech Limited to the introduction and Entrepreneurship as a separate co-founded technology consultancy, starting 2025-01 according to the main CV. No unsupported project outcomes or company URL were added.

- Public Service has The Standard's 2024-08-20 feature, the HYAB experience-sharing video starting at the user-selected 0:43, and the official EDB committee list. The 2021 Outstanding Tertiary Students award links to the organiser's profile video. Videos are linked, not embedded; no complete-viewing claim is made.
- ELEC3300 identifies Prof. Kam Tim Woo as course instructor according to the user's 2026-10-07 confirmation, linking to his HKUST faculty profile. ELEC3120 is listed separately from that attribution.
- Science Talent Society links point to the official association page and user-provided Instagram. The official page's student executive chairperson listing is distinct from Lin's President role.
- Delegations & Judging links to ISEF 2025, ISEF 2026 and Geneva 2026 event coverage, plus the organiser's media centre. Reports corroborate events and delegation results, not a named personal leadership appointment. Geneva wording specifies the EDB secondary-school delegation.

## HTML and publication settings, 2026-10-07
- Static HTML remains the implementation standard: three pages, shared CSS, no build or JavaScript dependency.
- English entry: index.html, with canonical URL https://hwlinaa.github.io/. Traditional Chinese: zh.html; Simplified Chinese: zh-hans.html. Each has its own canonical URL.
- Reciprocal absolute hreflang links include en, zh-Hant, zh-Hans and x-default. Visible language links stay relative for local preview.
- Each page has one h1 for the name, retaining the original font size and normal weight.
- UTF-8, viewport, author, description, index/follow and strict-origin-when-cross-origin referrer metadata are explicit.
- Open Graph and summary-card metadata use each page’s language and the approved portrait. Public image/URL fetching requires deployment; local metadata does not confirm a platform preview.
- Sitemap contains only the three language pages. Update lastmod when their substantive content changes. No custom domain is configured; update canonical, hreflang, social URLs, robots and sitemap together if the domain changes.
- Setup follows [Google's localized-page guidance](https://developers.google.com/search/docs/specialty/international/localized-versions) and [MDN's referrer metadata reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/meta/name/referrer).
- GitHub Pages activation, publication, live-site crawling and search indexing have not been verified. Local HTML readiness does not imply deployment or inclusion in search results.
- Validation: parsed both HTML pages and sitemap, checked local resource/anchor paths, verified the English root and Chinese page in the local browser, and confirmed footer and metadata updates with no horizontal overflow at the default viewport. Preview saved outside the publication directory.

## Research image optimisation, 2026-10-07
- Research images use static WebP derivatives: lightweight previews in the page, with links to larger versions. This avoids loading full figures for 160px-wide slots without adding a script, image CDN or build step.
- Full figures are limited to a 1920px longest edge, with previews limited to 480px for sharp display in 160px slots. Smaller images are not enlarged. Aspect ratio and existing alpha channels are preserved; there is no crop or content replacement.
- MINER uses a single lossless WebP at its original 572 x 537 size, smaller than both its PNG and a separate preview. Other figures use quality 90 for full images and 86 for previews, encoded with Pillow / libwebp 1.6.0, method 6.
- Original PNG/JPEG files are SHA-256-verified and archived outside this repository before replacement. The conversion manifest and visual comparison also remain outside the publication directory.
- Portrait and institution logos are unchanged. SLOC still uses the previously selected manuscript figure; compression does not resolve its final-publication verification status.
- Five original research assets: 12,773,773 bytes; five page previews: 121,248 bytes (99.05% less). All nine unique research WebP files including larger views: 1,150,096 bytes.
- Validation: SHA-256 original backups, WebP decoding, image-only HTML changes and local paths passed. Both language pages loaded all five previews; a full-size Coastal image opened successfully in the browser. Original and compressed previews were visually compared.

## Additional research recognition and patent, 2026-10-07
- Added the team Silver Award in the China International College Students’ Innovation Competition (2025) for collaborative heterogeneous robotic marine monitoring to Selected Honors & Awards, linking to the Ministry of Education result notice (evidence E23).
- Coastal lists two recognitions for the associated project: the 14th Challenge Cup business-plan competition national-final team Silver Award (2024, E22), and the OSHC Best Project Scholarship postgraduate-category winner, presented on 2025-05-19 (E26). These are project/innovation and scholarship recognitions, not best-paper awards. The scholarship academic year is not inferred.
- Added a compact Patent section after Research: inventor Hin Wang Lin, Photosensitive Panorama Photography Device, Hong Kong short-term patent HK1224505A, gazette date 2017-08-18 (E04). The official historical gazette is linked; no current validity claim is made.
- These four additions follow the user's approval. Additional career history and business cases are deferred.

## Three-language pages and institution logos, 2026-10-07
- Traditional Chinese News heading shortened to 新聞; the Simplified Chinese heading is 新闻.
- All three pages have native-language navigation, reciprocal hreflang entries, self-canonical URLs, and matching social metadata. The Simplified Chinese page is a standalone static file, with no browser-side conversion or additional runtime dependency.
- Simplified Chinese was converted from the reviewed Traditional Chinese copy using macOS ICU, then checked for terminology. Link URLs and author lists are retained verbatim. Future content edits must be synchronised across all three files.
- Education, Professional Experience and Entrepreneurship share a fixed-layout logo column and image boxes up to 130px wide and 112px high (80px high on narrow screens), using object-fit:contain to preserve the complete logo. The initial grey-background HKUST image was superseded by the transparent PNG specified in the revision below.
- The user-selected HKUST and HKPF images replace the earlier logos. Universpirit's supplied logo links to the company website beside its existing co-founder entry; NaviHK remains a separate text entry without an invented logo. Replaced assets are archived outside the public repository.
- Validation: all three pages passed local-resource, fragment, canonical/hreflang and sitemap checks. Traditional/Simplified outbound links and full research author lists match. All four institution logos loaded, with identical column widths; desktop and 390px browser checks showed no horizontal overflow. Native language links successfully opened Simplified Chinese and English pages.

## HKAGE internship and revised HKUST logo, 2026-10-07
- Added Summer Intern, Advanced Learning Experiences Division, The Hong Kong Academy for Gifted Education, 2021-06 to 2021-08. This is an existing main-CV record, distinct from the 2021-04-17 STEM/STEAM Club guest-instructor activity. No unverified internship responsibilities or outcomes are added.
- The three language pages list internships in reverse chronological order: Hong Kong Police Force, HKAGE, Hong Kong Disneyland. HKAGE uses its official homepage logo and the same institution column.
- HKUST now uses the user's replacement transparent PNG from geco.hkust.edu.hk. The superseded grey-background JPG is archived outside the public repository; the new PNG is copied without alteration.
- A CSS display frame compensates for the HKUST PNG’s large transparent margins, so the visible emblem is closer in scale to the other logos. Source pixels are unchanged and the complete emblem remains visible.
- During validation the local HKAGE asset was found to be a 1460 x 448 version, compared with the downloaded 1920 x 448 image. It was preserved; its pixels exactly match the corresponding left region of the official source, with the complete wordmark visible.

## Additional media links, 2026-10-07
- News adds the HKUST School of Engineering report dated 2025-06-25 on the team's Information Technology Second Prize at the 11th Hong Kong University Student Innovation and Entrepreneurship Competition (E12). This is separate from the national team Silver Award already in Selected Honors & Awards. The English page uses the English report; both Chinese pages use its Traditional Chinese counterpart.
- Entrepreneurship links to the GBA Infinity UAV profile published on 2022-07-07 (M10). It is a historical profile, not a claim about current business results. Full-video and complete-subtitle review remain incomplete in the private evidence log.
- Public Service uses the Sing Tao promotional interview (M06, 2024-08-23) on the Chinese pages and retains The Standard's English feature. All three pages add Wen Wei Po's community-visit report (M03, 2021-10-11).
- These are links to existing source pages, with no embedded videos or third-party tracking scripts.

## Repository housekeeping, 2026-10-07
- Ignore operating-system metadata, editor files, temporary files, local environment secrets, working materials and generated caches.
- Remove the previously tracked .DS_Store from Git's index while retaining the local file. Stage only the public HTML, CSS, assets, crawler files, README, .gitignore and .nojekyll.
- Validation: three language pages passed local-path, fragment, media-placement and chronological-order checks; desktop and 390px browser checks showed no horizontal overflow. Full publication dates stay together in resource links. Research, institution entries and selected awards are preserved.


## Navigation, copy and structured data, 2026-10-08
- Approved order: About and contact, Research, Patent, Education, Professional Experience, Entrepreneurship, Teaching & Service, Selected Honors & Awards, News. Existing public-service anchors remain valid.
- Use semantic navigation and native fragment links. The desktop contents column uses CSS sticky rather than a fixed overlay; below 1080px it becomes a native details/summary disclosure. No JavaScript, scrolling library or build dependency is required. Keep both menus and all three language files in sync when sections change.
- Introductions identify the PhD affiliation and advisor, then the research institute/laboratory and technical focus, following the user-approved revision below. The email address is displayed in full with a mailto link. The portrait is unchanged.
- Universpirit's description identifies school audiences and the course series without inventing a cumulative customer/student count. NaviHK remains a technology consultancy because specific client projects and deliverables are not established in the source CV.
- Youth Education now explains Talent Cup's organiser/co-organiser, the author's fixed-wing challenge design for editions 8 and 9, and edition 8's event-wide participation (36 schools, 755 teams, 2,265 students), supported by the existing R01 evidence record. These are competition totals, not Universpirit customers or the author's personal teaching reach. The unsupported “Hong Kong’s first” claim remains excluded. The organiser's source page is linked; a new full-page retrieval on 2026-10-08 failed, so this update relies on the existing verified evidence record.
- ISEF is expanded to Regeneron International Science and Engineering Fair at first mention. The 2024/2025 national innovation awards use matching year, track and team-award wording. The 2024 award links to the Ministry of Education notice at https://www.moe.gov.cn/srcsite/A08/s7056/202504/t20250418_1187857.html; the existing official award-list evidence supports the result.
- Each page includes static ProfilePage JSON-LD with a Person mainEntity and the same absolute person identifier. Names, public contact, research topics, HKUST affiliation/alumni relationship and GitHub/LinkedIn links reflect visible page content. JSON-LD helps describe the person; it does not guarantee search ranking, indexing or AI citation.
- References: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/position ; https://www.w3.org/WAI/tutorials/page-structure/regions/ ; https://developers.google.com/search/docs/appearance/structured-data/profile-page ; https://schema.org/Person

- Validation: all three pages passed structural nesting, unique IDs, local resources, fragment targets, canonical/JSON-LD agreement and sitemap parsing. Five paper entries, seven awards, institution records and every existing external link were preserved. Browser checks at 320, 390, 768, 1079, 1080 and 1280px showed no horizontal overflow; desktop anchors/sticky positioning and mobile keyboard disclosure/navigation worked. JSON-LD was validated locally, not through Google's Rich Results Test or Search Console. This batch has not been committed or pushed.


## Introduction wording and secondary-school affiliation, 2026-10-08
- Traditional Chinese uses the user's exact approved introduction, with institution links retained. English and Simplified Chinese follow the same affiliation-to-research sequence.
- Education adds Yuen Long Merchants Association Secondary School below HKUST, Forms 1–6, 2011-09 to 2017-08. Dates follow the user's main CV and explicit approval; no additional qualification or alumni-association appointment is inferred.
- The supplied school crest is stored as assets/ylmass.png without image alteration, using the same contain sizing as the existing institution logos. The crest and school name link to https://www.ylmass.edu.hk/web/, verified as the official school homepage on 2026-10-08.
- Person JSON-LD includes the school as a HighSchool entry alongside HKUST in alumniOf; the university affiliation remains unchanged. This revision is local and has not been committed or pushed.

- Validation: Traditional Chinese introductory text matches the approved sentence exactly; all three education entries and alumniOf JSON-LD passed local checks. The crest loaded on desktop and all three pages had no horizontal overflow at 390px. Existing papers and award contents are unchanged.


## Five additional public records, 2026-10-08
- Added all five records approved by the author across the three language pages, using the existing main CV and evidence index.
- News adds the Sing Tao interview on mainland car rental and driving (2024-04-01, M05) and the China Youth Daily interview on maritime rescue UAV development and the Challenge Cup (2019-11-14, M15). Both are linked as interviews; the rental article is not presented as an engineering achievement. The website and daily editions of M05 remain one interview.
- Education links to Oriental Daily's coverage of the author's secondary-school panoramic camera invention (2016-09-30, M18). The article's main tree-bandage headline concerns other students and is not attributed to the author.
- Youth Education adds the talk to 70 Form 6 students at HKFEW Wong Cho Bau Secondary School on 2024-11-08 (M14). This is the activity date; the source report was published on 2024-11-14. The English school name was cross-checked against its official School Profile.
- Delegations & Judging adds Universpirit Innovation's special award at the 26th Hong Kong Youth Science and Technology Innovation Competition, the author's award-panel judging role and prize presentation on 2024-03-24 (E48). The date refers to presentation, not an unverified judging date. This is company support and personal service, not an award received by the author or evidence of a personal donation.
- Source status: M05's article was read on 2026-10-08. New direct retrieval of M14, M15, M18 and the E48 review failed; existing evidence records remain the basis. Search results for the official E48 review and entry guide corroborate the event and company award, not a named individual judging appointment. No stronger verification claim is made.

- Validation: all three pages passed HTML nesting, unique IDs, local assets, fragment targets, five added source links and descending News dates. Existing papers, awards, structured data and all previous links are preserved. A 1280px desktop view and 390px views of all three languages showed no horizontal overflow. This revision has not been committed or pushed.

## Apple Design foundation pass, 2026-10-08
- User approved readability, contrast, spacing, heading hierarchy, contents navigation and keyboard refinements. Preserve approved copy, author lists, images, section order, links and trilingual metadata.
- Source: dickwu/apple-design-skill, commit 904b0eedc7cc778152f545506075d5bb5219ce77; installed separately under ~/.codex/skills/apple-design. Apply its web-relevant foundations, not native Apple app conventions.
- Compared a full visual/framework rebuild with a shared-CSS refinement. Selected the latter: no additional runtime, build process, JavaScript or downloaded visual assets, with one stylesheet serving all three languages.
- Standards: named CSS color roles; relative font sizing; 16px default body; 24px section headings; consistent 12/16/28px content spacing; 44px minimum contents targets; native details and anchors. Anchor destinations accept programmatic/native fragment focus without adding extra Tab stops.
- Existing white appearance and academic identity remain deliberate. No native app chrome, glass layer, dark appearance or animation is introduced. Existing optional figure transitions honor prefers-reduced-motion; prefers-contrast:more increases text and link contrast.
- Reference basis: accessibility.md > Vision / Mobility; layout.md > Visual hierarchy / Adaptability; typography.md > Ensuring legibility / Conveying hierarchy / Supporting Dynamic Type; color.md > Inclusive color; focus-and-selection.md > Best practices; branding.md > Best practices. Web contrast and reflow are checked against W3C WCAG 2.2, not native point-size thresholds.
- Verification sequence: preserve a SHA-256 baseline; compare text, links and assets; inspect desktop and narrow layouts in all languages; exercise contents and keyboard focus; inspect a doubled-text fixture; save preview screenshots outside the public repository.
- Verification result: all three languages passed 1280px, 768px, 390px and 320px overflow checks; images had no load failures. Separate 200% root-font fixtures (not browser zoom or a screen-reader audit) passed at 1280px, 390px and 320px, with no measured text-container overflow. Native language links and keyboard-operated mobile contents were exercised; fragment navigation moved focus to the chosen destination. Focus retained a 2px outline and underline. Text and resource URLs match the pre-change files exactly after excluding the new tabindex attributes.
- This pass is local only; no commit or push was performed. Screenshots and test fixtures are stored outside this public repository.

## Chinese contents labels, 2026-10-08
- Desktop and mobile contents use two-character labels in Traditional and Simplified Chinese: 簡介、研究、專利、學歷、經歷、創業、服務、獎項、新聞.
- Full section headings, anchor destinations and English labels are unchanged. Both contents menus in each Chinese page contain nine valid links.
