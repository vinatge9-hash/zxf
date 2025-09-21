# Niyantri Club - Website Setup

This is a static, Tailwind CSS-driven website for Niyantri Club, a cozy coffee shop.

What you get:
- Four pages: Home (index.html), Menu (menu.html), About Us (about.html), Contact (contact.html)
- A responsive, transparent navigation with a mobile hamburger menu
- A full-viewport Home hero with centered content and warm coffee-themed visuals
- A cozy, three-column testimonials section on the homepage
- A dark, three-column footer with brand, quick links, and a newsletter signup
- All styling via Tailwind CSS utility classes (no external CSS files)
- Image placeholders in the format: src="https://images.pexels.com/photos/30885765/pexels-photo-30885765.jpeg?auto=compress&cs=tinysrgb&h=650&w=940"
- Accessibility: semantic HTML5 elements, descriptive alt text, and proper heading structure (one h1 per page)

How to run locally:
1. Save the four HTML files and README.md in a single folder.
2. Open any page (e.g., index.html) in a browser. The site uses Tailwind via CDN, so no build step is required.
3. For a quick dev server, you can run a simple HTTP server (e.g., Python's http.server) in the folder:
   - Python 3: python -m http.server 8000
   - Navigate to http://localhost:8000/

Notes:
- The current context date and location are: Sunday, September 21, 2025, in Hyderabad, Telangana, India. Footer shows © 2025 and Hyderabad as the location.
- All interactive elements include smooth transitions: transition-all duration-300 ease-in-out, hover effects, and subtle scroll reveals.

