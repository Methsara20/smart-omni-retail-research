# Smart Omni-Retail System - Academic Research Website

Academic information website for SLIIT research group **R26-IT-060**, Sri Lanka.

## Purpose
Present four integrated research functions: inventory optimisation, personalised marketing, virtual try-on and sizing, and customer behaviour intelligence. This website explains the research and does not implement the retail application.

## Technology restrictions
HTML5 and CSS3 only. No JavaScript, frameworks, external fonts, UI libraries, build tools, npm dependencies, backend or database. Inline SVG icons and CSS diagrams require no external requests. Flutter, FastAPI, MongoDB and Firebase Authentication refer to the research product, not website dependencies.

## Folder structure
- `index.html`: complete Home page.
- `domain.html`: completed paper-grounded research domain, methodology and architecture page.
- `milestones.html`: research-stage timeline and verified refinement history.
- `documents.html`: nine academic categories, approved proposals/overviews/topic form, two available thesis drafts, final paper and clearly pending entries.
- `presentations.html`: three presentation PDF views/downloads, pending final presentation and research evolution.
- `about.html`: verified research team, portraits, integrated contributions, journey and affiliation.
- `contact.html`: approved researcher emails, working email actions and research resources.
- `css/style.css`: tokens, reset, typography, global layout.
- `css/components.css`: navigation, buttons, hero, cards, architecture, timeline, footer and internal pages.
- `css/responsive.css`: tablet/mobile layouts and reduced-motion support.
- `assets/images/`, `assets/diagrams/`, `assets/icons/`: team portraits in `assets/images/team/`; six original diagram PNGs are displayed in the document gallery; inline SVG icons are used.
- `documents/research-pdfs/`: the supplied public copy of the final research paper.
- `presentations/slides/`: three browser-friendly historical presentation PDFs; originals are archived externally.

## Run locally
Open `index.html` directly in a browser. Optionally run `python -m http.server 8000` from the root and visit `http://localhost:8000`. Python is optional; the site has no runtime dependencies. All links are relative for static hosting.

## Implementation status
Home includes the hero and conceptual architecture graphic, overview, four research components, layered product architecture, journey preview, documentation preview and closing call to action. All seven pages include consistent navigation and footer. Mobile navigation uses native details/summary. Focus styles, skip links, semantic headings, responsive grids and reduced-motion support are included.

The milestone page uses user-confirmed 2026 assessment dates, panel IT-P05, Conducted/Scheduled event statuses and Not Published marks/results. Resource cards point to section pages, not fictional downloads. Research results and personal information have not been invented.

## Phase 2 sources and content integrity
The primary source is `research-source/An AI Driven Smart Retail Recommendation System.pdf` (six pages), titled **AI-Driven Smart Fashion Retail Recommendation System**. No external references were introduced. Domain content draws on the Abstract and Sections I-VI. Its bibliography preserves all 26 available entries and citation numbering, without fabricated bibliographic details.

The challenge flow is a conceptual summary of the Abstract/Introduction. The methodology workflow is an HTML/CSS adaptation of Fig. 2, including iterative improvement. The layered architecture adapts Figs. 1 and 3. These are clearly captioned adaptations; no fake performance charts or original-paper alterations were made. The supplied approved public PDF is linked directly; its academic content is unchanged.

Confirmed headline results: daily inventory R-squared 0.9497; marketing accuracy 85.5%; brand-size accuracy 88.4%; behaviour classification accuracy 91.2%. Regression R-squared is distinct from classification accuracy. Additional component metrics retain their exact reported values. Partially simulated/prepared data and real-world validation limits are visibly explained.

### Source discrepancies requiring academic verification
- Marketing abstract accuracy is an older 78.3%; Section IV.B and user confirmation establish 85.5% as the website final value.
- Marketing ROC-AUC is 0.819 in text; Fig. 6 displays approximately 0.934. Website uses 0.819 and visibly flags the unresolved discrepancy.
- Section II cites [27], but the reference list ends at [26]. Entry [26] is a virtual dressing-room publication; no renumbering or invented [27] entry was introduced.
- Introduction citation [11] accompanies inventory/marketing claims, but bibliography [11] describes virtual try-on. Domain uses [11] only in the relevant literature theme.
- Section III.E defines Browsing/Transiting classification, while Section IV.D uses broader shopping-intent wording. Website follows the defined task without asserting validated purchase prediction.
- Institutional reference details, including [24] and [25], remain as supplied. No missing URL, DOI or publication information is invented.

## Phase 3 implementation
Completed Milestones, Documents and Presentations using the existing navigation/footer and scoped archive styles. The milestone sequence is Initial Proposal, PP1, PP2, Final Research Paper, and Final Presentation/Viva. Status describes material availability, not assessment completion; no assessment dates, marks, grades, outcomes or completion percentages were inferred.

The presentation covers remain HTML/CSS stage labels, not slide screenshots. Phase 3.5 adds native browser PDF viewing and PDF downloads while preserving the original PowerPoints externally.

### Historical Phase 3 public materials
Sizes use decimal MB (1 MB = 1,000,000 bytes).

| Material | Public path | Bytes | MB | Original slides / PDF pages |
| --- | --- | ---: | ---: | ---: |
| Final research paper | `documents/research-pdfs/An AI Driven Smart Retail Recommendation System.pdf` | 710,920 | 0.71 | 6 pages |
| Proposal | `presentations/slides/proposal-presentation.pdf` | 7,096,998 | 7.10 | 43 / 43 |
| PP1 | `presentations/slides/pp1-presentation.pdf` | 3,340,356 | 3.34 | 44 / 44 |
| PP2 | `presentations/slides/pp2-presentation.pdf` | 2,213,316 | 2.21 | 20 / 20 |

### Historical sources and verification notes
- Proposal: slides 4, 8-9, 11-13, 19-22, 27-32 and 34-40 document the early integrated concept, including CCTV emotion detection and smart mirrors. Proposed methods are not recast as final implementation.
- PP1: slide 2 is the explicit panel-feedback/refinement record. Prototype feedback appears in slides 15, 23, 34 and 41; future work in 16, 25, 35 and 42.
- PP2: component workflows in slides 8, 12, 16 and 19 were inspected as embedded figures; slide 20 documents future work. Figures show shared Firestore data, inventory manager review, GPS classification, brand sizing, virtual fitting and RFM/XGBoost marketing direction.
- PP1 uses earlier marketing technologies (Random Forest/Stable Diffusion). PP2's fitting text mentions Gemini while its workflow figure describes Vertex AI. The final paper is the authority for final methods and results; historical files are unaltered.
- PP2 has no separate verified user-feedback account. User feedback is attributed to the explicit PP1 sections, not invented for PP2. Workflow diagrams do not establish full integration testing or deployment completion.
- The final paper summary uses Sections III-VI: integration, evaluation, partially simulated/prepared data, limitations and future work. Final results and citations on Domain are unchanged.
- The actual final paper filename differs from AGENTS.md's suggested `final-research-paper.pdf`; the readable supplied file was used. The public PDF is byte-identical to the development copy.
- No `Website.pdf` university-guideline file was found in the workspace. The supplied instructions and AGENTS.md's 20 MB limit were used.

### Pending materials and file placement
Project Charter; standalone written proposal and supporting proposal documentation; PP1/PP2 written support; progress checklists; approved evaluation forms; individual final reports; other final documents; approved architecture/methodology exports and supplementary files; final presentation and viva/assessment details remain pending. Pending document cards omit download anchors entirely.

Place approved PDFs and research reports in `documents/research-pdfs/`, and approved presentation files/previews in `presentations/slides/`. Keep actual filenames and update the relevant static HTML card only after checking existence, content, stage, format and size. Do not assume that dropping a file into a folder updates the website automatically. Keep development references in `research-source/`; do not publish or package them without approval.

## Remaining phases
Phase 4 is implemented using user-confirmed team photographs, academic profiles and researcher emails. Supervisor details have not been supplied and are not published. Final assessment information and missing Phase 3 materials require verification. Phase 3.5 resolves oversized decks; final content review and Courseweb submission remain pending. The website is **not final-submission-ready**.

Home and Domain academic content is preserved. Domain now uses the byte-identical approved public paper, allowing development references to be excluded from staging.

## Source submission considerations
Keep the HTML and CSS directory structure intact. Include only verified necessary assets and stay below the university 20 MB limit. Empty reserved folders may need recreation after source-control checkout. Navigation and footer are repeated in static HTML; update all seven pages when changing them.

Review at 375, 768, 1024 and 1440 pixels, test keyboard and mobile menu behaviour, colour contrast and overflow. Automated source checks do not replace browser or assistive-technology testing. Checks actually performed are reported in the implementation response.

## Phase 2 verification
- HTML5 parser validation of Domain: no errors; balanced HTML structure and relative links/anchors checked across all seven pages.
- CSS syntax parsed with a CSS parser: no errors across all three stylesheets.
- All 26 reference targets, all required Domain sections, and every displayed component metric verified; no older abstract accuracy appears as a final result.
- Chrome inspection at exact 375, 768, 1024 and 1440 pixel viewport widths: no document horizontal overflow. Wide tables and section navigation use contained scrolling.
- All nine sticky-navigation anchors and a reference target land below the header/navigation at every width.
- Native mobile navigation opens using Enter; Tab moves to the first navigation link. Reduced-motion emulation disables hero animations.
- Full-page screenshots and viewport detail screenshots inspected for the hero, methodology, architecture, sizing component and evaluation cards across the requested widths.
- Home overflow regression checked at 375 and 1440 pixels. Hash checks confirm the Home page, five remaining pages and original source PDF are byte-for-byte unchanged.
- No JavaScript files, inline scripts, event handlers, package manifest, external stylesheet or asset requests were introduced. At Phase 2 completion, project size including the supplied PDF was under 1 MB; the later presentation assets are covered by the Phase 3 size report.
- Screen-reader and additional-browser testing were not performed. Source bibliography inconsistencies remain subject to academic verification.

PDF extraction, syntax-validation and browser automation tools used during implementation reside outside the project and are not website dependencies. Temporary screenshots are also outside the submission directory.

## Historical Phase 3 validation and size (before optimization)
- HTML5 parser validation passed for all seven pages. Verified unique anchors, semantic main/heading structure, active-page navigation, every local CSS/file link and cross-page anchor.
- CSS parser validation passed for all three stylesheets; no external imports, fonts, assets, framework/build dependencies, package manifest, inline scripts, event handlers or JavaScript files were introduced.
- The document library contains one actual available PDF and twelve pending document entries. Available PDF cards provide View and Download anchors; pending cards contain no anchors. The presentation gallery has exactly three genuine PPTX download links and no download or preview link on the pending final presentation.
- Three PPTX archives passed full ZIP integrity checks. The public PDF was read as six pages and is identical to the development source copy.
- Chrome QA passed for each Phase 3 page at exact 375, 768, 1024 and 1440 pixel viewport widths. No document horizontal overflow or clipped layout elements were detected; the literature/refinement table uses contained scrolling on smaller screens.
- Native mobile navigation opens with Enter; Tab reaches its first link on all three pages. Milestone and presentation source disclosures open with Enter. Section anchors land below the sticky site header; download links accept focus. Reduced-motion emulation disables archive hero animations.
- Desktop full-page and mobile/tablet viewport screenshots were inspected for timeline cards, refinement flow, document/presentation cards, available PDF buttons and the final pending state.
- Home and Domain overflow regression checks passed at 375 and 1440 pixels. Hash verification confirms Home, Domain, About, Contact, AGENTS.md and all original academic assets remain byte-for-byte unchanged.
- Screen-reader testing, other-browser testing and actual browser file-transfer completion were not performed. The download paths and file integrity were checked without downloading duplicate large decks.
- No submission archive was created. The 20 MB limit is **not met** with the original PowerPoints. An authorized asset/packaging decision remains required; Phase 4 was not started.

