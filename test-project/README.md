# Academic Personal Homepage - Applied Computational intelligencE Lab

A modern, responsive academic website template designed for professors and research labs.

## Features

- 🎨 Modern, clean design with professional academic aesthetics
- 📱 Fully responsive design that works on all devices
- ⚡ Fast loading with optimized CSS and JavaScript
- 🔍 Publications filtering system
- 👥 Research group member profiles
- 📧 Contact form with validation
- 🎯 Smooth scrolling navigation
- ✨ Subtle animations and hover effects

## Sections

- **HOME**: Hero section with profile and introduction
- **NEWS**: Latest updates and announcements
- **RESEARCH**: Research areas with visual cards
- **PUBLICATIONS**: Filterable publication list
- **GROUP**: Research team member profiles
- **EDUCATION**: Academic timeline
- **CONTACT**: Contact information and form

## Setup Instructions

1. **Add Your Profile Images**:
   - Place your profile photo as `assets/profile.jpg` (300x300px recommended)
   - Add team member photos as `assets/member1.jpg`, `assets/member2.jpg`, etc. (150x150px recommended)

2. **Customize Content**:
   - Replace `[Your Name]` with your actual name throughout `index.html`
   - Update university information, contact details, and addresses
   - Modify the research areas in the RESEARCH section
   - Add your actual publications in the PUBLICATIONS section
   - Update team member information in the GROUP section
   - Modify your education timeline in the EDUCATION section

3. **Customize Colors** (optional):
   - Edit CSS variables in `styles.css` under `:root` to change the color scheme
   - Default primary color is blue (#2563eb)

4. **Deploy**:
   - Upload all files to your web server
   - Ensure all image paths are correct
   - Test on different devices and browsers

## File Structure

```
test-project/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── assets/             # Images directory
│   ├── profile.jpg     # Your profile photo
│   ├── member1.jpg     # Team member photos
│   ├── member2.jpg
│   └── ...
└── README.md           # This file
```

## Customization Tips

1. **Colors**: Modify CSS variables in `styles.css` for consistent color changes
2. **Fonts**: Change font family in CSS or add new Google Fonts links
3. **Animations**: Adjust animation timings and effects in `script.js`
4. **Sections**: Add or remove sections by modifying HTML and updating navigation
5. **Content**: All text content can be easily modified in `index.html`

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Internet Explorer 11+ (with limited CSS Grid support)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact Form

The contact form includes client-side validation. For server-side processing, you'll need to:
1. Set up a server-side script (PHP, Node.js, etc.)
2. Update the form action attribute
3. Handle form data on the server

## Performance

- Optimized CSS with efficient selectors
- Minimal JavaScript for core functionality
- Compressed images recommended for production
- Uses system fonts with Google Fonts fallback

## Credits

- Font: Inter (Google Fonts)
- Icons: Font Awesome 6
- Design: Custom academic template

---

© 2024 Applied Computational intelligencE Laboratory. Customize as needed for your use.