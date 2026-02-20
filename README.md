# Nexlead Landing Page

A high-converting, dark-themed landing page for Nexlead - a B2B cold outreach agency.

## Features

- **Dark Theme**: Black background with white/gray text for high contrast
- **Serif Typography**: Uses Playfair Display (headings) and Lora (body) fonts
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Single Goal**: Designed to convert visitors into booked calls

## Setup

1. **Add Your Calendly Link**: 
   - Open `index.html`
   - Find the line with `href="[CALENDLY LINK]"`
   - Replace `[CALENDLY LINK]` with your actual Calendly URL

2. **Customize Agency Name** (if needed):
   - The agency name "Nexlead" appears in:
     - Navigation logo
     - Footer
   - Search and replace "Nexlead" if you want to change it

3. **Open the Page**:
   - Simply open `index.html` in a web browser
   - Or serve it using a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Node.js (if you have http-server installed)
     npx http-server
     ```

## File Structure

```
.
├── index.html      # Main HTML structure
├── styles.css      # All styling and theme
└── README.md       # This file
```

## Design Notes

- **Color Scheme**: Pure black (#000000) background with white (#ffffff) and light gray (#e5e5e5) text
- **Typography**: Serif fonts throughout (Playfair Display for headings, Lora for body text)
- **Layout**: Clean, spacious sections with generous padding
- **CTA Buttons**: White buttons with black text for maximum contrast

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).
