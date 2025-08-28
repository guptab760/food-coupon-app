# Food Coupon App

## Features
- Auto-generate coupons based on spend thresholds
- SVG QR codes for crisp printing
- Redeem page with QR scanning (html5-qrcode)
- Firestore backend hooks
- EmailJS & Twilio/Vonage placeholders

## Deployment
### Netlify Drop (easiest)
1. Go to https://app.netlify.com/drop
2. Drag and drop this zip file
3. Done!

### GitHub + Netlify
1. Create a GitHub repo
2. Push these files
3. Connect repo to Netlify (Publish directory = `/`)

### Vercel
1. Create new project
2. Import from GitHub
3. Deploy

Configure Firebase + API keys in `app.js` and `redeem.js` where marked.
