# Mohammad Ayaan Khan - Personal Resume Website

A responsive HTML/CSS resume website for Mohammad Ayaan Khan, an IIM Bangalore BBA DBE student. The design uses warm charcoal, cream, burnt orange, Barlow Condensed headings and DM Sans body text.

## Preview

Open `index.html` in a browser. Keep `styles.css` and `assets/` beside it. All fonts are local, so the website works offline and requires no build step or JavaScript.

## Structure

- `index.html`: semantic introduction, about, education, leadership, skills, learning and contact sections.
- `styles.css`: palette, typography, responsive layouts, interaction states and print rules.
- `assets/fonts/`: two local fonts and their copyright/license notices.

## CSS assignment techniques

| Requirement | Implementation |
| --- | --- |
| Consistent design values | `:root` custom properties for colours, typography and spacing |
| Typography | Local `@font-face` fonts, responsive `clamp()` headings and readable line height |
| Selectors | Element defaults, reusable classes and unique section IDs |
| Flexbox | Header, navigation and action alignment |
| Grid | Hero, section headings, education rows and skills |
| Positioning | Sticky navigation and a fixed keyboard skip link |
| Spacing | `border-box`, shared spacing values and a centred maximum-width container |
| Responsive design | Media queries at `60rem` and `40rem` |
| Accessibility | Heading hierarchy, persistent link cues, hover/focus states and anchor offsets |
| Motion preferences | `prefers-reduced-motion` disables smooth scrolling |
| Printing | A light, ink-efficient print stylesheet |

## Content and privacy

Career interests are aspirations. Previous BMS enrolment is explicitly incomplete, and CMA US and both coursework items are in progress. Reported achievements are attributed to personal reports. The site contains no private ID document, phone number or original resume download.

## Verification

Checked in Microsoft Edge at 375px, 768px and 1440px: no horizontal overflow; anchors, keyboard activation, focus, heading order, CSS/font loading, reduced motion and print rules passed. Tested text colour combinations reach at least 5.02:1 contrast. Other browsers and assistive technologies have not been tested.

## Hosting

Publish the repository root as a static website. If using GitHub Pages, keep `index.html` at the top level of the configured publishing folder. Verify the deployment's actual URL after publishing; the repository URL is a separate address.