Total project footprint (all workspace files): **187,741,909 bytes (187.74 MB)**. Public document/presentation assets: **186,843,027 bytes (186.84 MB)**. Development-only research sources account for a further 710,920 bytes; excluding them alone would still leave the site far over the limit. Figures use decimal MB.

Temporary source extracts, browser profiles, screenshots and QA tooling reside outside the project and are not submission assets or website dependencies.

## Historical Phase 3.5 optimization
Implemented PDF conversion, safe original relocation, public link updates and clean staging. No CSS, design, research findings, citations, or paper content were changed. Phase 4 has not started.

Original backup location: `D:\smart-omni-retail-research-originals`. Root copies were verified using SHA-256 before relocation; relocated originals are in its `relocated-originals/` subfolder and match those verified copies byte-for-byte. `backup-verification.json` records exact filenames, sizes and hashes. Originals were not overwritten or deleted.

| Original file | Original bytes | MB |
| --- | ---: | ---: |
| `R26-IT-060 - AI-Based Smart Retail Recommendation System.pptx` | 107,149,765 | 107.15 |
| `IT26-IT-060-PP1.pptx` | 57,705,192 | 57.71 |
| `IT26-IT-060-PP2.pptx` | 21,277,150 | 21.28 |

Microsoft PowerPoint exported read-only backup decks to real PDFs. Page counts match every original slide, preserve order and 16:9 aspect ratios, and contain text on every page. Representative titles, diagrams, screenshots and dense text were rendered and visually inspected. No additional image compression was necessary. A fixed-format retry improved PP2 text wrapping. PowerPoint's own rendering repeats a few wrapped words in PP1; all information remains readable. Static PDFs do not play embedded videos or animations; these remain preserved in the external original decks. No watermarks were added. Original historical claims are retained without editorial correction.

Presentation cards now provide View Presentation links with `target="_blank"` and `rel="noopener noreferrer"`, plus Download PDF links. Milestone downloads use the same PDFs. Final presentation stays Pending Upload. Documents already used the approved public paper; Domain's legacy development-source link was corrected. Reserved image/diagram/icon folders contain no files needing optimization.

Staging directory: `D:\smart-omni-retail-submission`. It includes seven HTML sources, three CSS sources, four public PDFs and this README. It excludes original PPTX files, research-source, AGENTS.md, backups, Git history, caches, converters and test artifacts. Open staging's `index.html` directly; no install or build is required. ZIP: `D:\smart-omni-retail-submission.zip`.

Final measured sizes and staged validation are recorded below after testing. The workspace is not a Git repository; no commits, pushes or history changes were made.

### Historical Phase 3.5 staged validation and final size
- All seven staged pages parse as HTML5 without errors; every relative link, CSS path and cross-page anchor resolves. All three CSS files pass syntax parsing.
- Chrome tested all seven staged pages at exact 375, 768, 1024 and 1440 px (28 combinations): CSS loads, no document horizontal overflow, and resource cards stay inside their viewports. Gallery screenshots were inspected. Seven navigation routes and native mobile menus using Enter/Tab passed.
- Three presentation preview links opened their actual PDF URLs in new tabs. All four PDF browser downloads completed and their SHA-256 hashes match the staged sources. All fourteen HTML/CSS/PDF files returned HTTP 200 with exact file contents; PDFs use application/pdf.
- Pending document and final-presentation cards contain no fake links. No PPTX or development-source links remain in staged HTML. No JavaScript, inline scripts/event handlers, or runtime dependencies were introduced.
- SHA-256 checks confirm Home, About, Contact, Documents, all CSS, AGENTS.md and both original paper copies are unchanged. Domain changed only its public-paper href. Original presentations match both verified external copies after relocation.
- PDF counts are 43/43, 44/44 and 20/20; all retain 16:9 pages and contain text. Representative visuals were inspected; minor native PowerPoint wrapped-word repetition in PP1 and static video/animation limitations remain disclosed above.
- Screen-reader and other-browser testing were not performed. Test scripts, browser profiles, downloaded test copies and screenshots remain outside development and staging.

Measured complete directory sizes (decimal MB):
- Development project: **14,265,218 bytes (14.27 MB)**.
- Public PDF assets: **13,361,590 bytes (13.36 MB)**.
- Uncompressed submission staging: **13,546,985 bytes (13.55 MB)**, including README and every required HTML/CSS/PDF.

The uncompressed staging folder satisfies both the 20 MB maximum and the preferred 15 MB target. ZIP compression is not required to meet either limit. The ZIP contains the same fifteen staged files, with no original decks or development references. This is an optimized snapshot of completed phases, not a claim of final submission readiness. About/Contact, verified team and contact details, final presentation/viva details, missing document categories, university guidelines and final academic/content review remain pending. Phase 4 requires explicit authorization.

## Phase 4 implementation
About Us and Contact Us are complete within the supplied scope. Existing Home, Domain, Milestones, Documents and Presentations HTML is unchanged. New CSS is scoped to `.people-page`; existing design tokens, header/footer, native mobile navigation and reduced-motion rules are reused.

About includes the requested hero, four verified researcher profiles with contribution summaries, connected research areas through Flutter/FastAPI/Firestore, a Proposal -> PP1 -> PP2 -> Final Research journey, milestone/architecture links and SLIIT academic affiliation. No supervisor, department, award or biography was invented. Contact includes the requested hero, group/institution/project identity, approved individual researcher emails, an Email Research Team action addressing all four researchers, individual mailto links, four research-resource cards and an academic-service disclaimer. Email actions open a configured email application; the website does not send email itself.

### User-confirmed photographs and contacts
All four member-to-image mappings were explicitly confirmed by the user during Phase 4. All four emails below were supplied by the user as approved contacts. No separate group mailbox was invented.

| Researcher | Student ID | Original image in assets/images/team/ | Approved email |
| --- | --- | --- | --- |
| W. M. Methsara | IT22244598 | `W.M.Methsara_IT22244598.png` | it22244598@my.sliit.lk |
| J. A. R. K. Wijetunga | IT22146588 | `J.A.R.K.WIJETUNGA_IT22146588.jpg` | it22146588@my.sliit.lk |
| T. A. Silva | IT22284952 | `T.A.Silva_IT22284952.png` | it22284952@my.sliit.lk |
| L. A. D. A. S. Perera | IT22243812 | `L.A.D.A.S.Perera_IT22243812.jpg` | it22243812@my.sliit.lk |

Portrait files total 733,691 bytes. The supplied photographs are retained byte-for-byte with no facial modifications, filters or further compression. Uniform contain-fit frames preserve each complete photograph. Silva (146 x 193) and Perera (221 x 247) are low-resolution originals and can look softer when enlarged; no artificial detail was generated. Higher-resolution approved replacements are optional.

### Staging, hosting and remaining materials
The previous verified Phase 3.5 ZIP was copied to `D:\smart-omni-retail-submission-phase35.zip` and its SHA-256 verified before regeneration. Original PowerPoint backups remain untouched at `D:\smart-omni-retail-research-originals`. Refresh staging at `D:\smart-omni-retail-submission`; final ZIP remains `D:\smart-omni-retail-submission.zip`. Only seven HTML pages, three CSS files, four public PDFs, four approved portraits and README are included. Development sources, AGENTS.md, large PowerPoints, backups, caches and QA tooling are excluded.

The static website is prepared for a future GitHub Pages upload: index.html entry, relative paths, exact filename capitalization, no Windows/local-development HTML links, JavaScript, build commands or external runtime dependencies. Upload staging's contents as the hosting root and select the repository/branch through GitHub Pages when authorized. No repository was created, no code pushed, and nothing published. Live hosting behavior and email delivery were not tested.

Required academic material still missing: Project Charter; standalone written proposal/support; PP1/PP2 written support; progress checklists; approved evaluation forms; individual final reports; other final documents; approved architecture/methodology exports and supplements; final presentation and viva/assessment dates/marks. No Website.pdf guidelines were supplied. Existing paper citation/result discrepancies and PP1 PDF wrapped-word repetition remain disclosed above. The website is not fully submission-ready while required academic materials remain missing.

### Phase 4 validation and final sizes
- Staged HTML5 parsing passed for all seven pages, including one main/h1 per page, proper heading hierarchy, unique anchors, image alt text, active-page navigation and all footer routes. All three stylesheets passed CSS syntax/declaration checks. All 268 local link/asset references and cross-page anchors resolve with exact filename capitalization.
- Chrome passed all seven pages at 375, 768, 1024 and 1440 px (28 layout checks), without document horizontal overflow or resource-card overflow. Native mobile menus work with Enter and Tab on all seven routes. About/Contact sections were additionally captured at all four widths and representative desktop/mobile/tablet screenshots inspected. Tablet portrait frames were corrected and affected layouts rechecked.
- All four confirmed portraits load, preserve full photographs with contain-fit frames and keep uniform 4:5 frame proportions. About and Contact also load directly from staged file URLs with working CSS/images, independently of the development folder.
- Visible keyboard focus and reduced-motion behavior passed on both new pages. Accessibility-tree main landmarks were checked. Eight representative new-page text/button colour pairs exceed 4.5:1 (minimum 5.69:1). These targeted checks are not a full WCAG audit; screen-reader/assistive-technology and other-browser testing were not performed.
- Three presentation View actions opened their actual PDF URLs in new tabs; four PDF downloads completed in Chrome and matched source SHA-256. HTTP delivery of all fourteen HTML/CSS/PDF resources passed. Research paper and presentation PDFs retain 6, 43, 44 and 20 pages. Pending document cards and the final presentation contain no fake links.
- Five previously completed HTML pages, all academic PDFs and original photographs remain byte-for-byte unchanged. Existing CSS bytes are preserved before the appended scoped rules. Confirmed results (inventory R-squared 0.9497, marketing 85.5%, sizing 88.4%, behaviour 91.2%) and flagged paper inconsistencies remain unchanged. There are no scripts, forms, framework/build/runtime dependencies, Windows links or development-source paths in staged HTML.
- Approved contact links address the four supplied researcher emails, including the combined Email Research Team action. Recipient/path and keyboard checks passed; launching a configured email client and actual email delivery were not tested.
- QA tools, browser profiles, screenshots and downloaded test copies are outside development and staging. No GitHub repository, push or publishing action was performed.

Complete measured footprints (decimal MB):
| Scope | Bytes | MB |
| --- | ---: | ---: |
| Development project | 15,019,645 | 15.02 |
| Public PDFs and portraits | 14,095,281 | 14.10 |
| Uncompressed submission (all nineteen files) | 14,301,412 | 14.30 |

The uncompressed submission has **5,698,588 bytes (5.70 MB)** remaining below the 20 MB maximum and **698,588 bytes (0.70 MB)** below the 15 MB target. Compression is not needed for compliance. The regenerated ZIP is verified against all nineteen staged file contents; the previous Phase 3.5 ZIP backup is hash-verified and unchanged. Hosting is technically prepared but remains unpublished; required academic materials and the documented source/conversion limitations still require attention before final submission.

## Phase 4.1: database terminology and compact references
The user explicitly confirmed MongoDB as the current research-system database. Home, Domain and About current architecture labels, component integration descriptions and the database technology row now use MongoDB. Firebase Authentication is retained as a separate authentication service. No MongoDB Atlas, deployment, schema or migration details are asserted; no application backend or database was modified.

Milestones retains Firestore in its historical PP2 workflow description and final-paper summary. Presentations retains Firestore in its explicit summary of the unchanged final paper. Domain retains three Firebase Authentication occurrences; Milestones retains one. The PDFs and original PowerPoints remain historical academic records with their original Firebase/Firestore terminology. README's older implementation/source notes are historical or internal development references, not statements of the current database. AGENTS.md's two current architecture/product descriptions were updated; all other rules remain intact.

