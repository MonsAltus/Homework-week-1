# Homework-week-1
## Code Refactoring

### Description:
This website is a landing page for the company Horiseon Social Solution Services, Inc.<br>
The codebase has been refactored with search engine optimization and accessibility in mind.

### Links:
[Website preview](./assets/images/preview.png)<br>
[Link to deployed website](https://monsaltus.github.io/Homework-week-1/)

### Fixes:
#### index.html:
- Added website title.
- Added ID for search-engine-optimization to fix link.
- Improved semantic structure of html by removing various classes and replacing `<div>` with more appropriate elements.
- Added descriptive alt properties to images in `main` element, as they provide context to the written content.
- Added blank alt properties to images in `aside` element, as they only provide aesthetic value.
#### style.css:
- Made various selectors universal after removing unnecessary classes.
- Consolidated css classes `.benefit-lead`, `.benefit-brand`, and `.benefit-cost` under `aside section`.
- Consolidated css classes `.benefit-lead img`, `.benefit-brand img`, and `.benefit-cost img` under `aside img`.
- Consolidated css classes `.benefit-lead h3`, `.benefit-brand h3`, and `.benefit-cost h3` under `aside h3`.
- Consolidated css classes `.search-engine-optimization`, `.online-reputation-management`, and `.social-media-marketing` under `main section`.
- Consolidated css classes `.search-engine-optimization img`, `.online-reputation-management img`, and `.social-media-marketing img` under `main img`.
- Consolidated css classes `.search-engine-optimization h2`, `.online-reputation-management h2`, and `.social-media-marketing h2` under `main h2`.
