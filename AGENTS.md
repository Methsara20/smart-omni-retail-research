AGENTS.md — Smart Omni-Retail Academic Research Website
Project purpose
This repository contains the academic information website for the SLIIT final-year research project Smart Omni-Retail System (Group ID: R26-IT-060). It documents the research journey, methodology, architecture, findings, deliverables, milestones, presentations, and team. It is not the Flutter/FastAPI/MongoDB retail product and must not be converted into that product.
Non-negotiable technology rules
- Use HTML5 and CSS3 only for the website. Do not add JavaScript, TypeScript, React, Next.js, Vue, Angular, Bootstrap, Tailwind, jQuery, Node.js, build tools, backend services, or databases.
- Keep all pages working as static files with relative paths. Do not require installation or a build command.
- Use semantic HTML, CSS Grid/Flexbox, responsive media queries, and CSS-only interactions where practical. Never introduce a nonfunctional control merely for appearance.
- Keep the entire Courseweb submission under 20 MB, including assets and approved downloadable materials. Exclude development-only research sources from the final submission package.
Existing structure and navigation
Preserve the seven required pages and their URLs:
1. index.html — Home
2. domain.html — Domain (literature survey, research gap/problem, objectives, methodology, technologies, findings)
3. milestones.html — Milestones (assessments, verified dates and allocated marks)
4. documents.html — Documents (approved research deliverables)
5. presentations.html — Presentations (proposal, PP1, PP2, final slides)
6. about.html — About Us (verified team details)
7. contact.html — Contact Us (verified contact information)
Existing CSS: css/style.css, css/components.css, css/responsive.css. Existing asset locations: assets/images/, assets/diagrams/, assets/icons/; approved downloadable documents: documents/research-pdfs/; slides: presentations/slides/. research-source/ contains development references and should not be publicly linked or included in the final delivery unless explicitly approved.
Visual design contract
- Preserve the premium hybrid theme: dark navy futuristic hero/header, clean light academic content, restrained cyan/blue accents, sophisticated typography, spacious layout, and subtle effects.
- Preserve existing Phase 1 components, navigation, footer, and responsive behavior unless a task explicitly requests changes.
- Favor readable research information over flashy animations. Avoid ecommerce storefronts, fake dashboards, stock-product catalogs, login screens, and excessive neon/glass effects.
- Maintain visual consistency across all seven pages. Reuse CSS classes and design tokens; avoid duplicating styles.
- Support reduced motion, visible keyboard focus, sufficient contrast, semantic heading order, and accessible CSS-only mobile navigation.
Academic content and source of truth
- Primary reference: research-source/final-research-paper.pdf, when present and readable. Read relevant sections before writing research content. If unavailable or unreadable, ask for it rather than guessing.
- Follow the supplied university Website.pdf guidelines when available. The academic site must document the research from proposal through final assessment.
- Treat the four functions as one integrated research system:
  1. AI-Driven Smart Inventory & Stock Flow Optimisation
  2. AI-Driven Personalised Marketing Intelligence
  3. AI-Based Virtual Try-On & Size Recommendation
  4. GPS-Based Customer Behaviour Tracking & Staff Assistance
- Research product architecture: Flutter Web/Dart interface; FastAPI/Python services; MongoDB shared data; Firebase Authentication; domain-specific XGBoost/Random Forest models and generative AI/RAG services. These are research-system technologies, not dependencies of this academic website.
- Never fabricate citations, publication details, results, datasets, timelines, assessment weights, author details, supervisors, contact details, document links, or deployment status. Mark missing information clearly and request verification.
- Do not claim production deployment, business impact, security compliance, or complete real-world validation without evidence. Disclose that evaluation used partially simulated/prepared data where relevant.
Confirmed headline results and known discrepancies
Use these user-confirmed final headline results:
- Daily inventory demand forecasting: R² = 0.9497 (MAE 0.5418; RMSE 0.9436).
- Personalised marketing redemption classification: accuracy = 85.5%.
- Brand-specific size classification: accuracy = 88.4% (weighted F1 = 0.881).
- Customer behaviour classification: accuracy = 91.2% (weighted F1 = 0.910).
The research paper's marketing abstract says 78.3%, while its results section says 85.5%; the user confirmed 85.5% for the website. The marketing ROC-AUC is 0.819 in text but approximately 0.934 in a figure. Do not silently reconcile this discrepancy; avoid publishing the disputed ROC-AUC until verified, or explicitly flag it for review. Never describe R² as classification accuracy.
Work discipline
1. Inspect existing files and this instruction file before editing.
2. Summarize the requested scope and identify the minimum files to modify.
3. Implement the requested phase only; do not start subsequent phases without authorization.
4. Preserve completed pages and avoid unrelated refactors or redesigns.
5. Use genuine files for document/slide links; do not create dead links or pretend placeholder files exist.
6. Never delete or overwrite user documents or source material without explicit permission.
7. Update README.md with actual completion status and outstanding tasks.
8. Report any unsupported source claims, conflicting results, or missing materials.
Validation checklist
Before reporting completion:
- Confirm seven navigation routes and all local asset/CSS paths resolve.
- Verify HTML semantics, heading hierarchy, links, keyboard access, focus styles, and responsive mobile menu.
- Check layouts at approximately 375, 768, 1024, and 1440 px when browser testing is available; inspect for overflow, clipping, overlaps, and illegible diagrams.
- Verify the project contains no JavaScript and has no external framework/build dependencies.
- Check displayed research numbers against the confirmed values and paper.
- Confirm submission package size stays under 20 MB and excludes unapproved development-only material.
- State what was tested and what was not; do not claim screenshot, browser, or accessibility testing that was not performed.
Phase status
- Phase 1: Home page, design system, navigation/footer, responsive foundation, and six initial placeholder pages reported complete.
- Phase 2: Domain and Methodology page; work only on explicit instruction and check current files to determine actual progress.
- Later phases: Milestones, Documents, Presentations, About Us, Contact Us, final QA and Courseweb submission packaging. Do not assume these are complete.
Completion report format
At the end of each task, provide a concise report of: files created/changed, implemented sections, source documents used, validation actually performed, unresolved issues, and next phase remaining. Do not start the next phase automatically.