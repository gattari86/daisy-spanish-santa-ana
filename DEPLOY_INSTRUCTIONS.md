# 🚀 Deploy Van Nuys Landing Page to Vercel

## Quick Deployment Steps

### Method 1: Vercel Dashboard (Easiest)

1. **Open Vercel Dashboard**
   - Go to: https://vercel.com/new
   - Login with your GitHub account

2. **Import GitHub Repository**
   - Click "Add New" → "Project"
   - Search for: `spanishvannuys`
   - Click "Import" on the `gattari86/spanishvannuys` repository

3. **Configure Project Settings**
   - **Project Name:** `spanishvannuys` (or your choice)
   - **Framework Preset:** Other (or None)
   - **Root Directory:** `./` (default)
   - **Build Command:** Leave empty
   - **Output Directory:** `./` (default)

4. **Deploy**
   - Click "Deploy" button
   - Wait 30-60 seconds for deployment
   - You'll get a live URL like: `spanishvannuys.vercel.app`

### Method 2: Vercel CLI (Alternative)

```bash
# Navigate to project
cd /Users/ricardogattas-moras/spanishvannuys

# Login to Vercel (opens browser)
vercel login

# Deploy to production
vercel --prod
```

## After Deployment

Your page will be live at:
- **Vercel URL:** `https://spanishvannuys.vercel.app` (or similar)
- **Custom Domain:** You can add a custom domain in Vercel settings

## Verify Deployment

Once deployed, check that:
- ✅ Page loads correctly
- ✅ Google Tag Manager is firing (GTM-KQK9GDDJ)
- ✅ Meta Pixel is tracking (1623449681952157)
- ✅ Booking link works: booking-van-nuys
- ✅ Phone link works: (877) 877-3030
- ✅ Location shows: 6640 Van Nuys Blvd, Suite 204, Van Nuys, CA 91405
- ✅ Hours show: Sábados 10:00 AM - 3:00 PM

## Troubleshooting

**404 Error?**
- Make sure you've imported the correct GitHub repository
- Check that the repository name is `spanishvannuys`
- Verify you're accessing the correct Vercel URL

**Need Custom Domain?**
- Go to your Vercel project settings
- Click "Domains"
- Add your custom domain
- Update DNS records as instructed

## Auto-Deploy

Once connected, any push to the `main` branch will automatically deploy to Vercel.
