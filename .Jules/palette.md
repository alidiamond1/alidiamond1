## 2026-01-27 - [GitHub Profile Accessibility & UX]
**Learning:** Social media icons in GitHub profile READMEs often use usernames as alt text, which is unhelpful for screen readers. Using the platform name (e.g., "Twitter") is much more accessible. Additionally, long profiles benefit significantly from a "Back to Top" navigation element.
**Action:** Always check social icon alt text and consider adding a "Back to Top" link for long READMEs.

## 2026-01-27 - [Broken HTML in Markdown Tables]
**Learning:** Complex layout attempts in Markdown using nested HTML <table> and <div> tags are prone to structural errors that can cause rendering issues. A single, clean <table> structure is more robust and easier to maintain.
**Action:** Simplify nested table structures in READMEs to improve maintainability and rendering consistency.

## 2026-01-27 - [URL Encoding for Dynamic SVGs]
**Learning:** When using dynamic SVG services like 'readme-typing-svg', special characters and emojis in the URL parameters MUST be URL-encoded (e.g., 👋 to %F0%9F%91%8B) to ensure they load correctly across all browsers and GitHub's image proxy (Camo). Literal emojis in URLs can cause the image to break.
**Action:** Always URL-encode parameters for external image services in READMEs.

## 2026-01-27 - [Unified Icon Sets for Profile UX]
**Learning:** Using individual icons from various sources often leads to inconsistent sizing, styles, and broken links. Adopting a unified icon set like 'Skill Icons' (skillicons.dev) provides a much more polished, professional, and stable UI for technical profiles.
**Action:** Prefer unified icon sets over individual image links for listing technical skills in READMEs.

## 2026-01-27 - [Individually Clickable Skill Icons]
**Learning:** While grouping icons into a single image (like Skill Icons combined) is cleaner code-wise, it prevents users from clicking individual technologies to see documentation. For developers who want to showcase specific proficiencies with deep links, individual icons wrapped in <a> tags are superior for UX and information density.
**Action:** Use individual icons instead of grouped images when the user wants each skill to be a separate, clickable link.
