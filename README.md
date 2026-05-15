# Dashboards Rich Filters - Marketing Website

This directory contains the marketing and documentation website for **Dashboards Rich Filters**, a premium Jira Cloud dashboard gadget available on the Atlassian Marketplace.

## Website Structure

```
dashboards-rich-filters-site/
├── index.html           # Landing page with features, pricing, screenshots
├── privacy-policy.html  # GDPR-compliant privacy policy
├── terms-of-use.html    # Terms of service
├── support.html         # Support center with FAQ
├── documentation.html   # User documentation and guide
├── README.md            # This file
└── image/               # Screenshots and assets
    ├── dashboard1.png
    ├── dashboard2.png
    ├── pmo1.png
    ├── Project Milestones1.png
    ├── Project Milestones2.png
    ├── Project Risk Analysis · Ishikawa.png
    ├── Snipaste_1.png
    └── Time Spent by Assignee.png
```

## Pages Overview

### index.html (Landing Page)
- Hero section with product introduction
- Feature highlights (6 key features)
- Screenshot gallery
- Pricing section (free tier + per-user volume pricing)
- SEO optimized with structured data (JSON-LD)
- Open Graph and Twitter Card meta tags

### privacy-policy.html
- GDPR and CCPA compliant
- Clear explanation of data handling
- Permission scopes documented
- No data storage statement
- Atlassian Marketplace compliance

### terms-of-use.html
- Standard SaaS terms of service
- License grant details
- Subscription and payment terms
- Limitation of liability
- Links to Atlassian terms

### support.html
- Contact information (email: dev.elolin@gmail.com)
- Response time commitment (<24 hours)
- Frequently Asked Questions
- Troubleshooting section
- Links to documentation

### documentation.html
- Installation guide
- Filter usage instructions
- Health Score calculation explanation
- Dashboard types overview
- Themes and Demo Mode guide
- Permissions explanation
- Screenshots of all features

## Atlassian Marketplace Requirements

| Requirement | Status | File |
|-------------|--------|------|
| Privacy Policy | Done | privacy-policy.html |
| Terms of Service | Done | terms-of-use.html |
| Support Contact | Done | support.html |
| Documentation | Done | documentation.html |
| Screenshots | Done | image/ folder |
| GDPR Compliance | Done | privacy-policy.html |
| Pricing Information | Done | index.html |

## SEO Features

All pages include:
- Semantic HTML5 structure
- Meta descriptions and keywords
- Canonical URLs
- Open Graph tags for social sharing
- Twitter Card tags
- JSON-LD structured data (index.html)
- Responsive design (mobile-friendly)
- Fast loading (no external dependencies)

## Design System

### Colors
- Primary: `#0052CC` (Brand blue — chosen for Jira-product visual harmony, not affiliated with Atlassian)
- Secondary: `#6554C0` (Purple)
- Accent: `#00B8D9` (Cyan)
- Success: `#36B37E` (Green)
- Warning: `#FFAB00` (Yellow)
- Danger: `#FF5630` (Red)

### Typography
- Font Family: System fonts (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto)
- Consistent heading hierarchy
- Readable line height (1.8)

## Deployment

Upload all files to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3 + CloudFront

## Maintenance

### Updating Screenshots
1. Replace images in the `image/` folder
2. Keep filenames consistent
3. Optimize images for web

### Updating Content
1. Edit the relevant HTML file
2. Update "Last Updated" date if applicable
3. Test all links

## Contact

- **Vendor**: elolin
- **Email**: dev.elolin@gmail.com
- **Marketplace**: _Listing pending — URL will be added once the app is approved._

## License

Copyright 2024-2026 elolin. All rights reserved.

---

Built for Atlassian Marketplace | Dashboards Rich Filters v2.7.5
