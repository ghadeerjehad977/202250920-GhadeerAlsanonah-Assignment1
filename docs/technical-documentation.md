# Technical Documentation

## Project Structure
- `index.html` – Main webpage structure (sections: About, Projects, Contact)
- `css/styles.css` – Styling and responsive layout rules
- `js/script.js` – JavaScript interactivity (time-based greeting)
- `assets/images/` – Folder for images
- `docs/` – Documentation files for AI usage and technical notes

## HTML Sections
- **Header**: Displays my name and title
- **About**: Short introduction about me
- **Projects**: Two sample project blocks with titles and descriptions
- **Contact**: A form with name, email, and message fields 

## CSS Styling
- Basic typography and spacing
- Styled header with background color
- Centered sections with a max-width for readability
- Responsive adjustments using a media query for screens under 600px

## JavaScript Functionality
The site displays a greeting message based on the current time:
- Before 12:00 → “Good morning”
- 12:00–17:59 → “Good afternoon”
- 18:00+ → “Good evening”

