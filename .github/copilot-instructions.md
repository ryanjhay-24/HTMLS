# Copilot Instructions for Lowkey Legacy Agency Website

This project is a simple static website for the Lowkey Legacy Agency, focused on promoting Bigo Live streamers. The codebase consists of two main files: `index.html` and `styles.css`.

## Project Structure
- `index.html`: Main HTML file. Uses Bootstrap 5 via CDN for layout and components. Contains sections for About, Streamers, Contact, and Footer.
- `styles.css`: Custom styles for branding and layout tweaks. Extends Bootstrap defaults.

## Key Patterns & Conventions
- **Bootstrap Integration**: All layout and UI components use Bootstrap classes. Custom styles are added in `styles.css`.
- **Image & Link Placeholders**: Replace `[Image URL ...]`, `[Streamer 1 Name]`, `[Bigo Live Link ...]`, and `[your.email@example.com]` with real data when updating content.
- **Section Structure**: Each major section (`about`, `streamers`, `contact`) is wrapped in a Bootstrap container for consistent spacing.
- **Cards for Streamers**: Streamer profiles use Bootstrap cards. Add more streamers by duplicating the card markup in the `#streamers` section.
- **Header Background**: Set the header background image in `styles.css` by updating the URL placeholder.

## Developer Workflow
- **No build step required**: Edit HTML and CSS directly. Changes are reflected immediately in the browser.
- **No tests or scripts**: This is a static site; there are no automated tests or build tools.
- **Debugging**: Use browser DevTools to inspect layout and styles. Bootstrap's grid and utility classes are used throughout.

## Integration Points
- **Bootstrap CDN**: External dependency for UI components. No local JS/CSS files required.
- **Image Hosting**: Use direct URLs for images (e.g., streamer photos, header background).
- **Contact & Social Links**: Update placeholders with real contact info and social media URLs.

## Example: Adding a New Streamer
1. Duplicate a `<div class="col-md-4">...</div>` block in the `#streamers` section.
2. Update the image URL, name, description, and Bigo Live link.

## Customization Tips
- Update the header background image in `styles.css` for branding.
- Add more sections or modify layout using Bootstrap classes.
- For advanced features (forms, interactivity), add custom JS or use Bootstrap components.

## References
- Key files: `index.html`, `styles.css`
- Bootstrap documentation: https://getbootstrap.com/docs/5.3/getting-started/introduction/

---
*If any section is unclear or missing, please provide feedback to improve these instructions.*
