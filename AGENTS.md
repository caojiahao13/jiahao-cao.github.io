# Personal Research Homepage Plan

## Project Goal

Build a polished personal research webpage for Jiahao Cao that can be linked from a department profile and Google Scholar. The site should present Jiahao primarily as a Bayesian statistician and statistical methodologist, with public academic information shown clearly, quickly, and in a form that is easy to maintain.

## Recommended Platform

Use GitHub for development and hosting.

- Keep the repository private while drafting and reviewing the site.
- Preview the site locally during development.
- When the content is approved, publish with GitHub Pages.
- Treat the public GitHub Pages deployment as the release step. Do not enable Pages until the site is ready to be public.

Google Sites remains a fallback if a no-code editor is preferred, but GitHub gives better control over design, publications, files, version history, and long-term portability.

## Source Material

Use these as primary public sources:

- `Personal_docs/CV_resume.pdf`
- `Personal_docs/Google Scholar.html`

Use these as design references:

- `Reference/https-:fengruan.github.io.html`
- `Reference/https-:bingx1990.github.io.html`
- `Reference/https-:sites.google.com:view:xinyanhu.html`
- `Reference/About me - Mihail Eric.html`
- `Reference/How to Make Your Own Academic Website _ Graduate and Postdoctoral Studies _ Rice University.html`

Treat the following as private background unless Jiahao explicitly approves specific content for publication:

- `Personal_docs/PreviousK99Document/`
- Reference letters
- Grant application drafts
- Mentor/co-mentor statements
- Institutional documents

## Public Profile Facts Identified

- Name: Jiahao Cao
- Current role: Postdoctoral Research Fellow, University of Texas Health Science Center at Houston
- Verified email domain: `uth.tmc.edu`
- Public research areas: Bayesian Statistics, Spatial Statistics, Uncertainty Quantification
- Primary research identity: Bayesian statistics, statistical methodology, method development, theory, computation, and machine learning
- Broader methodological interests from CV: Bayesian inference, Bayesian nonparametrics, statistical machine learning, spatial and spatio-temporal statistics, uncertainty quantification, scalable computation, high-dimensional and complex structured data
- Application domains: public health, epidemiology, environmental health, sports analytics, urban systems, and economic or financial functional time series

## Initial Site Structure

Use a simple static site first. A single-page homepage is enough for the first release.

Recommended sections:

1. Header
   - Name
   - Current role and institution
   - Short research identity statement centered on Bayesian statistics, method development, theory, computation, and machine learning
   - Links to email, Google Scholar, CV, GitHub if available

2. About
   - Brief academic biography
   - Current position
   - Research motivation as a statistician and methodologist
   - Application areas as places where the methods are used, not as the main professional identity

3. Research
   - Methodological interests
   - Application areas
   - Optional highlighted projects

4. Publications
   - Published papers
   - Preprints / under review
   - Working papers only if approved for public listing
   - Links to DOI, journal page, arXiv, Scholar, or PDF where available

5. News / Updates
   - Optional small section for new papers, talks, awards, and job updates

6. Teaching and Service
   - Teaching assistant experience
   - Journal reviewing
   - Conference talks

7. Contact
   - Institutional email
   - Department or lab affiliation if confirmed

## Design Direction

Aim for a restrained academic style:

- Clean typography
- Strong publication readability
- Minimal decoration
- Mobile-friendly layout
- Fast-loading static files
- Clear navigation

Avoid a marketing-style homepage. The first screen should immediately identify Jiahao, the research area, and the most useful links.

## Positioning Rules

- Present Jiahao as a Bayesian statistician and statistical methodologist.
- Center method development, theory, computation, uncertainty quantification, and machine learning.
- Describe public health, epidemiology, environmental health, sports analytics, urban systems, and economic or financial problems as application domains.
- Avoid describing Jiahao primarily as a public health researcher.
- Avoid over-weighting institutional application areas in the homepage headline or first paragraph.
- Use application examples to demonstrate the reach of the methods, not to define the core research identity.

## Development Approach

Start with plain static files unless the project later needs a framework.

Recommended first implementation:

- `index.html`
- `styles.css`
- `assets/` for images, CV, and optional icons

This is enough for GitHub Pages and avoids unnecessary build tooling. If the site grows into multiple pages or needs publication data automation, consider adding a static site generator later.

## Privacy Rules

- Do not publish grant documents, recommendation letters, or private drafts.
- Do not include personal email addresses from exported Google pages unless Jiahao confirms they should be public.
- Prefer institutional contact information.
- Keep the repository private until the final content is reviewed.
- Do not enable GitHub Pages until Jiahao approves public release.

## Open Questions Before Public Release

- Confirm preferred public email address.
- Confirm whether to include a profile photo and which photo to use.
- Confirm department/lab title and official affiliation wording.
- Confirm Google Scholar public URL.
- Confirm GitHub, ORCID, personal CV PDF, and LinkedIn links if desired.
- Confirm which working papers should be publicly listed.

## First Build Checklist

- Extract concise bio from CV.
- Draft publication list from CV and Google Scholar.
- Create static homepage.
- Add responsive styling.
- Add downloadable CV only after approval.
- Preview locally.
- Review text and privacy-sensitive content.
- Commit to private GitHub repository.
- Enable GitHub Pages only when ready for public release.
