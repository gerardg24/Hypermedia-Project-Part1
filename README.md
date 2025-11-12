# Hypermedia-Project-Part1
The design and code of my personal portfolio
## Project analysis, Information architecture

The information architecture of this portfolio is built on a high-contrast, "split-screen" layout designed for optimal usability on desktop and mobile.

On desktop, the page is divided into two vertical 50vw columns. The left column (`#Portada`) acts as a persistent "Identity Panel." It uses `position: sticky`, ensuring that the user's core identity—profile picture, name, title, and contact links—remains visible at all times. This strategic decision keeps key information and calls-to-action (like social links) accessible, regardless of the user's scroll position.

The right column (`#PortadaDreta`) serves as the scrollable "Content Panel." The information here is structured in a logical, top-down narrative that mirrors a traditional CV. It begins with "Professional Experience," immediately followed by "Academic Experience," as this is often the primary information recruiters seek. This is followed by "Skills" to quantify abilities, which are then validated by the "Projects" section acting as a portfolio. The entire page concludes with the "About Me" section, providing a personal narrative.

This architecture is fully responsive. On screens narrower than 900px (via `@media` query), the layout collapses into a single column (`flex-direction: column`). The Identity Panel stacks on top, followed by the Content Panel, creating a natural, linear, and easy-to-navigate flow for mobile users.

---

## Project analysis, Visual design

The visual design was developed to be modern, professional, and "alive," using a minimalist color palette with a strong, high-contrast accent.

The core design decision is the asymmetrical light/dark theme. The left "Identity Panel" uses a dark, subtly animated gradient (`linear-gradient(270deg, #1a1a1a, #545454, #0f0f0f)`). This creates a premium, dynamic feel and serves as a high-contrast background for the white text and the user's profile picture, which is softened with a 50% border-radius.

In contrast, the right "Content Panel" uses a neutral light-grey (`#b0b0b0`) background, which provides a clean, readable canvas for the main content. The content itself (like projects and academic history) is placed on white "cards" (`.targeta-projecte`) to create a sense of depth and organization.

The primary accent color is a vibrant yellow (`#ffff82`). This was chosen specifically to add "life" and draw the eye. It is used sparingly but effectively on the user's title (`#Dev`) and as a thick `border-bottom` on all section headers (`.capcalera-seccio`). These headers themselves use a dark gradient to stand out from the light background.

For typography, the serif font "Georgia" is used site-wide. This was a deliberate choice over a standard sans-serif font to convey a sense of professionalism, elegance, and reliability. Finally, subtle micro-interactions, like hover effects on links and project cards, provide user feedback and contribute to the dynamic feel of the page.

---

Public link --> https://gerardg24.github.io/Hypermedia-Project-Part1/
