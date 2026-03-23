# 80 Tick Alpha — Landing Page

## Files
- `index.html` — The complete landing page (single file, no dependencies)

## Quick Setup Checklist

### 1. Update Your Links (search & replace in any text editor)
- `https://whop.com` → your Whop Tier 1 URL
- Second `https://whop.com` → your Whop Tier 2 URL  
- `https://discord.com` → your Discord invite link
- `https://twitter.com/80TickAlpha` → your X profile URL
- `https://tradingview.com` → your TradingView affiliate link
- `https://takeprofittrader.com` → your Take Profit Trader affiliate link

### 2. Update Pricing
- Find `$XX / month` → replace with your actual Tier 2 price

### 3. PDF Download
- Find `href="#"` on the download button → replace with your PDF URL
- Or upload the PDF to GitHub in the same repo and use `./nq-precision-playbook.pdf`

### 4. Deploy to GitHub Pages
1. Go to github.com → New repository → name it `80tickalpha`
2. Upload `index.html` (and PDF if applicable) to the repo
3. Settings → Pages → Source: main branch, / (root)
4. Live at: https://yourusername.github.io/80tickalpha

## Customization Notes
- All colors use CSS variables at the top of the file (`:root {}`)
- Main accent: `--electric: #a855f7` (electric violet)
- To change pricing layout, find `#community` section
- Indicators section: find `#indicators` and edit the 4 `.indicator-card` blocks