Domain's visible bibliography [1]-[26], source-consistency notes, reference-numbering editorial aside and marketing clarification aside were removed. The compact References card retains the requested primary-source title, description and Read the Research Paper action to the verified public PDF. Inline citation numbers are unchanged; their links now open the complete paper at page 6 instead of targeting removed bibliography entries. The sticky References link and #references target remain. Literature, methods, findings, contributions, limitations and future work are preserved; no PDF citations/results were altered. The reported-text ROC-AUC value of 0.819 remains unchanged, with its unresolved discrepancy retained in the internal academic notes above. Bibliography-only CSS was removed after verifying no other page uses those selectors.

Source-document inconsistencies remain unresolved: marketing abstract 78.3% versus confirmed 85.5%; ROC-AUC text 0.819 versus figure approximately 0.934; [27]/[26] numbering, [11] citation context, limited reference details and behaviour terminology. The unchanged paper describes Firestore whereas the current website architecture follows the user's MongoDB update. Historical PDFs do not verify a MongoDB migration, deployment or re-evaluation.

The previous Phase 4 ZIP is preserved at `D:\smart-omni-retail-submission-phase4.zip` with verified SHA-256 before regeneration. Staging and final ZIP remain `D:\smart-omni-retail-submission` and `D:\smart-omni-retail-submission.zip`. Static GitHub Pages readiness is retained; nothing was published or pushed. Missing academic materials and prior conversion/image limitations remain as documented above.

### Phase 4.1 validation and final size
- All seven staged HTML pages and three CSS files pass parsing/syntax checks. All 264 local file/asset references resolve, including exact-case filenames, PDF page fragments and remaining HTML anchors. Navigation/active-page indicators, pending material states, team photographs and approved email actions remain intact.
- Chrome passed seven pages at 375, 768, 1024 and 1440 px (28 layout checks), without horizontal document/card overflow. Navigation routes and keyboard mobile menus passed. Three presentation previews opened actual PDFs; all four PDF downloads completed with matching SHA-256. The compact source-card paper action also opened its actual public PDF in a new tab.
- Domain's nine sticky section links land below the header/navigation at all four widths, including References. Architecture and compact References screenshots were captured at every width and representative desktop/mobile views inspected. Direct staged-file Domain loading, source-action visible keyboard focus and reduced-motion behavior passed. Existing contrast colours/styles are preserved; screen-reader and other-browser testing were not performed.
- Source comparison confirms nine current MongoDB labels in public HTML, four Firebase Authentication mentions and three explicitly historical Firestore mentions. Every inline citation number is unchanged and now points to the full paper. Only bibliography-specific selectors were removed. Contact, Milestones, Documents and Presentations, all photographs and all research/presentation PDFs remain byte-identical to the Phase 4 baseline; the paper still has six pages and slides PDFs have 43, 44 and 20.
- Current database terminology follows the user's instruction, not a change to the historical PDFs. Research results, existing inline citation text, study limitations and source discrepancies are preserved, with editorial/source-review notes now confined to README. No JavaScript, runtime dependencies, application database changes or hosting actions were introduced.

| Complete footprint | Bytes | Decimal MB |
| --- | ---: | ---: |
| Development project | 15,018,681 | 15.02 |
| Uncompressed staging (nineteen files) | 14,300,460 | 14.30 |

Staging remains under both the 20 MB maximum and 15 MB target, with **5,699,540 bytes (5.70 MB)** available below the university maximum. The regenerated ZIP is checked for integrity and exact equality with all nineteen staged files; the previous Phase 4 ZIP backup is preserved unchanged. GitHub Pages remains technically prepared and unpublished. Required academic materials and documented historical source/conversion limitations remain outstanding.

## Phase 4.2: SLIIT guideline compliance improvements
The original guideline was found at `C:\Users\Methsara\Downloads\Website.pdf` (214,063 bytes, 16 pages) and read in full during this phase. It is a development reference, not a public download/submission asset. Earlier notes about missing guidelines describe the earlier phases. Pages 8-16 specify the seven-page structure, Domain topics, assessments, document/slides lists, team/contacts and 20 MB maximum. The user-provided Phase 4.2 instructions impose the stricter HTML/CSS-only restriction; WordPress was not introduced.

Sources reviewed: the complete six-page final paper (especially Sections I-III for background/process and IV-VI for evaluation/limits), proposal slides 4/8/9, PP1 slides 2/15, and PP2 slides 4/8/12/16/19/20. Existing architecture/workflow figures and historical-source distinctions are retained. Current MongoDB terminology follows the Phase 4.1 instruction; Firebase Authentication remains separate. Source discrepancy notes remain internal and academic PDFs are unchanged.

Domain now names all six required topics in its sticky navigation, including Research Problem and Technologies Used. Technologies follows Methodology before additional architecture/components/results sections. The literature cards expand evidence-grounded approaches and limitations for all four functions while retaining original inline citations. The gap explains coordination across retail decisions; Research Problem adds four component-specific problems. The detailed methodology retains its workflow and adds data preparation, models, three-fold body-measurement tuning, evaluation/testing evidence and limitations. Its additional sections and compact References card are preserved; no public bibliography or source-consistency commentary was restored.

Milestones adds five native details/summary assessment dropdowns: Project Proposal, Progress Presentation 1, Progress Presentation 2, Final Assessment and Viva. Each exposes a description, date, allocated marks and status. All dates/marks/status values are **To be confirmed**, as explicitly instructed by the user; file availability is kept separate from assessment completion. Three real presentation links and the available final paper are provided; no viva or final-slide file is invented. The original research timeline and refinement history remain.

Documents now has the six explicit academic categories (Project Charter, Proposal Document, Checklist Documents, Final Documents, Main Group Research Report, Individual Research Reports), plus progress supporting documents and supplementary materials. There are seventeen cards: one available research paper and sixteen pending entries. The main group report is pending separately from the six-page paper; the paper is not silently treated as a full group report. Four member-specific individual report entries are pending. All original resource categories/material descriptions and the genuine paper View/Download links remain. No fake files, embeds or pending download links were added.

About now displays the already-approved member email addresses alongside verified portraits/profiles. Contact's existing team mailto action adds a subject and editable inquiry template (name, affiliation and topic); it opens a configured email application, with no form service or sender backend. Home and Presentations already satisfy their structure requirements and are unchanged.

### Seven-page university compliance checklist
Statuses describe evidence, not inferred completion. The numbered source pages refer to the original Website.pdf.

| Requirement | Page | Implemented status | Evidence | Missing information |
| --- | --- | --- | --- | --- |
| Seven main routes and consistent navigation/design (pp. 5-8) | All seven | Implemented | Shared header/footer, active route, relative links, source folder structure | None for navigation structure |
| Concise project introduction and restrained graphics (p. 9) | Home | Implemented | Research overview, four functions, CSS architecture and section links | None for page structure |
| Literature Survey (p. 10) | Domain | Implemented | #literature; four component backgrounds, limitations and retained source citations | Source bibliography inconsistencies remain internal |
| Research Gap and Research Problem (p. 10) | Domain | Implemented | #research-gap and #research-problem; central coordination question and four component problems | Real-world validation remains future work |
| Main/component research objectives (p. 10) | Domain | Implemented | #objectives; main objective and existing component/integration objectives | None for source-grounded presentation |
| Methodology and Technologies Used (p. 10) | Domain | Implemented | #methodology/#technologies; preparation, models, integration, evaluation and role-based stack | Historical paper retains Firestore; current site uses user-confirmed MongoDB |
| Architecture, findings, limitations and compact source link | Domain | Implemented | #architecture, #components, #results, #contributions, #future-work, #references | Existing academic discrepancies remain unresolved |
| Assessment dropdowns and descriptions (p. 11) | Milestones | Implemented | #assessments; five native details/summary controls; historical timeline preserved | None for dropdown interface |
| Assessment dates and allocated marks (p. 11) | Milestones | Incomplete | Each dropdown explicitly shows To be confirmed | Verified dates/marks for all five assessments; statuses also unconfirmed |
| Produced/pending document categories and links (p. 12) | Documents | Structure implemented; materials incomplete | Eight categories; one available paper and sixteen pending cards | Charter, written proposal/support, checklists, evaluation forms, main/individual reports and other final/supporting files |
| Required final document set/count (p. 12) | Documents | Incomplete | Group and four member-report entries represented as pending | University-approved final report types/count and actual files; guideline says four documents with the main but does not map them to this group |
| Proposal, PP1, PP2, future final slides (p. 13) | Presentations | Partially complete | Three optimized PDF previews/downloads; final entry pending | Final presentation PDF and assessment/viva materials |
| Group identification/photos/emails (p. 14) | About | Implemented | Four confirmed names/IDs, photographs, responsibilities, member mailto links and affiliation | Higher-resolution Silva/Perera portraits optional; no unverified achievements/supervisors asserted |
| General contacts and email template (p. 15) | Contact | Email requirements implemented | Four approved contacts, group action with editable mailto template and research links | No verified phone/postal address supplied; no details invented |
| Allowed technologies and maximum size (p. 16) | Submission | Implemented; measured size below | HTML5/CSS3 only, no runtime dependencies; public PDFs/portraits and source files included | Missing deliverables must be size-checked before addition |
| Static hosting preparation | All seven | Prepared; unpublished | Relative paths, exact case, index.html entry | User authorization and live-host verification before deployment |

### Remaining academic materials and approvals
Dates and allocated marks remain pending for all five assessments; no deadlines, grades or outcomes are inferred. Final presentation/viva material, standalone charter/proposal, PP1/PP2 support, progress checklists, evaluation forms, main group report, individual reports and final/supplementary exports remain missing. Final-report types/count need academic confirmation against p. 12. No verified phone number is available; approved email contacts are provided. Website.pdf is now reviewed and is no longer a missing source. Existing research-paper discrepancies and PDF/portrait limitations remain documented above.

The previous Phase 4.1 ZIP is backed up at `D:\smart-omni-retail-submission-phase41.zip` with matching SHA-256 before regeneration. Staging and final ZIP retain their usual paths. The website remains partially compliant because mandatory assessment data and deliverables are not yet supplied. No GitHub push or deployment was performed.

### Phase 4.2 final validation and packaging

Passed HTML5/CSS syntax, heading hierarchy, unique IDs, active navigation, 276 exact-case local links/assets and all approved PDF hashes/page counts. All seven pages passed Chrome layout checks at 375, 768, 1024 and 1440 px (28 layouts), with no horizontal overflow. All five assessment dropdowns passed Enter/Space/Tab and visible-focus checks at each width (20 cases); all eleven Domain sticky links reached their targets below the sticky header. Four genuine PDF downloads matched their source hashes and presentation/source previews opened correctly. Four portraits loaded with contain-fit frames, with reduced-motion, keyboard focus, main accessibility landmarks and direct file-mode checks passing. The group mailto subject/template and four approved recipients were verified without sending email.

Home, Presentations, AGENTS.md, base style.css, all portraits and all academic PDFs are unchanged from the Phase 4.1 baseline. Existing component/responsive CSS is preserved with additions. No JavaScript, frameworks, build requirement or new website assets were introduced. Manual screen-reader operation, other browser engines, actual email delivery and live deployment were not tested.

Development folder: **15,044,109 bytes**. Complete uncompressed Courseweb staging: **14,325,888 bytes** (14.326 MB decimal), including all nineteen files and README. This is below the preferred 15 MB and mandatory 20 MB limits, leaving **5,674,112 bytes** below 20 MB. Staging excludes development research-source, AGENTS.md and QA tooling. The refreshed ZIP was integrity-tested and every member compared byte-for-byte with staging; the Phase 4.1 backup remains unchanged. Mandatory dates, marks and missing deliverables still prevent a claim of complete university compliance.

## Phase 4.3 — academic document library

This section supersedes earlier document-availability and size snapshots. Implementation is in the existing development project only. The user explicitly postponed ZIP creation and staging refresh; those snapshots are not current delivery packages. The user approved public distribution of the four proposals, four overviews and TAF, including proposal signatures and the TAF annotations/panel signatures. After the files appeared in the project, the user separately approved the two theses **as available drafts** and instructed: **Integrate approved files locally; defer size resolution to finalization.** The enlarged local library therefore does not currently meet the 20 MB submission limit.

