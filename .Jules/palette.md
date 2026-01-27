## 2026-01-27 - [GitHub Profile Accessibility & UX]
**Learning:** Social media icons in GitHub profile READMEs often use usernames as alt text, which is unhelpful for screen readers. Using the platform name (e.g., "Twitter") is much more accessible. Additionally, long profiles benefit significantly from a "Back to Top" navigation element.
**Action:** Always check social icon alt text and consider adding a "Back to Top" link for long READMEs.

## 2026-01-27 - [Broken HTML in Markdown Tables]
**Learning:** Complex layout attempts in Markdown using nested HTML `<table>` and `<div>` tags are prone to structural errors that can cause rendering issues. A single, clean `<table>` structure is more robust and easier to maintain.
**Action:** Simplify nested table structures in READMEs to improve maintainability and rendering consistency.

## 2026-01-27 - [URL Encoding for Dynamic SVGs]
**Learning:** When using dynamic SVG services like 'readme-typing-svg', special characters and emojis in the URL parameters MUST be URL-encoded (e.g., 👋 to %F0%9F%91%8B) to ensure they load correctly across all browsers and GitHub's image proxy (Camo). Literal emojis in URLs can cause the image to break.
**Action:** Always URL-encode parameters for external image services in READMEs.
