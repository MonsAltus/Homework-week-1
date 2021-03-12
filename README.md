# Homework-week-1
## Code Refactoring

### Description:
This website is a landing page for the company Horiseon.<br>
The codebase has been refactored with search engine optimization and accessibility in mind.

### Links:
[Website preview](./assets/images/preview.png)<br>
[Link to deployed website](https://monsaltus.github.io/Homework-week-1/)

### Fixes:
#### index.html:
- Added website title.
- Added ID for search-engine-optimization to fix link.
- Improved symantic structure of html by removing various classes and replacing <div> with more appropriate elements.
- Added descriptive alt properties to images in content class, as they provide context to the written content.
- Added blank alt properies to images in benefits class, as they only provide asthetic value.
#### style.css:
- Made various selectors universal after removing unneccesary classes.
- Consolidated css classes ".benefit-lead", ".benefit-brand", and ".benefit-cost" under ".aside-subsection".
- Consolidated css classes ".benefit-lead img", ".benefit-brand img", and ".benefit-cost img" under "aside img".
- Consolidated css classes ".benefit-lead h3", ".benefit-brand h3", and ".benefit-cost h3" under "aside h3".
- Consolidated css classes ".search-engine-optimization", ".online-reputation-management", and ".social-media-marketing" under ".main-subsection".
- Consolidated css classes ".search-engine-optimization img", ".online-reputation-management img", and ".social-media-marketing img" under "main img".
- Consolidated css classes ".search-engine-optimization h2", ".online-reputation-management h2", and ".social-media-marketing h2" under "main h2".