### Document discovery, source review and approval

Eleven newly supplied files appeared inside existing documents subfolders during this phase. The nine proposal/overview/TAF files are byte-identical to the supplied Desktop set at `C:\Users\Methsara\Desktop\IT22244598\New folder` and their Downloads copies. Only existing project originals are linked; no duplicate public copies were added. PDF text and the scanned marketing proposal/TAF were reviewed. The complete sixteen-page Website.pdf was re-read, particularly document requirements on p. 12 and the 20 MB limit on p. 16. Existing paper and presentation paths were inspected and preserved.

Proposal covers/declarations confirm the four student IDs and the group. The marketing proposal is image-only, verified visually, and keeps its scanned format. Overview content confirms all four functions; researcher mapping follows the approved team/component mapping and supplied filenames, rather than claiming IDs are printed in the overview bodies. Thesis covers verify IT22244598 for inventory and IT22146588 for marketing. Both declaration/certification pages have blank signature/date fields; the page calls them drafts and asserts no assessed/finalized status. Keyword matches concerning passwords/API keys in the theses describe credential handling or missing environment variables; no literal credential was identified. This inspection is not an institutional clearance or exhaustive security certification.

Signatures in three proposal declarations and annotations/signatures in the TAF were flagged before inclusion, then explicitly approved by the user. All eleven supplied documents are now approved for local website links. No document remains awaiting publication approval in this set; newly supplied future documents need their own review. Research claims and historical Firestore terminology inside originals are unchanged.

### Current categories and availability

| Category | Status | Entries |
| --- | --- | --- |
| Project Charter | Pending Upload | One official group charter pending |
| Individual Research Proposal Reports | Available | Four separate student/component reports; no combined-group-proposal claim |
| Checklist Documents | Pending | Official checklist files not supplied |
| Other Approved Final Research Documents | Pending | Remaining approved final documents not supplied |
| Main Group Research Report | In Preparation | Full group thesis incomplete; individual theses/paper are separate |
| Individual Research Reports | Two available drafts; two pending | Methsara/Wijetunga drafts; Silva/Perera pending |
| Progress Supporting Documents | Available | Four system overviews, including one Word document |
| Supporting Research Materials | Paper available; further materials pending | Existing six-page final paper; architecture, methodology and integration/technical exports pending |
| Research Topic Assessment | Available | Verified R26-IT-060 Topic Assessment Form |

The Documents page has twenty-one cards: twelve available files (eleven PDF and one DOCX) and nine pending/in-preparation entries. Every available file has genuine Open/View and Download actions. Pending cards have no download anchors. The existing final paper title and its View/Download URLs are preserved exactly. No unofficial checklists, placeholder PDFs or supporting diagrams were generated.

### Current approved document locations

| Document | Student ID | Path | Format / pages | Bytes |
| --- | --- | --- | --- | ---: |
| Individual Research Proposal Report | IT22244598 | `documents/proposal-reports/IT22244598 - Proposal Report .pdf` | PDF / 36 | 1,468,771 |
| Individual Research Proposal Report | IT22146588 | `documents/proposal-reports/IT22146588 - Proposal Report.pdf` | PDF / 25 | 4,637,213 |
| Individual Research Proposal Report | IT22284952 | `documents/proposal-reports/IT22284952_Proposal_Report.pdf` | PDF / 28 | 1,176,872 |
| Individual Research Proposal Report | IT22243812 | `documents/proposal-reports/IT22243812_Proposal_Report.pdf` | PDF / 31 | 1,150,056 |
| Individual Thesis — Available Draft | IT22244598 | `documents/individual-theses/IT22244598_DRAFT.pdf` | PDF / 120 | 3,968,422 |
| Individual Thesis — Available Draft | IT22146588 | `documents/individual-theses/IT22146588_DRAFT.pdf` | PDF / 59 | 1,605,476 |
| Smart Inventory System Overview | IT22244598 | `documents/system-overviews/System_Overview_IT22244598.pdf` | PDF / 19 | 346,944 |
| Marketing Intelligence System Overview | IT22146588 | `documents/system-overviews/System_Overview_Marketing_Intelligence - RW.docx` | DOCX | 27,068 |
| Virtual Try-On System Overview | IT22284952 | `documents/system-overviews/System_overview-IT22284952.pdf` | PDF / 5 | 11,348 |
| Customer Behaviour System Overview | IT22243812 | `documents/system-overviews/System_overview-IT22243812.pdf` | PDF / 6 | 12,600 |
| Final Research Paper | Group R26-IT-060 | `documents/research-pdfs/An AI Driven Smart Retail Recommendation System.pdf` | PDF / 6 | 710,920 |
| Research Topic Assessment Form | Group R26-IT-060 | `documents/topic-assessment/TAF R26-IT-60.pdf` | PDF / 14 | 2,655,847 |

### Individual and group thesis status

| Researcher | Student ID | Component | Status |
| --- | --- | --- | --- |
| W. M. Methsara | IT22244598 | Inventory and stock flow | Available draft; 120 pages |
| J. A. R. K. Wijetunga | IT22146588 | Personalised marketing | Available draft; 59 pages |
| T. A. Silva | IT22284952 | Virtual try-on and sizing | Individual Thesis — Pending |
| L. A. D. A. S. Perera | IT22243812 | Customer behaviour and staff assistance | Individual Thesis — Pending |

The Main Group Research Report is **In Preparation**. Neither an individual thesis nor the six-page paper is used as the full group thesis.

### Folder reuse and document handling

Reused `documents/proposal-reports`, `documents/individual-theses`, `documents/system-overviews`, `documents/topic-assessment` and `documents/research-pdfs`. The topic-assessment folder arrived with the user’s upload. No new folder was created by the implementation and no empty category folders were added. Existing pending folders remain untouched. Existing filenames are retained to preserve original identity; HTML URLs encode spaces. Academic originals are not renamed, overwritten, optimized or deleted.

Microsoft Word export of an external copy stalled and no reliable PDF conversion could be verified. The approved marketing overview remains DOCX. Its Open action uses the actual Word file and explicitly identifies that a compatible application is required; no browser PDF preview is promised. The source Word document is unchanged. External experimental PDF copies were used only to evaluate size savings; no experimental copy is part of the project or linked website. Lossless checks preserved text and rendered pixels but did not give meaningful reductions; smaller image/font candidates retained all PDF page counts and extracted text but still did not meet the limit for the complete library. No quality-reduced file replaced an original.

### Size constraint and finalization decision

Before the eleven uploads: development project **15,044,109 bytes**; projected public source set **14,325,888 bytes**; public PDF assets **13,361,590 bytes**. The eleven uploaded originals add **17,060,617 bytes**, including the 27,068-byte Word file. Public document assets after upload total **30,422,207 bytes**, before HTML/CSS/portraits/README. Even experimental compression candidates exceed 20 MB once all research materials and existing assets are included.

The user chose to integrate approved documents locally and defer size resolution. This is an explicit exception for the current development phase, not a compliant submission or authorization for external hosting/exclusion. Before final submission, review the largest files (proposal presentation 7.10 MB, marketing proposal 4.64 MB, inventory thesis 3.97 MB, PP1 3.34 MB, TAF 2.66 MB), verify proposed optimization quality, and obtain approval for any exclusion or external hosting. The package must then be measured below 20 MB uncompressed. No live upload, package or staging refresh is authorized in Phase 4.3.

### Future updates and remaining materials

Add each future approved document to the appropriate existing subfolder; inspect title, ownership, private information, signatures and assessment content; obtain publication approval when uncertain. Preserve the original and avoid duplicate public assets. Replace only its matching pending card, add actual relative View/Open and Download URLs, update README availability and size, then validate links, downloads, all nine category anchors and mobile layouts. Any draft replacement needs title/status verification; do not silently call a draft final. No CMS, database or automatic upload mechanism is used.

Outstanding materials: official Project Charter, checklist documents, other approved final research documents, completed group thesis, Silva/Perera individual theses, approved architecture/methodology/integration/technical supporting files, final presentation and verified assessment dates/marks/status. Current university final-report types/count still need academic confirmation. The website remains incomplete and exceeds the final submission size limit pending the authorized finalization decision.

### Phase 4.3 validation and measured local size

Passed HTML5 parsing for all seven pages, CSS parsing for all three stylesheets, semantic heading order, unique IDs, active navigation, and **299 exact-case local links/assets**. The library has nine category anchors, twenty-one cards, twelve unique available file paths and nine link-free pending/in-preparation cards. PDF page counts match the inspected sources; all academic PDF/DOCX hashes match their original pre-edit records. Six other HTML pages, AGENTS.md, base/responsive CSS, portraits, existing paper and presentation files are unchanged.

Chrome passed all seven development pages at 375, 768, 1024 and 1440 px (**28 layouts**), with CSS loaded and no horizontal overflow or out-of-viewport cards. All nine category links reached visible targets below the header at every width (**36 anchor checks**). All twelve download actions showed keyboard-visible focus at every width (**48 checks**). Native mobile navigation passed Enter/Tab on all seven pages; reduced-motion support and direct file-mode loading of all seven pages passed. Desktop and mobile screenshots of proposal/thesis/overview cards were inspected; document actions align at card bottoms.

Ten newly linked PDF View actions opened the correct files in new tabs; the existing research-paper View action retains its working same-tab behavior. **All twelve actual browser downloads completed and matched source SHA-256 hashes**, including the DOCX overview. All twenty-five public HTML/CSS/PDF/DOCX resources returned exact contents with HTTP 200 and correct PDF/Word MIME types. The DOCX download was verified; a native browser Word preview is not claimed. Screen-reader operation, other browser engines, Word rendering fidelity and live deployment were not tested. QA scripts, downloads, experimental copies and screenshots reside outside the project.

Final development directory: **32,131,909 bytes (32.132 MB)**. Projected public source set: **31,413,688 bytes (31.414 MB)** across thirty files, excluding AGENTS.md and development-only research-source. The projected submission exceeds the 20,000,000-byte limit by **11,413,688 bytes**; remaining allowance is zero. These are measured source-set projections, not a created package. The user explicitly deferred size resolution; this is not a compliant/finalized submission.

The existing staging directory was checked byte-for-byte against its phase-start inventory and remains unchanged. No submission ZIP was present at the usual D:\ path at phase start; no ZIP was created, regenerated, replaced or modified. No GitHub repository/deployment/push, external hosting or backend/database change occurred. No original academic document was deleted or overwritten. Only documents.html, css/components.css and README.md were modified by implementation; the eleven academic files were supplied by the user.

## Phase 4.4 — research diagram review and integration

The six-entry diagram subsection is implemented under Supporting Research Materials in documents.html. **No diagram image is approved for public display in this phase:** five methodology PNGs were supplied under descriptive filenames, all need academic corrections, and the overall system architecture image is missing. The six requested canonical PNG filenames are not present; the table maps the five identified equivalents. Titles, pending descriptions and statuses appear as responsive cards, with no image preview or active View/Download action until a corrected file is verified. Captions have not been represented as corrections to embedded PNG text. Existing twelve academic document links and all nine document categories are preserved. Domain remains byte-for-byte unchanged because neither overall image is academically suitable for insertion.

### Filenames, locations and review status

All supplied originals are in assets/diagrams/. Preserve them as review sources, but **exclude these five unverified originals from any future public hosting/submission file set**. They are not linked, embedded or treated as publishable website assets. Do not deploy the entire development directory without applying these exclusions. No source was deleted, renamed or overwritten.

