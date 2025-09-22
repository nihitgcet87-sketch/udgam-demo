
# Udgam Demo Site (India-only, free hosting)

This is a static demo for Udgam (Barawhite Stone Heights Pvt Ltd) to deploy on a free subdomain first (e.g., Vercel), then move to udgam.co.in / udgam.in later.

## Files
- index.html — single-page site
- styles.css — styles
- /assets/udgam_logo.svg — chosen logo (Concept 3)

## Launch on Vercel (free)
1. Create a GitHub repo and push these files.
2. Connect the repo at https://vercel.com/new
3. Framework: "Other" (static). Build command: none. Output: root.
4. Get your free URL like https://udgam.vercel.app

## Add Zoho Form (free)
- Create a form in Zoho Forms (Name, Company, Phone/WhatsApp, State, Application, Mesh, Quantity, Packaging, Notes)
- Get "Public" embed iframe URL and replace the placeholder iframe in index.html

## Move to custom domain
- Buy udgam.co.in (or udgam.in) at an Indian registrar (BigRock/Hostinger/GoDaddy)
- In your domain DNS, add a CNAME pointing www -> your Vercel domain
- Add domain in Vercel Project Settings

## Zoho Mail (free custom domain)
- After domain purchase, create sales@udgam.co.in in Zoho Mail Free plan
- Add MX records in your domain DNS as guided by Zoho
- Replace demo email in the site with sales@udgam.co.in

## Price ranges
- Replace ₹X,XXX–₹Y,YYY in index.html when Nitin confirms state-wise numbers.
