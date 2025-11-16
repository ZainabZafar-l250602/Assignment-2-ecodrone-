# EcoDrone Mini-Site

## Project Overview
**EcoDrone** is a fictional eco-friendly drone company. This project is a **responsive single-page website** showcasing the product’s features and a **smart join-us form**. The website is built using **HTML5 and CSS3 only**, without JavaScript or external frameworks.

**Core Features:**
- Fully responsive layout using **CSS Grid** for main sections and **Flexbox** for components.
- Three CSS-only interactive components:
  1. Hero button with hover/focus effects
  2. Feature cards with hover/focus animation
  3. Custom checkboxes and radio buttons in the form
- Fully functional and accessible form:
  - Text inputs (name, email)
  - Checkboxes (interests)
  - Radio buttons (subscription plan)
  - Select dropdown (country)
  - Textarea (message)
  - Submit button
- Accessibility considerations: proper labels, `fieldset` and `legend`, `tabindex`, focus outlines, and ARIA labels on SVGs.

---

## File Structure

**Explanation:**
- **index.html** – Contains the main structure, semantic sections, and the smart form.  
- **styles.css** – Styles for the layout, responsive design, and interactive components.  
- **assets/** – Holds images and the custom SVG for icons or logos.  
- **screenshots/** – Contains images showing mobile, tablet, desktop views, and form interaction.  
- **README.md** – Explains the project, design decisions, and provides references to validation, Git history, and live link.

## Design Rationale

1. **Color Scheme:**  
   Green tones (#27ae60, #2ecc71) to convey sustainability and eco-friendliness.

2. **Layout:**  
   - CSS Grid for the **features section**, allowing responsive card arrangement.  
   - Flexbox for **header navigation** and **form elements**, ensuring proper alignment.

3. **Accessibility:**  
   - All form fields have proper `<label>` tags.  
   - Focus states on buttons, links, and interactive cards.  
   - SVGs include `role="img"` and `aria-label` attributes for screen readers.  
   - Keyboard navigation supported with `tabindex` and visible outlines.

4. **Interactive Components:**  
   - Hero button enlarges slightly on hover/focus.  
   - Feature cards lift and change background color on hover/focus.  
   - Custom checkboxes and radio buttons use CSS pseudo-elements for visual feedback.

---

## Screenshots

### Desktop View
![Desktop Screenshot](screenshots/desktop.png)

### Tablet View
![Tablet Screenshot](screenshots/tablet.png)

### Mobile View
![Mobile Screenshot](screenshots/mobile.png)

### Form Interaction
![Form Screenshot](screenshots/form.png)

---

## HTML & CSS Validator Proofs

- [W3C HTML Validator](https://validator.w3.org/) - passed ✅  
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - passed ✅  

*Screenshots of validator results can be saved in the `screenshots/` folder.*

---

## Responsive Design

The site uses **three breakpoints**:

| Device       | Breakpoint |
|-------------|------------|
| Mobile      | ≤480px     |
| Tablet      | ≤768px     |
| Desktop     | >768px     |

The layout adapts using CSS Grid and Flexbox to maintain readability and usability across devices.

---

## Git History

The project includes **at least 6 commits**, demonstrating incremental development:

1. Initial project setup with HTML skeleton  
2. Added header and hero section  
3. Added features section with CSS Grid  
4. Added form with input fields  
5. Styled form with custom checkboxes and radio buttons  
6. Responsive design and accessibility improvements  

---

## GitHub Pages Link

The live website is hosted at:  
[https://yourusername.github.io/EcoDrone](https://yourusername.github.io/EcoDrone)

---

## Notes

- All assets are included in the `assets/` folder.  
- The site is fully functional **without JavaScript**.  
- The site has been tested on Chrome, Firefox, and Edge at desktop, tablet, and mobile widths.