| Diagram title | Expected canonical filename | Supplied filename | Status |
| --- | --- | --- | --- |
| Overall System Architecture | `overall-system-architecture.png` | Not supplied | Not Supplied |
| Overall Research Methodology | `overall-research-methodology.png` | `assets/diagrams/AI-Driven Omni-Retail Research Workflow.png` | Correction Required |
| Smart Inventory Methodology | `smart-inventory-methodology.png` | `assets/diagrams/Smart Inventory Optimisation Methodology.png` | Correction Required |
| Marketing Intelligence Methodology | `marketing-intelligence-methodology.png` | `assets/diagrams/Personalised Marketing Intelligence Flowchart.png` | Correction Required |
| Virtual Try-On Methodology | `virtual-tryon-methodology.png` | `assets/diagrams/AI Fashion Try-On Methodology Infographic.png` | Correction Required |
| Customer Behaviour Methodology | `customer-behaviour-methodology.png` | `assets/diagrams/GPS-Based Customer Behaviour Research Workflow.png` | Correction Required |

### Exact academic corrections and unresolved evidence

- **Overall architecture:** supply the missing image. Confirm MongoDB as shared data storage and Firebase Authentication as a separate service where applicable; distinguish documented/proposed links from demonstrated integrations. Existing HTML/CSS architecture remains available.
- **Overall methodology:** the supplied PNG names LSTM/ARIMA/ensemble demand forecasting and K-Means segmentation, generic size/behaviour classifiers, outfit suggestions, feedback analysis and user-acceptance testing. Regenerate component labels around the confirmed XGBoost forecasting, prompt-confirmed XGBoost redemption classification, Random Forest sizing and Random Forest behaviour classification; retain only evidenced methods/inputs and mark planned tests/integration as planned. Do not infer completed user acceptance or business validation. Marketing model choice requires reconciliation with the newer draft noted below.
- **Inventory:** daily R² 0.9497, MAE 0.5418 and RMSE 0.9436 agree with the confirmed paper; monthly R² 0.9353 is supported by the inventory thesis. However the PNG labels inventory intelligence and transfer recommendation as XGBoost regressors and depicts random 80/20 splitting. Inventory thesis pp. 26 and 41 describes a rule-based recommendation engine and chronological holdout; pp. 14/45/49 describe controlled review/approval/execution and inventory updates. Correct those model/split labels and preserve the real approve/reject/cancel/execute workflow. Do not turn business-impact examples or confidence intervals into verified outcomes.
- **Marketing:** XGBoost Regressor appears twice; the PNG uses illustrative MAE ~0.142, RMSE ~0.286 and R² ~0.92 and repeats regression metrics in monitoring. Remove these unsupported regression results; use classification terminology. The prompt/user-confirmed historical website accuracy remains 85.5%, but do not regenerate a verified final-results image until the newer thesis conflict is resolved. ROC-AUC 0.819 remains unverified; the paper text/figure already disagree. Verify segmentation, uplift and cross-module product/behaviour links instead of retaining unsupported generic integrations.
- **Virtual try-on:** replace generic diffusion/pose/keypoint processing with the evidenced Google Cloud Vertex AI virtual try-on implementation, Random Forest measurement regression and brand-size classification roles. Confirmed sizing accuracy is 88.4%. The customer inputs, recommended M size, product/customer pictures and **87% confidence score** are unlabelled examples; mark them explicitly illustrative or remove them. SSIM, baseline comparisons, user-feedback surveys, acceptance testing and image-enhancement stages must not imply verified evaluation without evidence.
- **Customer behaviour:** replace incorrect **87.6% classification accuracy** with prompt-confirmed 91.2%; remove the unsupported **84.2% Random Forest staff-assistance result** and separate staff-assistance classifier. Staff alerts use dwell-time/movement rules. The defined paper task is Browsing/Transiting; the PNG's Product Interested/Ready to Purchase/Need Assistance/Other classes and transaction/conversion inputs require evidence or removal. Clearly label illustrative zone map/customer output and future real-world testing; do not claim purchase-intent validation.

**New source conflict requiring academic decision:** IT22146588_DRAFT.pdf p. 3 reports that earlier leakage inflated results up to 85.5%, then states corrected tuned Random Forest accuracy **63.3%**, ROC-AUC **0.672**, and F1 **0.711**. Pages 42/47 discuss the earlier XGBoost result and leakage; p. 59 identifies RandomForestClassifier with 300 trees. This differs materially from the Phase 4.4 prompt and previously confirmed paper-based website. The draft does not verify 0.819. Existing Domain metrics, model descriptions and original academic files have been preserved; no discrepancy was silently reconciled. The user must confirm which final methodology/evaluation should govern regenerated marketing/overall images and any later website correction.

Review used all five actual PNGs, the complete existing source files, research-paper Sections III-V, inventory thesis method/workflow/evaluation passages and marketing thesis abstract/results/appendix. Editable diagram sources were not supplied; dependable correction of every embedded label, layout and unsupported claim was not verified. No AI-generated replacement, altered metric, fake missing diagram or caption-only workaround was published.

### Lossless optimization experiment

WebP copies were generated **outside the project** for all five supplied originals. Every copy preserves 1536 × 1024 resolution, complete RGBA pixel equality, text, arrows, labels, icons and layout. They are optimization candidates only, remain inaccurate like their originals, and are not linked/copied into the public asset set. No resized preview, duplicate public asset or optimized public variant was created for a held image. Re-evaluate corrected originals before eventual publication and reuse one approved optimized asset between Documents and Domain.

| Supplied PNG | Original bytes | Pixel-identical lossless WebP bytes | Saved bytes |
| --- | ---: | ---: | ---: |
| `AI Fashion Try-On Methodology Infographic.png` | 1,894,915 | 1,374,976 | 519,939 |
| `AI-Driven Omni-Retail Research Workflow.png` | 1,856,962 | 1,331,284 | 525,678 |
| `GPS-Based Customer Behaviour Research Workflow.png` | 1,928,512 | 1,429,602 | 498,910 |
| `Personalised Marketing Intelligence Flowchart.png` | 1,925,590 | 1,397,922 | 527,668 |
| `Smart Inventory Optimisation Methodology.png` | 1,773,869 | 1,252,294 | 521,575 |

Total supplied originals: **9,379,848 bytes**. External lossless candidates: **6,786,078 bytes**. Public diagram image additions: **zero bytes** because every supplied image is withheld.

### Remaining work

Supply the missing overall architecture and corrected/verified versions of all five methodology images, preferably with editable sources. Resolve the marketing thesis-versus-confirmed-results conflict before producing final result labels. Then add actual image previews with meaningful alt text, width/height, lazy loading, full-size View/Download actions and shared Domain embeds where appropriate; remove the matching pending state only after verification. Original sources should stay out of the publishable file set. Phase 4.4 does not authorize another phase, final packaging, source exclusion for approved academic files, external hosting or whole-site size optimization. The prior 20 MB issue remains deferred, as instructed.

### Phase 4.4 validation and measured sizes

Passed HTML5 parsing of all seven pages, CSS syntax in all three stylesheets, semantic heading order, unique IDs, active navigation and **300 exact-case local links/assets**. All twenty-one Phase 4.3 document cards are preserved with identical parsed content and twelve original file paths/actions. Six additional diagram entries have the requested titles, no fake images and no inactive/broken download controls. No inaccurate diagram is linked or embedded anywhere across the seven pages. Original PNGs, all academic PDF/DOCX files, Domain and the other five HTML pages are unchanged. Only documents.html, css/components.css and README.md were modified.

Chrome passed **28 layouts** across all seven development pages at 375, 768, 1024 and 1440 px, with no horizontal overflow or clipped cards. Nine category links plus the new Research Diagrams jump link passed **40 section-anchor checks** below the header. All twelve original downloads passed **48 visible-focus checks** and completed browser transfers with matching SHA-256 hashes. Ten new-tab PDF previews and the existing same-tab paper view remained working. Seven navigation routes, Enter/Tab mobile menus, reduced motion, HTTP assets/MIME types and direct file-mode page loading passed. Desktop/mobile diagram-entry screenshots were inspected. No actual diagram preview, View/Download or Domain embed is claimed because every image is withheld. Lossless external candidates retain exact dimensions/pixels, so optimization introduces no distortion. Screen-reader operation, other browsers and live hosting were not tested.

Development project including the five held PNG originals: **41,527,090 bytes (41.527 MB)**. Projected approved public source set excluding AGENTS.md, research-source and the five held PNGs: **31,429,021 bytes (31.429 MB)**. Copying the full public-path source folders without those held-image exclusions would total **40,808,869 bytes (40.809 MB)** and include unverified images; that is not an approved delivery set. The approved projection already exceeds 20 MB by **11,429,021 bytes**. No complete size-resolution attempt or final packaging occurred; this issue remains deferred as instructed.

No new public image asset was created. External lossless candidates are not a substitute for academically corrected images. The usual staging directory is byte-for-byte unchanged. No ZIP was created, regenerated or modified; no remote push, repository creation, external upload or deployment occurred. No original thesis/document/image was deleted or overwritten. Phase 4.4 image integration remains pending the missing architecture, corrected diagrams and marketing evidence reconciliation.

## Phase 4.4.1 — draft diagram previews and correction checklist

This update supersedes Phase 4.4’s decision to withhold all image previews. The user explicitly authorized viewing the five existing PNGs **as drafts**, using their actual filenames. All five are present; none is marked missing. The later folder recheck also identified `Smart Omni-Retail System Architecture (1).png`; its card now shows a sixth draft preview. No architecture placeholder remains because the actual image is present. Documents now shows each original PNG with a responsive 3:2 thumbnail, meaningful draft alt text, intrinsic dimensions, lazy loading, Draft — Academic Review Required badge and full-resolution draft View link. No diagram has a download action, verified status or claim that HTML captions corrected its embedded text. The actual PNG bytes and filenames are unchanged. No standardized filename or duplicate asset is required.

The user’s permission covers draft previews; it does not approve inaccurate images as finalized research materials. Domain and all twelve approved academic document cards/links remain unchanged. Prior Phase 4.4 public-set exclusions describe that historical state; a future source set supporting these explicitly authorized draft previews must include the five linked PNG originals (while keeping their draft status), or obtain approval to change that delivery. Submission staging and ZIP remain untouched.

Five draft files displayed: `AI-Driven Omni-Retail Research Workflow.png`, `Smart Inventory Optimisation Methodology.png`, `Personalised Marketing Intelligence Flowchart.png`, `AI Fashion Try-On Methodology Infographic.png`, and `GPS-Based Customer Behaviour Research Workflow.png`, all in assets/diagrams/. Overall architecture is not supplied.

### Embedded-text correction checklist

The following is a proposed image-edit checklist, not a record of applied corrections. No embedded PNG text or research metric was changed. Page numbers refer to physical PDF pages. Marketing values/model are unresolved until the user identifies the authoritative thesis version; existing previously confirmed Domain content is preserved.

