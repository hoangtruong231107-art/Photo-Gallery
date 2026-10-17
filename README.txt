FIELD NOTES — RESPONSIVE DESIGN PROJECT

Files
- index.html: page content and all nine replacement images with descriptive alt text.
- style.css: mobile-first layout and the four required media queries.

Run locally
1. Keep index.html and style.css in the same folder.
2. Open index.html in a browser. Internet access is needed to load the Unsplash photographs.

How the assignment requirements are covered
- Mobile-first: one-column CSS Grid with a 10px gap; no mobile media query.
- Tablet: @media (min-width: 772px), two columns, circular figures, final figure spans both columns.
- Large screen: @media (min-width: 992px), every third figure spans both columns and figure corners are square. No max-width media query is used.
- Reduced motion: @media (prefers-reduced-motion: reduce) disables smooth scrolling and suppresses transitions.
- Dark color scheme: @media (prefers-color-scheme: dark) changes figure surfaces, type, and border colors.
- All images include meaningful alt text; paragraph content is original replacement copy.

Before submission
1. Run index.html through https://validator.w3.org/ using the direct-input or URL/file-upload option.
2. Run the page through https://wave.webaim.org/ and inspect any reported contrast or structural issues.
3. Test browser widths below 772px, from 772px to 991px, and 992px or wider.
4. Test dark mode and reduced motion in your operating-system accessibility/display settings.
5. Since the starter repository was not accessible from the current environment, this is a clean implementation of the supplied rubric, not a patch of the original starter files.
