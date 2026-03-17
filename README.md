# Vidarix Landing Page

Landing page untuk **Vidarix** — Video Analytics AI untuk TikTok Marketer Indonesia.

## Tech Stack

- Pure HTML, CSS, JavaScript (no framework)
- Google Fonts: Plus Jakarta Sans + DM Sans + DM Mono
- Zero dependencies

## Deploy

### Vercel (Recommended)
1. Push repo ini ke GitHub
2. Buka [vercel.com](https://vercel.com) → New Project
3. Import repo dari GitHub
4. Framework Preset: **Other**
5. Klik Deploy — selesai!

### GitHub Pages
1. Push repo ke GitHub
2. Settings → Pages → Source: `main` branch → `/ (root)`
3. Save → tunggu beberapa menit
4. Akses di `https://username.github.io/vidarix-landing`

## Struktur File

```
vidarix-landing/
├── index.html      # Landing page utama
├── vercel.json     # Konfigurasi Vercel
└── README.md       # Dokumentasi ini
```

## Custom Domain (Vercel)

Setelah deploy, tambahkan domain `vidarix.id`:
1. Vercel Dashboard → Project → Settings → Domains
2. Add domain: `vidarix.id`
3. Update DNS di registrar (Niagahoster/Domainesia):
   - Type: `A` → `76.76.21.21`
   - Type: `CNAME` → `cname.vercel-dns.com`

---

© 2025 Vidarix
