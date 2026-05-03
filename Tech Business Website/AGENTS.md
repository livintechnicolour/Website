# AI Agent Instructions - Tech Business Website

## Project Overview
A service-focused website for "Tech Confident by Liv," offering tech support and assistance to users.  
Static HTML/CSS site with a hero section, services, and contact call-to-action.

## Code Standards & Commitments

### HTML
- Use semantic HTML5 (`<header>`, `<section>`, `<nav>`, etc.)
- Keep class naming consistent: kebab-case (e.g., `hero-title`, `service-card`)
- Fix syntax: ensure all quotes match, no extra spaces before `>`
- Fix attribute syntax: use `class=""` or `id=""`, never bare `=`

### CSS
- Use standard CSS properties: `color` (not `colour`), `background-color` (not `background:`)
- All declarations must end with `;`
- Follow the existing structure: RESET → GLOBAL → HEADER → HERO → SERVICES
- Color palette: Primary #6ec6c5 (teal), Dark text #1a1f36, White backgrounds

### When Making Changes
1. **Validate syntax** before considering work complete (no typos in properties/attributes)
2. **Preserve structure** — don't reorganize sections without explicit request
3. **Test responsiveness** — ensure mobile layout works (viewport meta tag present)
4. **Link consistency** — verify `href` targets match section `id` attributes

## Common Issues to Avoid
- CSS color properties: `color:` for text, `background-color:` for backgrounds
- HTML attributes: always quote values, proper syntax for boolean attributes
- Navigation links: ensure `href` matches actual section IDs (currently `#help`, `#contact`)

## Quick Commands
- Validate HTML: Check for unclosed tags, mismatched quotes, invalid attributes
- Validate CSS: Check for undefined properties, missing semicolons
