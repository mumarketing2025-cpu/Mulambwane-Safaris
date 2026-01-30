# Mulambwane Wildlife & Hunting Safaris

A professional website for Mulambwane Wildlife & Hunting Safaris, a community-owned safari operation in Limpopo Province, South Africa.

## Overview

This is a fully responsive website featuring:
- **Game Viewing & Hunting Safaris** - Year-round wildlife viewing and seasonal hunting experiences
- **Safari Lodge** - Luxury bush accommodation with modern amenities
- **Premium Game Meat** - Ethically sourced African game meat products
- **Contact & Booking** - Professional inquiry and reservation forms
- **Our Story** - Community heritage and conservation mission

## Tech Stack

- **Frontend**: HTML, CSS (Tailwind CSS), JavaScript
- **Backend**: Netlify Functions (serverless)
- **Email**: Nodemailer with Gmail
- **Hosting**: Netlify

## Project Structure

```
.
├── index.html              # Home page
├── story.html              # Our Story page
├── hunting.html            # Game Viewing & Hunting page
├── lodge.html              # Safari Lodge page
├── gamemeat.html           # Game Meat products page
├── contact.html            # Contact & Booking page
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   ├── main.js             # Main functionality
│   ├── get-help-loader.js  # Live chat component loader
│   └── image-optimization.js # Image loading optimization
├── components/
│   └── get-help.html       # Live chat component
├── netlify/
│   └── functions/          # Serverless functions
│       ├── booking.js      # Lodge booking form handler
│       ├── contact.js      # Contact form handler
│       ├── hunting-booking.js # Hunting booking handler
│       ├── order.js        # Game meat order handler
│       └── chat.js         # Live chat API
├── images/                 # Website images and backgrounds
├── package.json            # Dependencies
├── netlify.toml            # Netlify configuration
└── .gitignore              # Git ignore rules
```

## Features

✅ **Professional Design** - Safari-themed branding with African aesthetics
✅ **Responsive Layout** - Mobile, tablet, and desktop optimization
✅ **Form Submission** - Booking and contact forms with email notifications
✅ **Live Chat** - AI-powered help widget for visitor support
✅ **Image Optimization** - Lazy loading and performance optimization
✅ **SEO Optimized** - Meta tags, structured data, and fast loading
✅ **Accessibility** - WCAG compliant with keyboard navigation

## Setup & Deployment

### Prerequisites
- Node.js 18+ (for Netlify Functions)
- GitHub account
- Netlify account

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/mumarketing2025-cpu/Mulambwane-Safaris.git
   cd Mulambwane-Safaris
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env.local
   ```
   
   Required variables for forms:
   - `EMAIL_USER` - Gmail address for sending emails
   - `EMAIL_PASS` - Gmail app password (not regular password)

4. Test locally:
   ```bash
   npm run dev
   ```

### Deployment to Netlify

1. Connect your GitHub repository to Netlify
2. Set environment variables in Netlify dashboard:
   - `EMAIL_USER`
   - `EMAIL_PASS`
3. Deploy!

## Environment Variables

Required for email functionality:

```
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-gmail-app-password
```

For Gmail:
1. Enable 2-Factor Authentication
2. Generate an App Password
3. Use the 16-character password as `EMAIL_PASS`

## Contact Information

- **Email**: mulambwanesafaris@gmail.com
- **Phone**: +27 73 342 6833
- **WhatsApp**: Available
- **Location**: Waterpoort, Louis Trichardt, Limpopo Province, South Africa

## License

ISC

## Author

Mulambwane Wildlife & Hunting Safaris

---

*"Luxury bush accommodation in the heart of Africa" - Community-owned • Conservation-focused • Authentically African*
