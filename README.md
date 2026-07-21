# Faith Holiness Community Development Corporation Website

A professional, informational website for Faith Holiness CDC featuring information about the organization, services, partnerships, and donation capabilities.

## Features

✅ **Who We Are** - Mission, values, and organizational information
✅ **What We Do** - Comprehensive service offerings (housing, employment, education, mental health, community programs, senior services)
✅ **Partnerships** - Information about local partnerships and collaboration opportunities
✅ **Zelle Donations** - Integrated donation section with Zelle payment information
✅ **Contact Information** - Multiple ways to get in touch
✅ **Responsive Design** - Mobile-friendly layout

## Getting Started

### Quick Setup

1. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Set Source to "Deploy from a branch"
   - Select Branch: `main`, Folder: `/(root)`
   - Save

2. **Your site will be available at:**
   ```
   https://mara121926.github.io/FaithHolinessCDC.org/
   ```

### Customization Required

Before launching, update the following placeholders in `index.html`:

```html
<!-- In the Donate Section -->
<p><strong>Zelle Username/Email:</strong> <span class="highlight">donations@faithholinesscdc.org</span></p>
<p><strong>Phone (Optional):</strong> [Your Phone Number]</p>

<!-- In the Contact Section -->
<li><strong>Phone:</strong> [Your Phone Number]</li>
<li><strong>Address:</strong> [Your Address]</li>

<!-- Tax Information -->
<p><strong>Tax Information:</strong> Faith Holiness CDC is a registered 501(c)(3) nonprofit organization. Your donation is tax-deductible. Tax ID: [Your EIN]</p>
```

## File Structure

```
├── index.html          # Main website page
├── styles.css          # Styling and responsive design
└── README.md           # This file
```

## Sections

### 1. **Navigation Bar**
- Sticky navigation with links to all major sections
- Brand/logo display

### 2. **Hero Section**
- Eye-catching banner with mission statement
- Call-to-action button for donations

### 3. **About Us**
- Organization mission statement
- Core values (Faith, Compassion, Partnership, Empowerment, Excellence)

### 4. **What We Do**
- 6 service cards:
  - Housing Assistance
  - Employment Services
  - Education & Tutoring
  - Mental Health Support
  - Community Programs
  - Senior Services

### 5. **Partnerships**
- Information on collaboration with local networks
- List of partner types
- Partnership inquiry contact

### 6. **Donate Section**
- Why donate
- **Zelle donation integration** with account details
- Tax deductibility information
- Alternative donation methods

### 7. **Contact**
- Contact information
- Email contact form
- Multiple contact channels

### 8. **Footer**
- Organization name and mission statement

## Customization Tips

### Change Colors
Edit the color scheme in `styles.css`:
- Primary Blue: `#1a3a52` and `#2c5aa0`
- Accent Gold: `#d4af37`

### Update Service Cards
Modify or add service cards in the "What We Do" section. Each card has:
- Icon (emoji)
- Title
- Description

### Email Links
Replace email placeholders:
- `info@faithholinesscdc.org` - General inquiries
- `donations@faithholinesscdc.org` - Donation inquiries

## Zelle Setup

To enable donations via Zelle:

1. **Register your organization's email or phone with Zelle** through your bank
2. **Update `index.html`** with your Zelle contact information in the Donate section
3. **Add your EIN** (Employer Identification Number) for tax purposes
4. Test the donation process

## Contact Form

The contact form uses a mailto link. For advanced functionality (database storage, notifications), consider:
- Formspree (formspree.io)
- EmailJS (emailjs.com)
- Netlify Forms (if deploying on Netlify)

## Mobile Responsive

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

## Launch Checklist

- [ ] Update all `[Your ...]` placeholders with actual information
- [ ] Update Zelle account information
- [ ] Add your EIN and tax information
- [ ] Add your organization's phone number and address
- [ ] Test all links and contact forms
- [ ] Enable GitHub Pages
- [ ] Share your site URL: `https://mara121926.github.io/FaithHolinessCDC.org/`

## Support

For questions or updates needed to this website, contact your web administrator.

---

**Faith Holiness Community Development Corporation**
*Empowering lives through faith and community*
