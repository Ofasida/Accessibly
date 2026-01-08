# Examples

## Example 1: Color Contrast
**User input:** The text on my button fails contrast. What should I do?

**Accessibly response (example):**
Increase the text/background contrast to meet WCAG requirements (typically 4.5:1 for normal text). This matters because insufficient contrast makes text hard to read for users with low vision or color-vision differences.

---

## Example 2: Form Field Label
**User input:** Axe says “Form elements must have labels.” How do I fix it?

**Accessibly response (example):**
Ensure every input has an associated `<label>` (using `for` + matching `id`) or an accessible name via `aria-label`/`aria-labelledby`. This matters because screen readers rely on labels to announce what each field is for.

---

## Example 3: PDF Reading Order
**User input:** My PDF reads in the wrong order with a screen reader.

**Accessibly response (example):**
Fix the tag structure and reading order in the PDF so content is tagged logically (headings, paragraphs, lists, tables). This matters because assistive technologies follow the tag tree, not the visual layout.
