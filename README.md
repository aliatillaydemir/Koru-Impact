# Koru Impact - Professional Website

A modern, responsive website for Koru Impact, a sustainable innovation consulting company. Built with HTML and Tailwind CSS.

## 🔗 Live Demo

You can view the live version of this project by clicking the link below:

[Visit the website](https://koru-impact.vercel.app)

## 🌟 Features

- **Responsive Design**: Fully responsive across all devices
- **Modern UI**: Clean, professional design with smooth animations
- **Accessibility**: Semantic HTML and proper contrast ratios
- **Performance**: Optimized for fast loading with CDN resources
- **SEO Ready**: Proper meta tags and semantic structure

## 📁 Project Structure

```
Koru Impact/
├── index.html          # Home page
├── about.html          # About Us page
├── services.html       # Our Services page
├── contact.html        # Contact page
└── README.md           # Project documentation
```

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#2563EB` - Used for headings, buttons, and links
- **Primary Green**: `#16A34A` - Used for accents and secondary highlights
- **Accent Gold**: `#FBBF24` - Used sparingly for CTAs and highlights
- **Background**: `#FFFFFF` (White)
- **Text**: `#1F2937` (Gray-800)

### Typography
- **Headings**: Lato (Google Fonts) - Modern, warm, accessible sans-serif
- **Body Text**: Libre Baskerville (Google Fonts) - Authoritative, academic serif

## 🚀 Deployment Plan

### Step 1: GitHub Repository Setup
1. Create a new GitHub repository
2. Push all files to the repository
3. Ensure the repository is public for free hosting

### Step 2: Deploy to Netlify (Recommended)
1. Go to [netlify.com](https://netlify.com)
2. Sign up/Login with your GitHub account
3. Click "New site from Git"
4. Select your GitHub repository
5. Deploy settings:
   - Build command: (leave empty - static site)
   - Publish directory: `/` (root)
6. Click "Deploy site"

### Step 3: Custom Domain Setup
1. In Netlify dashboard, go to "Domain settings"
2. Click "Add custom domain"
3. Enter: `koruimpact.org`
4. Follow DNS configuration instructions:
   - Add CNAME record: `koruimpact.org` → `your-site.netlify.app`
   - Add A record: `@` → `75.2.60.5` (Netlify's IP)

### Alternative: Deploy to Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy automatically
4. Configure custom domain in Vercel dashboard

## 📱 Pages Overview

### Home Page (`index.html`)
- Hero section with company tagline
- Overview of Four Pillars
- Clear CTAs to Services and About pages
- Professional gradient background

### About Us Page (`about.html`)
- Company mission and values
- Founder's professional bio
- Education and achievements
- CTA to Services page

### Services Page (`services.html`)
- Detailed descriptions of Four Pillars:
  - Strategic Consulting
  - Technology Solutions
  - Team Development
  - Performance Analytics
- CTA to Contact page

### Contact Page (`contact.html`)
- Contact form with validation
- Company email: `info@koruimpact.org`
- Phone and office information
- FAQ section
- Professional contact details

## 🛠 Technical Implementation

### Technologies Used
- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework
- **Google Fonts**: Lato and Libre Baskerville
- **SVG Icons**: Heroicons for consistent iconography

### Key Features
- **Fixed Navigation**: Sticky header with smooth scrolling
- **Responsive Grid**: CSS Grid and Flexbox for layouts
- **Hover Effects**: Smooth transitions and interactions
- **Form Validation**: HTML5 form validation
- **Accessibility**: ARIA labels and semantic HTML

### Performance Optimizations
- CDN-hosted Tailwind CSS
- Optimized Google Fonts loading
- Minimal JavaScript (vanilla HTML)
- Compressed SVG icons
- Responsive images and layouts

## 📋 Content Strategy

### AI Content Generation Process
1. **Research Phase**: Analyze company mission and values
2. **Prompt Engineering**: Create specific prompts for each page
3. **Content Generation**: Use LLM to generate professional copy
4. **Review & Refinement**: Ensure consistency and accuracy
5. **SEO Optimization**: Include relevant keywords naturally

### Content Guidelines
- Professional tone throughout
- Focus on sustainability and innovation
- Clear value propositions
- Action-oriented language
- Consistent brand voice

## 🔧 Customization

### Adding New Pages
1. Copy existing page structure
2. Update navigation links
3. Modify content and styling
4. Test responsiveness

### Modifying Colors
Update the Tailwind config in each HTML file:
```javascript
colors: {
    'primary-blue': '#2563EB',
    'primary-green': '#16A34A',
    'accent-gold': '#FBBF24',
    'text-gray': '#1F2937'
}
```

### Adding Features
- Forms: Use Netlify Forms or Formspree
- Analytics: Add Google Analytics tracking
- SEO: Implement meta tags and structured data
- Performance: Optimize images and implement lazy loading

## 📞 Support

For technical support or questions about the website:
- Email: info@koruimpact.org
- Phone: +1 (555) 123-4567

## 📄 License

© 2025 Koru Impact. All rights reserved.

---

**Built with ❤️ for sustainable innovation** 