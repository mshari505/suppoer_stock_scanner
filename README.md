# AlphaScanner v3 — Islamic Edition
## US · TASI · BTC · Halal Screening

### 🚀 Deploy (FREE — $0)

**Option 1 — Netlify (easiest, 10 seconds):**
1. Go to https://netlify.com → sign up free
2. Drag the `AlphaScanner-v3` folder onto the dashboard
3. Done — live URL instantly

**Option 2 — Cloudflare Pages:**
1. Upload folder to GitHub repo
2. Go to https://pages.cloudflare.com → Connect to Git
3. Build command: *(leave empty)*
4. Output directory: `/`
5. Deploy

**Option 3 — GitHub Pages:**
1. Upload to GitHub repo
2. Settings → Pages → Deploy from branch (main, root)
3. Your URL: `yourusername.github.io/repo-name`

**Option 4 — Open locally:**
Just double-click `index.html` — works in any browser with no server needed.

---

### Features
- 45 stocks: 25 US + 20 Saudi TASI
- Real-time BTC price (CoinGecko)
- EMA 50 / 100 / 200 crossover signals
- RSI(14) with overbought/oversold detection
- High volume detection (>1.5× 20-day average)
- BUY / SELL / WATCH signals with entry, TP +10%, TP +15%, Stop -5%
- EMA Clearance % — distance from each EMA
- Shariah screening (AAOIFI-aligned): Halal / Doubtful / Haram
- Compliance score 0–100% with score bar
- Purification % for borderline holdings
- 4 Themes: Dark · Light · Matrix · Gold
- F-Pattern layout for optimal readability
- Price flash animations on refresh
- Market hours clocks (NYSE + TASI + BTC 24/7)
- Auto-refresh every 60 seconds

### Data Sources (all free, no API keys)
| Source | Data |
|--------|------|
| Yahoo Finance v8 | US + TASI OHLCV (via allorigins CORS proxy) |
| CoinGecko Free API | BTC price, 24h change, volume, market cap |

### Architecture
Single-file application — all HTML, CSS, and JavaScript in one `index.html`.
No frameworks. No build tools. No npm. Just open or deploy.

### Disclaimer
For informational purposes only. Not financial or religious advice.
Consult a qualified Shariah scholar for a personal fatwa.
