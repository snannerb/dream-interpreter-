# Dream Interpreter Webpage

A simple webpage for interpreting dreams, featuring a pixel-style font, a grey background, and an embedded AI widget.

## Features
- **Title:** "Dream Interpreter" in a pixel-style font.
- **Widget:** Embeddable AI widget for dream interpretation.
- **Footer:** Link to "Pixel Oracle" with external redirect.

## Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge).

## Setup
1. Clone this repository or download the files.
2. Open `index.html` in your browser.

## Testing
- Test the page in multiple browsers (Chrome, Firefox, Safari, Edge).
- Verify the following:
  - Title is displayed correctly.
  - Widget is functional.
  - Footer link redirects to "Pixel Oracle" in a new tab.

## Accessibility Considerations
- Ensure the contrast ratio between text and background meets WCAG standards.
- Use semantic HTML tags for better screen reader compatibility.
- Test the page in browsers with accessibility features enabled (e.g., Chrome's Accessibility Developer Tools).

## Deployment

### **Option 1: Local Deployment**
- Serve the files locally using a simple HTTP server for local testing:
  ```bash
  python -m http.server 8000
  ```
  Access the page at `http://localhost:8000`.

### **Option 2: Web Hosting**
- Upload the `dream-interpreter/` folder to a web hosting service (e.g., GitHub Pages, Netlify, Vercel).

### **GitHub Pages Deployment**
1. Push the project to a GitHub repository.
2. Go to `Settings > Pages` and select the `main` branch as the source.
3. Access your live site at `https://<username>.github.io/dream-interpreter/`.