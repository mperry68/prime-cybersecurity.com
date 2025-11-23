# Prime Cybersecurity Website

A professional cybersecurity services marketing website built for Cloudflare Pages deployment.

## Structure

```
/
├── index.html                    # Main homepage
├── phishing-training.html        # Dedicated page for phishing training services
├── audits-pentests.html          # Dedicated page for security audits and penetration testing
├── _redirects                    # Cloudflare Pages redirect rules
├── README.md                     # This file
├── assets/
│   ├── css/
│   │   └── styles.css            # Main stylesheet
│   └── js/
│       └── script.js             # JavaScript for interactivity
├── src/                          # Source files and development assets
├── blog/                         # Blog posts and articles
└── public/
    ├── images/                   # Image assets
    ├── documents/                # PDF documents
    └── fonts/                    # Custom fonts
```

## Deployment to Cloudflare Pages

1. Connect your repository to Cloudflare Pages
2. Set the build output directory to `public/` (this is where your HTML files and images are)
3. No build command is needed (static site)
4. The site will be automatically deployed on push to your main branch

**Important:** Make sure your HTML files (index.html, etc.) are in the `public/` folder, or move them there. The build output directory should point to `public/` so that images in `public/images/` are accessible at `/images/`.

## Features

- Responsive design for all devices
- Modern, professional UI
- Service pages for:
  - Phishing Training & Email Security
  - Security Audits & Penetration Testing
- Contact form integration
- Smooth scrolling navigation
- Mobile-friendly menu

## Contact Information

- Email: info@prime-consulting.ca
- Phone: +1 (514) 881-9888
- Address: 6500 Trans-Canada Hwy Suite 400, Pointe-Claire, Quebec, Canada H9R 0A5

