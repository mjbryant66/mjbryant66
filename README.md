# MJBryant.ca Website

Professional website for Michael Bryant, featuring AI Strategy consulting and Indigenous Law services.

## Tech Stack

- **Framework:** Astro 4.x
- **Styling:** Tailwind CSS
- **Hosting:** Netlify
- **Forms:** Netlify Forms

## Quick Start

### 1. Install Dependencies

```bash
npm install
```

### 2. Run Development Server

```bash
npm run dev
```

Visit http://localhost:4321 to view the site.

### 3. Build for Production

```bash
npm run build
```

The built site will be in the `dist/` directory.

### 4. Preview Production Build

```bash
npm run preview
```

## Project Structure

```
/
├── public/              # Static assets
│   ├── logos/          # Media outlet logos (to be added)
│   └── images/         # Headshot image (to be added)
├── src/
│   ├── components/     # Reusable components
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   ├── MediaLogos.astro
│   │   └── ServiceCard.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/          # Page routes
│       ├── index.astro       # Homepage
│       ├── ai.astro          # AI Strategy
│       ├── session.astro     # Session request form
│       ├── indigenous.astro  # Indigenous Law
│       ├── about.astro       # About page
│       ├── contact.astro     # Contact form
│       └── 404.astro         # 404 page
└── package.json
```

## Deployment to Netlify

1. Push code to GitHub
2. Connect repository to Netlify
3. Build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
4. Deploy!

Netlify will automatically detect the forms and enable form submissions.

## Next Steps

1. Add headshot image to `public/images/`
2. Add media outlet logos to `public/logos/` (grayscale, 40-50px height)
3. Update MediaLogos component to use real logos instead of placeholders
4. Configure custom domain (mjbryant.ca) in Netlify
5. Enable HTTPS in Netlify after DNS propagation

## Forms

Two Netlify Forms are configured:
- **Session Request Form** (`/session`)
- **Contact Form** (`/contact`)

Forms will work automatically once deployed to Netlify.

## License

© 2025 Michael J. Bryant
