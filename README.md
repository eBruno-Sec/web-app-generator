# 🚀 Web App Generator

**Automated full-stack web application builder powered by AI and Puppeteer automation**

This repository contains a questionnaire-driven system that generates, codes, and deploys complete web applications automatically.

---

## 📋 What This Does

This system:
1. ✅ Asks you standardized questions about your web project
2. ✅ Generates complete, production-ready code
3. ✅ Automatically deploys to free hosting (Vercel/Netlify)
4. ✅ Saves everything to GitHub for version control
5. ✅ Creates a reusable, repeatable process

---

## 🗂️ Repository Structure

```
web-app-generator/
├── README.md                    # You are here
├── questionnaire.json           # The questions asked for each project
├── templates/                   # Starter code templates
│   ├── landing-page/           # Simple HTML landing pages
│   ├── react-app/              # React applications
│   ├── ecommerce/              # E-commerce templates
│   ├── saas-app/               # SaaS application templates
│   └── portfolio/              # Portfolio websites
├── scripts/                     # Automation scripts
│   ├── deploy-vercel.js        # Vercel deployment automation
│   └── deploy-netlify.js       # Netlify deployment automation
└── projects/                    # Your completed projects
    └── [project-name]/         # Each project gets its own folder
```

---

## 🎯 How To Use This System

### Prerequisites
- Docker MCP with GitHub integration enabled
- GitHub personal access token configured
- (Optional) Vercel or Netlify account

### Starting a New Project

Simply say to Claude:
```
"I want to build a new website"
```

Claude will:
1. Read the questionnaire from this repo
2. Ask you the questions
3. Generate code based on your answers
4. Save the project to `projects/[your-project-name]/`
5. Deploy it live
6. Give you the URL

---

## 📝 The Questionnaire

The questionnaire covers:

### 1. Business Basics
- Business/project name
- Industry/niche
- Description

### 2. Website Purpose & Goals
- Primary goal
- Target audience
- Key actions for visitors

### 3. Features & Functionality
- Core features (auth, payments, CMS, etc.)
- Third-party integrations

### 4. Design & Branding
- Brand colors
- Design style
- Inspirations

### 5. Content Structure
- Main pages needed
- Content readiness

### 6. Technical Requirements
- CMS needs
- Expected traffic
- Mobile/SEO priorities

---

## 🛠️ Available Templates

### Landing Page (`templates/landing-page/`)
- Simple HTML/CSS/JS
- Perfect for marketing sites
- Fast and lightweight
- Easy to customize

### React App (`templates/react-app/`)
- Modern React with hooks
- Component-based architecture
- Ready for complex features
- Optimized for performance

### E-commerce (Coming Soon)
- Product listings
- Shopping cart
- Payment integration
- Admin dashboard

### SaaS App (Coming Soon)
- User authentication
- Dashboard
- Billing integration
- Team management

### Portfolio (Coming Soon)
- Project showcase
- Resume/CV
- Contact form
- Blog integration

---

## 🚀 Deployment Options

### Vercel (Recommended for React/Next.js)
- Automatic deployments from GitHub
- Free SSL certificates
- Global CDN
- Instant previews

### Netlify (Recommended for static sites)
- Drag-and-drop deployment
- Form handling
- Serverless functions
- Split testing

---

## 📊 Project History

All your projects are saved in the `projects/` folder:

```
projects/
├── acme-corp-website/
│   ├── index.html
│   ├── styles.css
│   └── deployment-info.json
├── johns-portfolio/
│   └── ...
└── saas-startup/
    └── ...
```

Each project folder contains:
- ✅ Complete source code
- ✅ Deployment information
- ✅ Configuration files
- ✅ README with project details

---

## 🔄 Workflow Diagram

```
User Request → Read Questionnaire → Ask Questions → 
Collect Answers → Select Template → Customize Code → 
Create GitHub Folder → Deploy Live → Return URL
```

---

## 🎨 Customization

### Adding New Templates
1. Create a new folder in `templates/`
2. Add your starter code
3. Use `{{VARIABLE}}` syntax for dynamic content
4. Update the template selection logic

### Modifying Questions
1. Edit `questionnaire.json`
2. Follow the existing structure
3. Add new questions to relevant sections
4. Update template logic to use new data

### Adding Deployment Targets
1. Create a new script in `scripts/`
2. Follow the pattern of existing scripts
3. Add platform-specific configuration

---

## 📈 Roadmap

- [x] Core questionnaire system
- [x] Landing page template
- [x] React app template
- [ ] E-commerce template
- [ ] SaaS app template
- [ ] Portfolio template
- [ ] Blog/CMS template
- [ ] Database integration helpers
- [ ] Payment processing templates
- [ ] Authentication boilerplate

---

## 💡 Tips

1. **Start Simple**: Begin with a landing page, add complexity later
2. **Use Placeholders**: Don't worry about perfect content on day 1
3. **Iterate**: Deploy fast, improve continuously
4. **Save Everything**: GitHub is your backup and version control
5. **Learn as You Go**: Each project teaches you something new

---

**Built with ❤️ by Claude + Docker MCP + Puppeteer**

Last Updated: October 17, 2025