| Diagram filename | Embedded text / claim | Correct replacement text or instruction | Supporting academic document | Confirmation / approval |
| --- | --- | --- | --- | --- |
| AI-Driven Omni-Retail Research Workflow.png | Demand Forecasting Model: Time series forecasting (e.g., LSTM, ARIMA, ensemble methods) | Demand Forecasting: XGBoost regression | Research paper III.A; IT22244598_DRAFT.pdf p. 3 | Confirmed |
| AI-Driven Omni-Retail Research Workflow.png | Customer Segmentation: Clustering algorithms (e.g., K-Means) | Customer Segmentation: RFM-based segmentation | Research paper III.B; marketing system overview | Confirmed for paper-based method; final thesis authority needs approval |
| AI-Driven Omni-Retail Research Workflow.png | Promotion Prediction: classification models | Promotion Redemption Classifier — model awaiting authoritative thesis confirmation | Paper III.B versus IT22146588_DRAFT.pdf pp. 3/42/59 | User approval required; do not select XGBoost or Random Forest silently |
| AI-Driven Omni-Retail Research Workflow.png | Size Recommendation: ML classification/regression; Behavioural Classification: ML classification models | Size Recommendation: Random Forest brand-size classifier; Behaviour Classification: Random Forest (Browsing/Transiting) | Paper III.D–E | Confirmed |
| AI-Driven Omni-Retail Research Workflow.png | Outfit Suggestions; User Feedback Analysis; user acceptance testing; compare with existing methods | Remove unsupported completed-stage labels; use Planned evaluation / future work where appropriate | Paper III/V; actual component overviews | Approval/evidence needed for claimed completion |
| Smart Inventory Optimisation Methodology.png | Inventory Intelligence Model: XGBoost Regressor; Recommendation Model: XGBoost Regressor; XGBoost Transfer Recommendation | Inventory Intelligence: stock-health calculations with demand forecasts; Stock Transfer Recommendation: rule-based recommendation engine | IT22244598_DRAFT.pdf pp. 26/49 | Confirmed by supplied draft; do not label every function XGBoost |
| Smart Inventory Optimisation Methodology.png | Random split (e.g., 80/20) | Chronological holdout (training before 2025; 2025 evaluation) | IT22244598_DRAFT.pdf p. 41 | Confirmed |
| Smart Inventory Optimisation Methodology.png | Review & Approve → Execute Stock Transfer → Update Inventory | Manager review → Approve / Reject / Cancel; approved transfer → Execute → Update both inventories → Record and monitor | IT22244598_DRAFT.pdf pp. 14/45/49 | Confirmed; retain actual approval/execution ordering |
| Smart Inventory Optimisation Methodology.png | Confidence interval; confidence score & risk level; Validate Business Impact | Remove unverified confidence claims or label illustrative; Planned business-impact validation | Paper V; inventory thesis limitations | Requires verification/approval |
| Smart Inventory Optimisation Methodology.png | Daily R² 0.9497; monthly R² 0.9353 | Retain daily R² 0.9497 and monthly R² 0.9353; preserve MAE/RMSE as reported | Paper IV.A; inventory thesis p. 3 | Confirmed; these numbers do not need correction |
| Personalised Marketing Intelligence Flowchart.png | XGBoost Regressor (two occurrences) | Promotion Redemption Classifier — authoritative model unresolved | Paper III.B versus marketing thesis pp. 3/42/59 | User approval required: paper XGBoost vs draft tuned Random Forest |
| Personalised Marketing Intelligence Flowchart.png | MAE ~0.142; RMSE ~0.286; R² ~0.92; repeated MAE/RMSE/R² monitoring | Classification evaluation — values unresolved; remove unsupported regression metrics | Paper IV.B; marketing thesis pp. 3/42/47 | Confirmed removal; replacement numeric values need user approval |
| Personalised Marketing Intelligence Flowchart.png | Any proposed replacement accuracy / ROC-AUC | Accuracy and ROC-AUC: unresolved pending authoritative thesis confirmation | Paper 85.5% / 0.819 (figure about 0.934) versus IT22146588_DRAFT.pdf p. 3: 63.3% / 0.672 | User approval required; no numeric substitution made |
| Personalised Marketing Intelligence Flowchart.png | K-Means clustering; product recommendations; sales uplift; cross-module behaviour/product links; Validate Business Impact | RFM-based segmentation where evidenced; label planned/unverified integrations and business validation explicitly | Paper III.B/V; marketing overview and thesis | RFM paper-based correction confirmed; other claims require evidence/approval |
| AI Fashion Try-On Methodology Infographic.png | Generative AI (Diffusion Model); body keypoint/pose processing as implemented pipeline | Google Cloud Vertex AI virtual try-on; Random Forest measurement regression and brand-size classification | Paper III.D | Confirmed; remove unsupported implemented processing steps |
| AI Fashion Try-On Methodology Infographic.png | Sizing evaluation lacks verified accuracy | Brand-size classification accuracy: 88.4% | Paper IV.C; user-confirmed result | Confirmed |
| AI Fashion Try-On Methodology Infographic.png | Customer inputs/pictures; Recommended Size M; Confidence Score 87% | Illustrative inputs and output — not measured research results; remove unverified 87% or label illustrative | Paper III.D/IV.C; virtual try-on overview; no source for 87% | Example labelling confirmed; any retained numeric confidence requires approval |
| AI Fashion Try-On Methodology Infographic.png | SSIM; baseline comparisons; Image Refinement / Clothing Alignment / Quality Enhancement; user acceptance / satisfaction survey | Remove unsupported completed evaluation/processing claims; label planned evaluation where applicable | Paper III.D/V; virtual try-on overview | Requires implementation/evaluation evidence or approval |
| GPS-Based Customer Behaviour Research Workflow.png | Behaviour accuracy: 87.6% | Behaviour classification accuracy: 91.2% | Paper IV.D; user-confirmed headline | Confirmed |
| GPS-Based Customer Behaviour Research Workflow.png | Staff Assistance Recommendation: Random Forest Classifier; Staff Assistance Model Performance: 84.2% | Staff assistance: dwell-time and movement-pattern alert rules; no separate verified model accuracy | Paper III.E; customer behaviour overview | Confirmed: remove unsupported 84.2% |
| GPS-Based Customer Behaviour Research Workflow.png | Browsing / Product Interested / Ready to Purchase / Need Assistance / Other classes | Behaviour classes: Browsing / Transiting; staff assistance alerts evaluated separately | Paper III.E | Confirmed for defined task; do not assert verified purchase prediction |
| GPS-Based Customer Behaviour Research Workflow.png | Transaction/conversion inputs; zone map; CUST_1024 / 3 min 25 sec example; real-world testing | Remove unverified model inputs; Illustrative zone map and customer output; Planned real-world validation | Paper III.E/V; customer behaviour overview | Illustrative/future labels confirmed; additional inputs need evidence/approval |

The supplied architecture must be reviewed for the confirmed MongoDB shared database and distinct Firebase Authentication service. The marketing conflict remains open: the paper’s 85.5% and 0.819 (with a conflicting figure) differ from the supplied draft’s corrected Random Forest 63.3%, ROC-AUC 0.672 and F1 0.711. Draft captions/statuses do not reconcile that conflict. User approval of an authoritative version is required before changing existing research results or finalizing those diagram labels.


### Architecture found during final folder recheck

`assets/diagrams/Smart Omni-Retail System Architecture (1).png` is present (1,663,805 bytes; 1536 × 1024). It is now displayed as a draft with its original filename, lazy preview and view-only full-resolution link. There are five methodology previews plus this architecture preview; **no diagram is missing**. The original architecture image is unchanged, and all six diagrams remain unapproved for final research use. Earlier missing-architecture observations describe the state of the initial folder listing, not the final state.

| Diagram filename | Embedded text / omission | Correct replacement text or instruction | Supporting academic document | Confirmation / approval |
| --- | --- | --- | --- | --- |
| Smart Omni-Retail System Architecture (1).png | Generic Authentication & Authorization; no distinct Firebase Authentication service | Add Firebase Authentication as a separate service, distinct from MongoDB storage | AGENTS.md confirmed stack; user-confirmed architecture; research-paper technology table | Confirmed role; final wiring must match documented implementation |
| Smart Omni-Retail System Architecture (1).png | Explainable AI (SHAP) | Grounded Gemini explanations; SHAP attribution — future work | IT22244598_DRAFT.pdf p. 26 and future-work discussion; inventory overview | Confirmed: SHAP is not established as current implementation |
| Smart Omni-Retail System Architecture (1).png | Generative AI (Outfit Suggestions); Personalised Fashion Advice; Computer Vision (Try-On) | Google Cloud Vertex AI virtual try-on; Random Forest measurement and brand-size recommendation; remove unverified outfit/advice services | Research paper III.D and try-on overview | Verified model roles confirmed; additional services require evidence/approval |
| Smart Omni-Retail System Architecture (1).png | Indoor Navigation; Customer Assistance Detection; Staff Recommendation System | GPS movement tracking; rule-based dwell-time/movement staff alerts | Research paper III.E; behaviour overview | Confirmed for documented task; navigation/recommendation capabilities need evidence |
| Smart Omni-Retail System Architecture (1).png | Product recommendation, system administration, model monitoring and cross-layer integration shown as completed capabilities | Label unverified capabilities/integration as proposed until demonstrated | Paper III/V; individual overviews/theses | Evidence or user approval required |
| Smart Omni-Retail System Architecture (1).png | Nata Storage & Retrieval | Data Storage & Retrieval | PNG text review | Confirmed typographic correction |

### Phase 4.4.1 validation and preservation

Passed HTML5/CSS syntax, heading hierarchy, unique IDs and **312 exact-case local references** across seven pages. All twenty-one original academic document cards, twelve original download paths, original PNG/PDF/DOCX files and six other HTML pages are unchanged. Six PNG preview paths use the actual filenames; six draft-only full-image links open correctly in new tabs. The supplied architecture has a draft preview; no diagram is marked Not Supplied. No diagram download attributes, approved status or corrected-image claim were added.

Chrome passed all seven pages at 375, 768, 1024 and 1440 px (**28 layouts**), with no horizontal overflow. All six preview images loaded at all four widths (**24 checks**), retaining 1536 × 1024 intrinsic resolution and responsive aspect ratio without clipping/distortion. Six full-resolution PNG links opened their actual image URLs; all six draft links passed visible keyboard-focus checks at every width. Desktop/mobile screenshots confirm the draft badge is readable and full-image actions accessible. All twelve actual academic-document downloads completed with source SHA-256 matches; existing PDF views, forty section-anchor checks, mobile Enter/Tab navigation, reduced motion and direct file-mode page loading passed. Screen-reader and other-browser testing were not performed.

Current development project: **43,208,976 bytes (43.209 MB)**. Projected source set supporting the authorized draft previews, excluding AGENTS.md and research-source but including the six linked PNGs: **42,490,755 bytes (42.491 MB)**. It remains over the 20 MB limit; final size resolution remains deferred. No new image assets or duplicate public images were created. Staging remains byte-for-byte unchanged; no ZIP was created or modified, no remote push/deployment occurred, and no original was deleted or overwritten. Modified files: documents.html, css/components.css and README.md.

## Phase 4.4.2 — Supporting Research Materials cleanup

Removed the complete System Architecture Diagrams, Research Methodology Summaries, and Integration & Technical Documentation placeholder cards from the document subsection. These cards duplicated the separate six-image research diagram gallery. Supporting Research Materials now uses the requested description: “The final research paper and supporting system architecture and research methodology diagrams are presented below.” It does not imply academic approval.

The Final Research Paper card is preserved unchanged, including title, description, file metadata and original PDF View/Download paths. Its single-card grid occupies one column across the available subsection width, eliminating empty grid columns and the extra placeholder row; existing card styling remains. The diagram gallery remains a separate subsection with its existing responsive grid. All six draft cards, actual PNG previews, full-resolution view links and Draft — Academic Review Required labels are unchanged. All twelve academic downloads and nine document categories remain. No academic claims, metrics, image contents or original documents were altered. Current card count: eighteen academic document entries (twelve available and six pending/in preparation), plus six draft diagram entries.

Only documents.html, css/components.css and README.md were edited. All other website pages, thesis/proposal/overview files, PDFs and diagrams are preserved. Academic diagram corrections and unresolved marketing results remain pending as recorded in Phase 4.4.1. Submission size resolution remains deferred; this cleanup does not finalize the site or authorize a new phase.

### Phase 4.4.2 validation

Passed HTML5/CSS syntax, heading hierarchy, unique IDs and all 312 local references across seven pages. Confirmed complete removal of the three specified placeholders. Parsed content of all eighteen retained academic cards and all six draft diagram cards matches the phase-start source; the final paper card and six-image gallery are unchanged. Original-file hashes confirm no thesis, proposal, overview, PDF or PNG changes.

Chrome passed seven pages at 375, 768, 1024 and 1440 px (28 layouts), with no horizontal overflow. The paper subsection contains exactly one card and one grid column at every width; the separate diagram grid keeps its responsive layout. All six images loaded without distortion at every width (24 image checks); six full-resolution draft links opened correctly. All twelve academic downloads completed and matched original SHA-256 hashes. Forty category/section anchor checks, visible keyboard focus, Enter/Tab mobile navigation, existing PDF views, reduced motion and direct file-mode pages passed. Desktop/mobile screenshots of the cleaned paper subsection and gallery were inspected. Screen-reader and other-browser testing were not performed.

