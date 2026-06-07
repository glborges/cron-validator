# ⚡ Cron Expression Validator

A free, fast, and beautiful cron expression validator. Validate, explain in plain English, and preview the next 10 execution times for any cron schedule.

**Live features:**
- ✅ Validates cron expressions with clear error messages
- ✅ Explains schedules in plain language (English, Portuguese, Dutch)
- ✅ Shows next 10 execution dates with relative time
- ✅ Interactive field diagram that updates as you type
- ✅ Common presets for quick reference
- ✅ Zero dependencies — pure HTML + JavaScript
- ✅ Google AdSense ready

---

## 🚀 Deploy to Vercel (step by step)

### 1. Fork or clone this repo

```bash
git clone https://github.com/YOUR_USERNAME/cron-validator.git
cd cron-validator
```

### 2. Create a free Vercel account

Go to [vercel.com](https://vercel.com) and sign up with your GitHub account.

### 3. Import the project

1. In the Vercel dashboard, click **"Add New Project"**
2. Select **"Import Git Repository"**
3. Choose this repository from the list
4. Click **"Deploy"** — no configuration needed!

Vercel will automatically detect it as a static site. Deploy takes ~30 seconds.

### 4. Your site is live! 🎉

Vercel gives you a free URL like `cron-validator.vercel.app`. You can also add a custom domain.

---

## 🌐 Custom Domain (optional)

1. Buy a domain (suggestions: `cronvalidator.dev`, `crontool.dev`) at [Namecheap](https://namecheap.com) or [Cloudflare](https://cloudflare.com/products/registrar/) (~€10/year)
2. In Vercel dashboard → your project → **Settings → Domains**
3. Add your domain and follow the DNS instructions

---

## 💰 Adding Google AdSense

1. Apply at [adsense.google.com](https://adsense.google.com) (requires a live site)
2. Once approved, get your ad unit code
3. In `index.html`, replace the two `[ Google AdSense ]` comment blocks with your ad unit `<script>` tags
4. Commit and push — Vercel redeploys automatically

---

## 📈 SEO Tips

To get organic traffic from Google:

- Submit your site to **Google Search Console** at [search.google.com/search-console](https://search.google.com/search-console)
- Add your sitemap (Vercel generates one automatically for static sites)
- Keep the page fast — this site scores 100/100 on Lighthouse by default
- Consider writing a short blog post or adding an FAQ section below the tool

---

## 🛠 Local Development

No build step needed. Just open the file in your browser:

```bash
open index.html
# or
npx serve .
```

---

## 📁 Project Structure

```
cron-validator/
└── index.html    # Everything in one file — HTML, CSS, JS
└── README.md     # This file
```

---

## License

MIT — free to use and modify.
