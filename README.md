# OBE Faculty Learning Lab — Promotional Website

A responsive, animated, static website for validating interest in a planned Udemy course on Outcome-Based Education (OBE) in Higher Education.

## Contents

- `index.html` — website structure and page copy
- `styles.css` — responsive visual styling, gradients, animations and mobile layout
- `script.js` — mobile navigation and reveal-on-scroll animations
- `assets/favicon.svg` — simple OBE favicon

## Survey connection

The website embeds your deployed Apps Script survey and provides a direct-open fallback link.

Survey URL:
https://script.google.com/macros/s/AKfycbxUQogr53IBkDx85DEHsyUV-re0mRpXl-nJowqAbdNMElYxv_vZ-FmmvullAzzrtzf4/exec

If the embed does not appear due to Google deployment permissions or browser restrictions, the fallback link opens the survey in a separate tab. Ensure the Apps Script web app deployment allows the intended respondents to access it.

## Deploy using GitHub Pages

1. Create a GitHub repository (for example, `obe-faculty-course-landing-page`).
2. Upload all files and folders in this package to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then Save.
6. Wait for GitHub Pages to publish. Your site will be available at a URL similar to:
   `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Customise before publishing

- Replace “TP” in the instructor visual with your initials, or replace it with a profile photo.
- Add your full name, profile, qualifications and relevant OBE/NBA experience in the instructor section.
- Edit the course topics to match your final curriculum.
- If you want to change the survey link, replace the URL in both the iframe and the fallback link inside `index.html`.
- Add a privacy statement if you collect personal information, explaining what you collect and how it will be used.

## Initial market research (directional, not a market-size estimate)

Research performed on 21 November 2026 found signals of an existing market for OBE-related professional development:

- Class Central lists a Udemy course titled **Outcome Based Education (OBE) & Academic Quality Assurance**, reporting about 2,000 ratings, a 4.4 rating, and a course length of about 8h 55m. Treat these figures as third-party listing snapshots and re-check them before making promotional claims.
- Udemy also has a course titled **Introduction to Outcome Based Education**, covering fundamentals, learning outcomes, alignment, assessment, implementation and continuous improvement.
- Recent faculty-development and accreditation workshops list practical topics such as measurable Course Outcomes, CO–PO mapping, assessment/attainment, documentation, and continuous improvement.

These signals suggest that there is interest and competition. A differentiated practical course for faculty—with guided examples, templates, assessment design, mapping, attainment, and improvement workflows—may be worth testing. The survey is intended to validate interest and willingness to pay before significant production investment.

### Research references

- Class Central course listing: https://www.classcentral.com/course/udemy-outcome-based-education-and-academic-quality-assurance-97601
- Udemy: Introduction to Outcome Based Education: https://www.udemy.com/course/introduction-to-outcome-based-education/
- NITTTR / OBE FDP brochure (search result): https://www.spit.ac.in/wp-content/uploads/2026/06/FDP_Brochure_OBE_IQAC_SP_IT_NITTTR.pdf
- VIT faculty development programme (search result): https://ebooks.vit.ac.in/files/TLCE/Event-Brochure/Jan-2026/27-Jan-26-Outcome-Based-Education-Defining-Course-Outcomes-and-Mapping-to-Program-Outcomes.pdf

## Notes

- The site is a pre-launch research page, not a course sales page.
- Do not add claims about course availability, certificates, enrolment, outcomes, or pricing until confirmed.
- The page uses Google Fonts from the web; if offline, the system fonts remain as fallbacks.
