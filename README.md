# Mulambwane Wildlife & Hunting Safaris

**Professional Safari Website - Community-Owned Conservation in Limpopo Province, South Africa**

This is the official website for Mulambwane Wildlife & Hunting Safaris, a community-owned and operated safari destination featuring hunting safaris, luxury lodge accommodation, and premium game meat products.

## Features

- **Responsive Design**: Modern, mobile-first website built with Tailwind CSS and vanilla JavaScript
- **Serverless Functions**: Netlify Functions for form submissions (contact, bookings, orders)
- **Video Hero Sections**: Optimized video backgrounds with fallbacks
- **Image Optimization**: Lazy loading and responsive image delivery
- **Safari Packages**: Game viewing, hunting, and lodge accommodation offerings
- **Conservation Mission**: Ubuntu-driven approach to community and wildlife preservation

## Pages

- **Home** (`index.html`) - Main landing page with hero section and feature highlights
- **Our Story** (`story.html`) - Heritage, mission, and community impact
- **Game Viewing & Hunting** (`hunting.html`) - Safari packages and wildlife experiences
- **Safari Lodge** (`lodge.html`) - Accommodation options and amenities
- **Game Meat** (`gamemeat.html`) - Premium game meat products and ordering
- **Contact** (`contact.html`) - Inquiry forms and contact information

## Project Structure

```
├── index.html                    # Home page
├── story.html                    # Our Story
├── hunting.html                  # Game viewing & hunting safaris
├── lodge.html                    # Safari lodge accommodations
├── gamemeat.html                 # Game meat products
├── contact.html                  # Contact page
├── css/
│   └── styles.css                # Global styles and theme
├── js/
│   ├── main.js                   # Core functionality
│   ├── get-help-loader.js        # Live chat component
│   └── image-optimization.js     # Image optimization utilities
├── components/
│   └── get-help.html             # Live chat component
├── netlify/
│   └── functions/
│       ├── booking.js            # Lodge booking submissions
│       ├── hunting-booking.js    # Safari booking submissions
│       ├── contact.js            # Contact form submissions
│       ├── order.js              # Game meat order submissions
│       └── chat.js               # Live chat responses
├── netlify.toml                  # Netlify configuration
├── package.json                  # Project dependencies
└── images/                       # Image assets (not included in repo)
```

## Setup & Development

### Prerequisites
- Node.js 18+
- npm or yarn
- Netlify CLI (for local development)

### Installation

```bash
# Clone the repository
git clone https://github.com/mumarketing2025-cpu/Mulambwane-Safaris.git
cd Mulambwane-Safaris

# Install dependencies
npm install

# Install Netlify CLI (optional, for local serverless functions)
npm install -g netlify-cli
```

### Development

```bash
# Start local Netlify development server
netlify dev

# Or start a simple HTTP server
python -m http.server 8000
```

Then visit `http://localhost:8000` (or the port shown by Netlify CLI)

## Environment Variables

Create a `.env` file for local development:

```env
# Email Configuration
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your-email@gmail.com
SMTP_PASS=your-app-password
ADMIN_EMAIL=your-email@gmail.com

# Optional: ChatBot AI
OPENAI_API_KEY=your-openai-key-here
```

## Netlify Deployment

This site is configured for deployment on Netlify with serverless functions.

**Build Settings:**
- Build command: (None required for static site)
- Publish directory: `.`
- Functions directory: `netlify/functions`

**Environment Variables Required on Netlify:**
- `SMTP_HOST` - SMTP server address
- `SMTP_PORT` - SMTP port (587 or 465)
- `SMTP_USER` - Email username
- `SMTP_PASS` - Email password (use App Password for Gmail)
- `ADMIN_EMAIL` - Email to receive form submissions
- `OPENAI_API_KEY` - (Optional) For AI chatbot responses

## Serverless Functions

All backend logic runs on Netlify Functions (AWS Lambda):

- **`/booking`** - Lodge reservation submissions
- **`/hunting-booking`** - Safari booking submissions
- **`/contact`** - Contact form inquiries
- **`/order`** - Game meat product orders
- **`/chat`** - Live chat responses

## Features

### Responsive Design
- Mobile-first approach with Tailwind CSS
- Touch-friendly navigation and forms
- Optimized for all device sizes

### Performance
- Lazy-loaded images
- Optimized video backgrounds
- Minimal JavaScript dependencies
- Static site generation where possible

### Accessibility
- Semantic HTML structure
- ARIA labels and descriptions
- Keyboard navigation support
- Color contrast compliance

### SEO
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Sitemap-ready structure
- Structured data for rich snippets

## Community & Conservation

Multambwane Wildlife & Hunting Safaris is **100% community-owned** through the Mulambwane Community Property Association (CPA). Every safari experience directly supports:

- Local employment and economic development
- Wildlife conservation and anti-poaching efforts
- Cultural heritage preservation
- Education and healthcare initiatives
- Sustainable habitat management

**Our Philosophy: "Ubuntu" - "I am because we are"**

## Contact

**Mulambwane Wildlife & Hunting Safaris**
- 📧 Email: [info@mulambwanesafaris.co.za](mailto:info@mulambwanesafaris.co.za)
- 📞 Phone: +27 73 342 6833
- 💬 WhatsApp: [Click to message](https://wa.me/27733426833)
- 📍 Location: Limpopo Province, South Africa

## License

ISC

## Credits

Website developed by [Mumarketing.Org](https://mumarketing.org)

---

**"Luxury bush accommodation in the heart of Africa" - Community-owned | Conservation-focused | Authentically African**
