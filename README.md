# Shopify Sections Library

A set of reusable, customizable Shopify 2.0 sections I use across client stores. Each section is self-contained with its own schema, so you can drop the `.liquid` file into any theme's `sections/` folder and it shows up in the theme editor right away — no extra setup.

I built these over time while working on different stores (fashion, handicraft, home decor, pharma) and cleaned them up here so they're easy to reuse.

## What's inside

| Section | What it does |
|---|---|
| `hero-banner.liquid` | Full-width hero with image, heading, subtext and a CTA button. Mobile + desktop image support. |
| `faq-accordion.liquid` | Accordion FAQ built with blocks, add as many Q&A items as you want from the editor. |
| `product-slider.liquid` | Horizontal product carousel from any collection. Configurable products-per-row. |
| `testimonials.liquid` | Customer review grid with star rating and author. |
| `announcement-bar.liquid` | Top announcement bar with optional link, custom colors and dismiss option. |

## How to use

Copy the section file you want into your theme's `sections/` folder, then open the theme editor (Online Store, Themes, Customize), click **Add section** and pick it from the list. Everything is editable from the section settings, so no code changes are needed. If you use Shopify CLI, run `shopify theme dev` and add the section from the editor the same way.

## Notes

- Built for Online Store 2.0 themes (Dawn-compatible).
- All settings use the standard schema, so they work with the native theme editor.
- CSS is scoped per section to avoid clashing with theme styles.

## License

MIT — free to use in your own projects. A credit is appreciated but not required.

---

Made by Nitesh Kumawat — Shopify & front-end developer.
Open to freelance / remote work: niteshkumawat911@gmail.com