No ZIP was created or modified, staging remains byte-for-byte unchanged, no remote push/deployment occurred, and no original academic file or image was overwritten or deleted. Diagram academic-review status and the deferred 20 MB submission issue remain unchanged.

## Phase 4.4.3 — Final Research Paper classification

Moved the existing Final Research Paper card from Supporting Research Materials (#supporting-materials) to Other Approved Final Research Documents (#final-documents), replacing only that section’s generic pending placeholder. The paper appears exactly once, remains Available and keeps identical card content, title, description, group/page context, PDF format/size and original View/Download paths. No PDF was copied, renamed or altered. Other valid entries and all unrelated academic statuses remain unchanged. The full-width single-card grid styling follows the paper to its new section.

Other Approved Final Research Documents now describes “Approved final-stage research publications and related academic documents produced by the research group.” Supporting Research Materials now describes “System architecture and research methodology diagrams illustrating the integrated research framework and its four intelligent components. The current diagrams are available as drafts pending academic verification.” It has no paper card or empty paper grid: only the existing separate six-diagram gallery remains. All six draft cards, PNG previews, full-resolution view links and Draft — Academic Review Required badges are preserved without metric/image changes.

The twelve available academic documents and their original files/links remain; the generic pending final-document card was removed. There are seventeen academic document entries (twelve available and five pending/in preparation), plus six unchanged draft diagrams. Existing category and section anchors are unchanged. Prior phase descriptions are historical; this section records the current classification. Modified files: documents.html, css/components.css and README.md. No other website page, thesis, proposal, overview, research metric, original PDF or PNG was modified. Marketing/diagram academic verification and final submission size resolution remain pending; no new phase is started.

### Phase 4.4.3 validation

Passed HTML5/CSS syntax, heading hierarchy, unique IDs and all 312 exact-case local references across seven pages. The Final Research Paper appears exactly once under Other Approved Final Research Documents; its original card content and PDF paths are unchanged. Supporting Research Materials contains only the six unchanged draft diagram cards. All seventeen retained academic cards, twelve original download targets and original academic/image files match the phase-start records.

Chrome passed all seven pages at 375, 768, 1024 and 1440 px (28 layouts), with no horizontal overflow. The relocated paper grid has one card and one column at every width. All six PNG previews loaded at all four widths (24 image checks), and their full-resolution links opened correctly. All twelve actual downloads completed and matched source SHA-256 hashes. Forty section-anchor checks, visible keyboard focus, mobile Enter/Tab navigation, PDF views, reduced motion and direct file-mode pages passed. Mobile paper and desktop gallery screenshots were inspected. Screen-reader and other-browser testing were not performed.

Only documents.html, css/components.css and README.md changed. Submission staging and all original academic files/images remain byte-for-byte unchanged. No duplicate PDF, ZIP creation/modification, remote push or deployment occurred. Diagram academic verification and deferred submission size resolution remain unchanged.

## Phase 4.4.4 ? Academic document category and status corrections

Current classification supersedes historical phase descriptions above. Project Charter is Completed via Microsoft Forms: it was submitted during project registration and has no separate downloadable document or upload requirement. Checklist Documents is Planned; official assessment checklists will be added as they become available during remaining assessment activities. Neither card has a fabricated file or download action.

Section D is now Main Group Research Paper, containing the unchanged Available six-page Final Research Paper, AI-Driven Smart Fashion Retail Recommendation System, with original metadata and View/Download paths. Section E is Main Group Thesis Document, marked In Preparation, and describes the complete group thesis awaiting completion and approval. The paper and individual theses are not presented as the group thesis. Category navigation labels match the new headings; all existing anchor IDs are preserved.

Only documents.html, css/components.css and README.md changed. Completed and Planned use existing status colors through dedicated CSS classes. All other categories, twelve academic download links, six draft diagrams and research findings are preserved. No original PDF/image changes, staging rebuild, ZIP creation/modification, deployment or remote push are authorized or performed. Diagram academic review and final submission size resolution remain deferred; no subsequent phase is started.

### Phase 4.4.4 validation

Passed HTML5/CSS syntax, heading hierarchy, unique IDs and 312 exact-case local references across seven pages. Confirmed four corrected category/status labels and preserved anchor IDs. The paper appears once and its complete card content is unchanged. All five unrelated categories, six draft diagrams and every link attribute match the phase-start source. Original academic/image file hashes, submission staging and existing ZIP records are unchanged. No outdated category references were found in the other six website pages; earlier README phase descriptions remain historical.

Chrome passed seven pages at 375, 768, 1024 and 1440 px (28 layouts), with no horizontal overflow or card clipping. Forty anchor checks, 48 download focus checks, mobile keyboard navigation, PDF views and direct file-mode pages passed. All twelve actual downloads matched source SHA-256 hashes. Six responsive PNG previews loaded at every width (24 checks); all full-resolution draft links worked. The renamed paper section retains its one-card responsive layout; its mobile screenshot was inspected. Screen-reader and other-browser testing were not performed. No new issue was found; prior academic diagram verification and the deferred 20 MB submission limit remain unresolved.

## Phase 4.4.5 - Four permanent individual thesis entries

The existing folder is documents/individual-theses/. No new thesis directory was created. PDF cover pages confirm IT22244598_DRAFT.pdf belongs to W. M. Methsara, with title AI-Driven Smart Inventory and Stock Flow Optimization (120 pages, 3,968,422 bytes), and IT22146588_DRAFT.pdf belongs to J. A. R. K. Wijetunga, with title AI-Driven Personalized Marketing Intelligence (59 pages, 1,605,476 bytes). These originals, filenames, hashes, card content and View/Download links are preserved; both remain Available Draft.

Four permanent researcher-specific cards are present. T. A. Silva (IT22284952, Virtual Try-On & Size Recommendation) and L. A. D. A. S. Perera (IT22243812, Customer Behaviour Tracking & Staff Assistance) are Awaiting PDF. Their cards include component, thesis entry title, a clearly unconfirmed academic title, researcher, student/group IDs, expected PDF format and unconfirmed file size/page count. The existing action area is reserved with an Awaiting PDF message, without links or fake buttons. Available cards retain their verified titles, metadata and actions. The section description now reads: "Individual research theses for the four research components. Available documents can be viewed or downloaded; remaining reports will be added as they are supplied."

### Future thesis file convention

Use documents/individual-theses/ for future PDFs:

| Researcher | Future filename | Current status/file |
| --- | --- | --- |
| W. M. Methsara | IT22244598_Individual_Thesis.pdf | Available Draft: IT22244598_DRAFT.pdf |
| J. A. R. K. Wijetunga | IT22146588_Individual_Thesis.pdf | Available Draft: IT22146588_DRAFT.pdf |
| T. A. Silva | IT22284952_Individual_Thesis.pdf | Awaiting PDF |
| L. A. D. A. S. Perera | IT22243812_Individual_Thesis.pdf | Awaiting PDF |

Existing draft filenames and working links stay unchanged. Expected future filenames are documentation only; no link to a missing file is activated.

### Adding a supplied individual thesis

1. Copy the supplied PDF into documents/individual-theses/ using the matching standardized filename; preserve existing originals.
2. Verify the cover-page student ID, researcher and exact thesis title belong to the intended card.
3. Open the PDF and confirm it is readable and complete.
4. Update only that researcher's card from Awaiting PDF to Available Draft or an explicitly verified final status; fill the exact academic title.
5. Replace the Awaiting PDF message in its existing archive-actions area with the existing View Document and Download Document link pattern. Use the correct relative PDF path; keep accessible labels and the View link's new-tab behavior.
6. Record the actual file size and page count.
7. Validate both links, the downloaded file and responsive layout. Do not redesign the cards or change other researchers' entries. No JavaScript or folder scanning is needed.

Only documents.html and README.md were modified. All other document categories, original academic files, twelve download targets and six draft diagrams remain unchanged. No placeholder PDF, duplicate folder, ZIP creation/modification, staging rebuild, deployment or remote push occurred. Academic diagram review and submission size resolution remain deferred. No subsequent phase is started.

### Phase 4.4.5 validation

Passed HTML5/CSS syntax, heading hierarchy, unique IDs, no-JavaScript checks and all 312 exact-case local references across seven pages. Four thesis cards have the same metadata field order and action-area structure; correct researcher IDs/components and statuses were checked. The two Available Draft cards are unchanged, and both Awaiting PDF cards have no links. All eight other categories, six diagrams and every existing link attribute match the phase-start source. All original academic/image hashes, ZIP records and submission staging are unchanged; the existing thesis folder still contains exactly the two original PDFs.

Chrome passed all seven pages at 375, 768, 1024 and 1440 px (28 layouts), with no horizontal overflow or card clipping. All twelve actual academic downloads, including both original theses, matched source SHA-256 hashes. Forty anchor checks, 48 visible-focus checks, mobile keyboard menus, existing PDF views, reduced motion and direct file-mode pages passed. Six PNG previews loaded at all four widths (24 checks), and all full-resolution image links worked. Desktop and mobile thesis-section screenshots were inspected. Screen-reader and other-browser testing were not performed. The two future PDFs and their exact academic titles/size/page counts remain awaiting supply; no final approval is implied. Diagram verification and the deferred submission size issue remain unchanged.

## Phase 4.4.6 - Main Group Thesis integration

Section E, Main Group Thesis Document (#group-report), is Available and links the existing documents/group-thesis/R26-IT-060_DRAFT.pdf directly. Verified cover title: AI-Driven Smart Fashion Retail Recommendation System; cover document designation: COMMON INTEGRATED SOLUTION REPORT. The four cover-page researchers/student IDs match the group, and internal references on PDF pages 29-30 identify R26-IT-060. This is the supplied group thesis draft, distinct from the six-page Main Group Research Paper and individual theses. No duplicate or new folder was created.

The PDF has 46 pages and 990,299 bytes (0.990299 decimal MB; displayed 0.99 MB). It is unencrypted, has no embedded files and all pages rendered successfully. Declaration/supervisor-certification (page 2) and team-contribution (page 46) signature/date fields are visually blank. Text review found academic identities and general security/privacy descriptions, with no apparent confidential credentials or restricted-distribution marking. This review is not a formal confidentiality audit. The user explicitly approved public distribution of this supplied draft during Phase 4.4.6; this is not final academic assessment approval.

The card shows the verified title, group ID, Main Group Thesis type, PDF size/pages and genuine View Document/Download Document actions. The source PDF is unchanged. All eight other categories, the existing research-paper card/links, individual thesis entries and six draft diagrams are preserved. No research numbers were changed. The group draft still describes Firestore (for example its abstract), conflicting with the user-confirmed MongoDB website architecture; the original remains intact and this does not authorize changing website findings or academically finalizing the document.

### Phase 4.4.6 projected submission size

The projection sums the current source files, excluding AGENTS.md and research-source/, including all thirteen linked academic documents and all six linked draft PNGs; it does not rebuild submission staging or estimate ZIP compression. The earlier approximately 31.429 MB estimate predates the current diagram assets. The new group thesis adds 990,299 bytes (0.990299 MB). The final measured total and excess are recorded below after validation. Original files are not compressed or removed; the previously authorized deferral of the 20 MB size resolution remains in effect.

Modified files: documents.html and README.md only. No ZIP creation/modification, staging changes, deployment or remote push occurred. No original academic PDF/image was altered or deleted; no later phase was started.

### Phase 4.4.6 validation and final size

Passed HTML5/CSS syntax, heading hierarchy, unique IDs, no-JavaScript checks and 314 exact-case local references across seven pages. The Section E title, group/type/format metadata, 46 pages and 0.99 MB display match the verified PDF. All eight other categories and twelve previous download paths remain unchanged. All original academic/image hashes, submission staging and ZIP records are unchanged.

Chrome passed all seven pages at 375, 768, 1024 and 1440 px (28 layouts), without horizontal overflow or card clipping. The group thesis View link opened its PDF in a new tab; all thirteen actual downloads, including the newly linked thesis, matched source SHA-256 hashes. Forty anchor checks, 52 visible download-focus checks, mobile keyboard menus, PDF views, reduced motion and direct file-mode pages passed. Six draft previews loaded at all four widths (24 checks), and all full-resolution image links worked. The mobile group thesis screenshot was inspected. Screen-reader and other-browser testing were not performed.

Final projected source size: 43,498,530 bytes (43.498530 MB); excess above 20,000,000 bytes: 23,498,530 bytes (23.498530 MB). This includes README.md, all linked originals and six draft diagrams, and excludes AGENTS.md and research-source/. It is an uncompressed source projection, not a newly generated submission package. The size limit remains exceeded; no compression, removal, ZIP/staging work, deployment or remote push was performed.

## Phase 4.4.7 - Research milestones and assessment details

Research Group R26-IT-060 and Research Assessment Panel IT-P05 are displayed near the Milestones introduction. The user supplied the confirmed dates/statuses; no panel member names, scores or outcomes were inferred.

| Assessment | Confirmed date | Event status | Allocated Marks | Assessment Results |
| --- | --- | --- | --- | --- |
| Proposal Presentation | 16 March 2026 | Conducted | Not Published | Not Published |
| Progress Presentation 1 (PP1) | 11 May 2026 | Conducted | Not Published | Not Published |
| Progress Presentation 2 (PP2) | 1 September 2026 | Conducted | Not Published | Not Published |
| Final Presentation, Assessment & Viva | 19 October 2026 | Scheduled | Not Published | Not Published |

The final assessment remains upcoming as of 11 October 2026. Conducted means the event occurred and implies no pass/fail result. Four native HTML details/summary assessment dropdowns show the requested descriptions, semantic dates, panel, event status and distinct publication statuses for allocated marks and results. The previous separate Final Assessment and Viva dropdowns were consolidated because they are one confirmed event. Existing presentation/research-paper links are preserved. The separate final-paper timeline entry and historical research activities/evolution remain intact; the four assessment timeline entries now show matching dates and event badges. Outdated unconfirmed-date statements were replaced.

Modified files: milestones.html, css/components.css and README.md. Original academic files, diagrams, document paths, research findings and other pages remain unchanged. Final presentation materials, allocated marks and results remain unavailable. Final submission packaging/size resolution remains postponed; no ZIP creation/modification, staging rebuild, deployment or remote push occurred. No subsequent phase was started.

### Phase 4.4.7 validation

Passed HTML5/CSS syntax, heading hierarchy, unique IDs, no-JavaScript checks and 314 exact-case local references across seven pages. Four dropdowns contain the exact confirmed assessment dates, panel IT-P05, three Conducted statuses, one Scheduled status and eight Not Published metadata values. Outdated To be confirmed assessment wording is absent. Timeline dates match the dropdowns. Historical research evolution and the paper timeline entry are unchanged; every existing link attribute is preserved. Only milestones.html, css/components.css and README.md changed; academic PDFs/images, other pages, submission staging and ZIP records are unchanged.

Chrome passed all seven pages at 375, 768, 1024 and 1440 px (28 layouts), with no horizontal overflow or card clipping. All four assessment dropdowns passed visible-focus and Enter/Space open/close checks at each width (16 dropdown checks); expanded details remained responsive. Mobile final-assessment and desktop introduction/assessment screenshots were inspected. Existing mobile keyboard navigation, forty document anchors, 52 download-focus checks, PDF views, reduced motion and direct file-mode pages passed. All thirteen academic downloads matched source SHA-256 hashes; all six draft previews and full-image links worked. Screen-reader and other-browser testing were not performed.

Allocated marks and assessment results remain Not Published, and final presentation materials remain unsupplied. The 19 October 2026 final assessment is Scheduled as of 11 October 2026; no grade or completion is assumed. Prior diagram academic verification and the over-20-MB submission-size issue remain deferred. No ZIP was created or modified, no staging work occurred, and no deployment or remote push was performed.


## GitHub repository and live website

Public repository: https://github.com/Methsara20/smart-omni-retail-research

GitHub Pages: https://methsara20.github.io/smart-omni-retail-research/

Branch: main. The source-only initial commit was 410c2c69d40606788eaafd3d76abf03e91778cd0; it was pushed in Phase 5.1. Pages was subsequently enabled by the repository owner and was verified built from main at the start of Phase 5.3. Current publication scope is described below; earlier source-only exclusion notes describe historical phase states.

## Phase 5.3 - Documents, presentations and repository cleanup

Thirteen original academic library documents and three presentation PDFs are approved for public GitHub/GitHub Pages distribution. Existing approvals include the four proposals, four overviews and topic assessment form (including their approved signatures and assessment annotations), the two available individual thesis drafts, the research paper and the supplied group thesis draft. The user separately confirmed public distribution of all three presentation PDFs during this phase. Draft thesis designations remain accurate. All files are linked directly at existing paths and retain their original hashes; no duplicate copy or placeholder was created.

The six diagram-card review badges were removed as requested; each image, title, description and responsive preview remains, with neutral View Diagram actions. This is a display-label change only: it does not academically verify the image content or resolve the detailed correction checklist recorded under Phase 4.4.1. Model/workflow/example-value corrections remain open, including the marketing paper versus individual-thesis conflict (85.5% versus 63.3%, disputed ROC-AUC/model choice), inventory rule-based transfer and chronological split, Vertex AI fitting and illustrative confidence, behaviour 91.2% versus diagram values and rule-based assistance, and architecture authentication/SHAP/service labels. Original PNGs and website findings were not changed.

AGENTS.md remains unchanged locally and is ignored through /AGENTS.md. It is removed from current Git tracking, without rewriting history. Historical copies remain accessible through prior commits; inspection found project instructions and public research references, with no recognized credentials. .gitignore allows only the sixteen exact approved binary paths, retaining default exclusions for other academic files, research-source/, credentials, caches, conversion/temp outputs, ZIPs and staging. Four portraits and six diagrams stay tracked.

Unavailable materials remain unavailable: Silva's and Perera's individual thesis PDFs, final presentation, planned assessment checklists and other not-yet-supplied reports. The Project Charter was completed via Microsoft Forms and has no separate PDF. Allocated marks/results remain Not Published and the final assessment remains Scheduled for 19 October 2026 as of 11 October 2026. No missing-file link was activated.

### Public download inventory and live tests

Sizes below are exact original bytes, using decimal MB for card displays. Each URL preserves filename capitalization and encodes spaces. Live results will be recorded after the authorized deployment.

| File / deployed URL | Bytes | HTTP / View / Download |
| --- | ---: | --- |
| [R26-IT-060_DRAFT.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/group-thesis/R26-IT-060_DRAFT.pdf) | 990,299 | Pending live verification |
| [IT22146588_DRAFT.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/individual-theses/IT22146588_DRAFT.pdf) | 1,605,476 | Pending live verification |
| [IT22244598_DRAFT.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/individual-theses/IT22244598_DRAFT.pdf) | 3,968,422 | Pending live verification |
| [IT22146588 - Proposal Report.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/proposal-reports/IT22146588%20-%20Proposal%20Report.pdf) | 4,637,213 | Pending live verification |
| [IT22243812_Proposal_Report.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/proposal-reports/IT22243812_Proposal_Report.pdf) | 1,150,056 | Pending live verification |
| [IT22244598 - Proposal Report .pdf](https://methsara20.github.io/smart-omni-retail-research/documents/proposal-reports/IT22244598%20-%20Proposal%20Report%20.pdf) | 1,468,771 | Pending live verification |
| [IT22284952_Proposal_Report.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/proposal-reports/IT22284952_Proposal_Report.pdf) | 1,176,872 | Pending live verification |
| [An AI Driven Smart Retail Recommendation System.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/research-pdfs/An%20AI%20Driven%20Smart%20Retail%20Recommendation%20System.pdf) | 710,920 | Pending live verification |
| [System_Overview_IT22244598.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/system-overviews/System_Overview_IT22244598.pdf) | 346,944 | Pending live verification |
| [System_Overview_Marketing_Intelligence - RW.docx](https://methsara20.github.io/smart-omni-retail-research/documents/system-overviews/System_Overview_Marketing_Intelligence%20-%20RW.docx) | 27,068 | Pending live verification |
| [System_overview-IT22243812.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/system-overviews/System_overview-IT22243812.pdf) | 12,600 | Pending live verification |
| [System_overview-IT22284952.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/system-overviews/System_overview-IT22284952.pdf) | 11,348 | Pending live verification |
| [TAF R26-IT-60.pdf](https://methsara20.github.io/smart-omni-retail-research/documents/topic-assessment/TAF%20R26-IT-60.pdf) | 2,655,847 | Pending live verification |
| [pp1-presentation.pdf](https://methsara20.github.io/smart-omni-retail-research/presentations/slides/pp1-presentation.pdf) | 3,340,356 | Pending live verification |
| [pp2-presentation.pdf](https://methsara20.github.io/smart-omni-retail-research/presentations/slides/pp2-presentation.pdf) | 2,213,316 | Pending live verification |
| [proposal-presentation.pdf](https://methsara20.github.io/smart-omni-retail-research/presentations/slides/proposal-presentation.pdf) | 7,096,998 | Pending live verification |

### Deployment size and university submission

GitHub Pages deployment assets and the final university package are separate. The deployed tracked-source total will be measured after validation; it includes original documents/presentations and rendering assets, not .git history, AGENTS.md or research-source/. The 20 MB university submission limit remains an unresolved final-submission task. No original PDF/DOCX/PNG is compressed or replaced, no document is removed to meet that limit, and no ZIP or staging package is generated.

Only .gitignore, .gitattributes, documents.html and README.md source text changes are required, plus AGENTS.md tracking removal and sixteen approved binaries added to tracking. No thesis, proposal, research-paper, overview, assessment, presentation or image contents changed. No force-push or history rewrite is permitted.

### Phase 5.3 local validation and publication review

Passed HTML5/CSS syntax, heading hierarchy, unique IDs, no-JavaScript checks and all 314 exact-case local references across seven pages. Thirteen existing academic cards and all other pages remain unchanged. Six diagram images/titles/descriptions and view paths are preserved; the redundant review badges are absent and actions read View Diagram. PDFs rendered and retained recorded page counts/sizes; the Word overview's OOXML content is readable and structurally intact. No recognized credential patterns or unapproved contact details were detected in extracted document text; the scanned proposal/assessment signatures and annotations retain the user's existing explicit public approval. Three slide PDFs retain their correct milestone titles and slide counts (43/44/20), with explicit public-distribution approval this phase. Image-only/scanned pages cannot be fully certified by text extraction; prior visual reviews and explicit approvals remain the publication basis.

Local Chrome passed seven pages at 375, 768, 1024 and 1440 px (28 layouts), with no horizontal overflow/card clipping. All thirteen academic document and three presentation downloads completed and matched original SHA-256 hashes. Six preview images loaded at every width (24 checks), and all six full-resolution views worked. Document anchors, visible keyboard focus, mobile menus, native assessment dropdowns, PDF views, reduced motion and direct file-mode pages passed. The mobile diagram gallery screenshot was inspected. Screen-reader and other-browser testing were not performed. Live validation follows after the authorized push.

.gitattributes marks PDF, DOCX and image formats binary so Git cannot normalize their line endings. This was required because two small overview PDFs were initially detected as text by Git. All sixteen staged document/presentation blobs now exactly match original SHA-256 hashes; no original content was changed. Current publication inventory is 39 tracked files: source/rendering assets, sixteen approved downloads and .gitattributes, without AGENTS.md or research-source/.
