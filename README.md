# SOLIFIC - Holistic Consultation Landing Page

A clean, earth-tone landing page for SOLIFIC consultation requests.

## Features

- Responsive design (mobile-friendly)
- Consultation request form
- Video testimonials section
- Community call-to-action
- Earth-tone healing aesthetic

## Setup

### Form Configuration

The form uses Formspree for submissions. To set it up:

1. Go to [Formspree.io](https://formspree.io) and create a free account
2. Create a new form and get your form endpoint
3. In `index.html`, replace `YOUR_FORM_ID` in the form action:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Video Testimonials

To add video testimonials:

1. Upload your testimonial videos to YouTube or Vimeo
2. Get the embed code or video ID
3. In `index.html`, replace `YOUR_VIDEO_ID_1`, `YOUR_VIDEO_ID_2`, etc. with actual video IDs

**For YouTube:**
```html
<iframe src="https://www.youtube.com/embed/VIDEO_ID_HERE"></iframe>
```

**For Vimeo:**
```html
<iframe src="https://player.vimeo.com/video/VIDEO_ID_HERE"></iframe>
```

### Skool Community Link

Update the Skool community link in two places in `index.html`:

1. Hero section secondary button
2. Community section button

Replace `https://www.skool.com/solific` with your actual Skool community URL.

## Deployment

### GitHub Pages
1. Go to repository Settings > Pages
2. Select main branch as source
3. Your site will be live at: `https://yourusername.github.io/solific-consultation-landing`

### Vercel (Recommended)
1. Import this repository in Vercel
2. Deploy with default settings
3. Get instant HTTPS URL

### Netlify
1. Connect repository to Netlify
2. Deploy with default settings
3. Optionally enable Netlify Forms (no Formspree needed)

## Color Palette

- Background: `#F4F1EC`
- Accent: `#C2A878`
- Text: `#3A3A3A`
- Primary Button: `#6B8E6E`
- Button Hover: `#5A7D60`

## File Structure

```
├── index.html          # Main HTML file
├── style.css           # All styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

© 2026 SOLIFIC. All rights reserved.
