# Shift Society — Landing Page

## Before deploying
1. Get a free access key at https://web3forms.com using Inquiries@shift-society.co.za
2. Open src/App.jsx and replace PASTE_YOUR_ACCESS_KEY_HERE with your key

## Deploy on Vercel (free)
1. Create an account at https://vercel.com
2. Either:
   - Push this folder to a GitHub repo, then "Import Project" in Vercel, OR
   - Install Vercel CLI (`npm i -g vercel`) and run `vercel` inside this folder
3. Vercel auto-detects Vite. Accept defaults. You get a live URL.

## Connect shift-society.co.za
1. Vercel → your project → Settings → Domains → Add "shift-society.co.za" and "www.shift-society.co.za"
2. Vercel shows DNS records (A record 76.76.21.21 + CNAME cname.vercel-dns.com)
3. Add those records in your domain registrar's DNS panel
4. Wait up to an hour — site goes live with automatic HTTPS

## Local development (optional)
npm install
npm run dev
