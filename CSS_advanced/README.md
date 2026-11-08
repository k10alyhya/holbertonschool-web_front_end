
## Tasks
| # | File | Description |
|---|------|-------------|
| 0 | `images/` | Download project images (logos, favicon, 10 Unsplash pictures) |
| 1 | `styles/1-style.css` | Smooth scrolling on the `html` element |
| 2 | `styles/2-style.css` | Text colors and `.visually-hidden` |
| 3 | `styles/3-style.css` | Color custom properties in `:root` |
| 4 | `styles/4-style.css` | Font family variables (base and title) |
| 5 | `styles/5-style.css` | Font size variables and `62.5%` root size |
| 6 | `styles/6-style.css` | Font weight variables |
| 7 | `styles/7-style.css` | Google Fonts (Open Sans, Raleway) |
| 8 | `styles/8-style.css` | Line height variables |
| 9 | `styles/9-style.css` | Remove default link decoration |
| 10 | `styles/10-style.css` | Center section headers |
| 11 | `styles/11-style.css` | Section tagline styles (uppercase, bold) |
| 12 | `styles/12-style.css` | Section title styles |
| 13 | `styles/13-style.css` | Link pseudo-classes (LVHA order) |
| 14 | `styles/14-style.css` | normalize.css v8.0.1 |
| 15 | `styles/15-style.css` | Universal `box-sizing: border-box` |
| 16 | `styles/16-style.css` | Centered 960px container |
| 17 | `styles/17-style.css` | Section, header, body and footer padding |
| 18 | `styles/18-style.css` | Navbar (float, list reset, hover) |
| 19 | `styles/19-style.css` | Float grid columns and footer styles |
| 20 | `styles/20-style.css` | Clearfix after each row |
| 21 | `styles/21-style.css` | Shared `[class^="col-"]` selector |
| 22 | `styles/22-style.css` | Dark theme with `data-section-theme` |
| 23 | `styles/23-style.css` | Fix footer address and SVG icons for dark theme |
| 24 | `styles/24-style.css` | Service cards background and hover |
| 25 | `styles/25-style.css` | Outlined buttons with hover state |
| 26 | `styles/26-style.css` | Rounded testimonial avatars and cite |
| 27 | `styles/27-style.css` | Hero section sizing and padding |
| 28 | `styles/28-style.css` | Header padding and absolutely positioned logo |
| 29 | `styles/29-style.css` | Nav link `::before` hover bar |
| 30 | `styles/30-style.css` | Works cards: `object-fit` and hover overlay |
| 31 | `styles/31-style.css` | Decorative quote mark on testimonials |
| 32 | `styles/32-style.css` | Transitions and transforms |

## Key Concepts Applied
- **CSS variables**: every color, font, size and spacing lives in `:root`, and the dark theme only redefines a few of them
- **normalize.css** placed first so custom rules can override it
- **Float grid** with `border-box` and a clearfix (`.row::after`)
- **Specificity**: shared `[class^="col-"]` rule placed before the specific column widths
- **Positioning**: `relative` parent + `absolute` child (logo, nav bar, work cards)
- **Transitions** on `transform` for smooth, performant hover effects

## Author
Khaled Al-Yahya — Holberton School
EOF
