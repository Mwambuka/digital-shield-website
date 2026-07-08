# Digital Shield — Official Website

The official website for **Digital Shield**, a National NGO in Rwanda (Law N° 058/2024) delivering cyber-safety education and community technology programs to young people and institutions.

- **Flagship program:** The Digital Shield Program — a 3-day cyber-safety and digital-literacy curriculum for Secondary 4 students.
- **Institutional program:** Tech Umuganda — an Audit-Fix-Teach model for device maintenance and digital literacy in schools, TVETs, health centers, and public offices.

## Structure

Static site, no build step, no framework, no dependencies:

```
index.html      All markup, styles (inline <style>), and scripts (inline <script>)
images/         Site photography, referenced by relative path
favicon.svg     Browser-tab icon
robots.txt      Crawler access
vercel.json     Security headers + long-term caching for /images and favicon
```

Open `index.html` directly in any browser to view the site locally — nothing to install or build.

## Deploying

This repo deploys to [Vercel](https://vercel.com) with zero configuration: import the repo, leave the framework preset as "Other," and deploy. `vercel.json` supplies security headers and asset caching; no build command or output directory is needed since `index.html` sits at the repo root.

Once a production domain is assigned, update the `og:image` / `twitter:image` meta tags in `index.html` from relative paths to absolute URLs (`https://yourdomain/images/hero-classroom.jpg`) so link previews render correctly on platforms that require fully-qualified image URLs.

## Contact

- Email: digitalshield@gmail.com
- Phone: +0798904755
- Location: Norrsken Kigali House, 1 KN 78 St, Kigali, Rwanda
