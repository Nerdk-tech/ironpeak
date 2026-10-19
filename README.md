# Iron Peak Finance — Static Site

Plain, self-contained static build. No jQuery, no Bootstrap JS, no Slick/WOW/Select2 —
one small vanilla script runs the FAQ, mobile nav, profit calculator and newsletter stub.

## Structure

index.html          — the whole page (HTML + all CSS in <style> + JS in <script>)
config.json         — site metadata
assets/
  fonts/            — self-hosted web fonts (offline-capable, no CDN)
  images/           — all site imagery

## Hosting

Works on any static host as-is (no build step):
• Netlify / Vercel / Cloudflare Pages — drag the folder in
• Any web server — upload the folder, open index.html

Notes:
• Zero external requests — fonts and images are local files.
• No .htaccess / netlify.toml included (some Telegram hosting bots reject them).
