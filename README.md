# SoCal EP Website

Emergency planning website for SoCal Emergency Planning - built with Astro and Tailwind CSS.

## Pages

- `/` - Home/Landing page
- `/services` - Training, Consulting, Speaking services
- `/speaking` - Speaking topics
- `/about` - About founder Dr. Halima Phillips-Smith
- `/contact` - Contact and booking form

## Local Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Output is in the `dist/` folder.

## Deploy to Vercel

1. **Create GitHub Repository**
   - Go to https://github.com/new
   - Name: `socalep`
   - Initialize with README

2. **Push Code**
   ```bash
   cd socalep
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/socalep.git
   git push -u origin main
   ```

3. **Deploy to Vercel**
   - Go to https://vercel.com
   - Click "Add New..." > Project
   - Import your `socalep` GitHub repo
   - Framework Preset: Astro
   - Click Deploy

4. **Add Custom Domain**
   - After deploying, go to Project Settings > Domains
   - Add your custom domain (e.g., socalep.com)
   - Follow the DNS instructions Vercel provides

## Contact Form

The contact form uses Formspree. To enable:

1. Sign up at https://formspree.io
2. Create a new form
3. Replace `https://formspree.io/f/placeholder` in `src/pages/contact.astro` with your Formspree form ID
4. Push the update to GitHub

## Technologies

- [Astro](https://astro.build) - Static site framework
- [Tailwind CSS](https://tailwindcss.com) - Styling
- [Vercel](https://vercel.com) - Hosting