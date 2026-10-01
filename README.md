# m5-hw5-Perez-Stephanie
| Issue found | Fix made | Verification |
| --- | --- | --- |
| Navigation text had low contrast | Changed the text color to white in `styles.css` | Re-ran lighthouse; issue no longer appears |
| Body text had low contrast | Changed the text color to black in `styles.css` | Re-ran lighthouse; issue no longer appears |
| Inquiry Box text had low contrast | Changed the text color to black in `styles.css` | Re-ran lighthouse; issue no longer appears |
| Footer text had low contrast | Changed the text color to white in `styles.css` | Re-ran lighthouse; issue no longer appears |
| Page areas used generic `<div>` elements | Added semantic page elements, named the navigation with `aria-label`, and linked the sections to their headings with `aria-labelledby`; kept the existing CSS classes | Checked the page layout and landmarks |
| Section headings skipped from `<h1>` to `<h3>` | Changed the section headings to `<h2>` | Checked heading order and appearance |
| Form fields had placeholders but no labels | Added a visible `<label>` linked to each field by its `id` | Checked that each field has an accessible name |
| “Send Message” was a `<div>` | Changed it to a submit `<button>` and kept the `.submit-btn` class | Checked that it can be reached and activated with a keyboard |
| Phone emoji could be announced unnecessarily | Added `aria-hidden="true"` to the emoji’s `<span>` | Checked that the footer text still reads clearly |
| SEO: Lighthouse reported a missing meta description | Added a page summary with <meta name="description"> in index.html | Re-ran Lighthouse; SEO warning no longer appears |
