# Matthew Benko — Portfolio

Personal portfolio site for Matthew Benko, Network Security Engineer. Hosted
on GitHub Pages at **mattbenko.xyz**.

## Stack

- Single-file HTML with inline CSS (no build step, no external CSS framework)
- Google Fonts (Inter, JetBrains Mono)
- GitHub Pages for hosting, TLS, and CDN

## Local development

Just open `index.html` in a browser. The whole site is one file plus this
README and the `CNAME` — there's no build step.

## Production deployment

1. Push to `main` branch on GitHub.
2. GitHub Pages serves the site from `main` automatically.
3. The `CNAME` file in this repo tells GitHub Pages to use `mattbenko.xyz`
   as the custom domain.
4. DNS for `mattbenko.xyz` points to GitHub's IP set (managed in Namecheap).

## Content updates

The site is a single `index.html`. To update content, edit the file directly
and commit. The structure:

- Hero (name, title, contact links)
- Summary
- Technical Skills
- Professional Experience
- Projects (with links to public repos)
- Certifications, Licenses & Awards
- Education
- Footer

## Privacy

- No analytics, no tracking, no cookies.
- The site is static and public.
- Cert IDs are displayed (EC-Council, CompTIA, AWS) — these are public
  credentials by design.
- Email link uses `mailto:benkomatt@gmail.com` — the address is already
  on the public web in many places.

## Related

- The site is part of a pair — see `BenkoMatt/jenna-lynn-photography` for
  the photography site (Jenna's business).
