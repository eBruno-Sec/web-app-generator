# 🍜 Maze Kusina - Filipino-Japanese Fusion Food & Curated Goods

**Where Flavor Meets Culture**

---

## 📋 Project Overview

Maze Kusina is a beautiful, modern website for a family-owned business selling homemade Filipino-Japanese fusion meals, baked goods, and carefully curated items from San Diego local stores. Based in National City, California, this site tells the story of a culinary journey spanning three countries: Philippines → Japan → USA.

**Live URL:** *[Add your Vercel URL here after deployment]*

---

## ✨ Features

✅ **Fully Responsive Design** - Works beautifully on phones, tablets, and desktops
✅ **Filipino-Japanese Fusion Aesthetic** - Coral pink, teal, and gold color palette
✅ **Multiple Contact Methods** - Text, call, contact form, and social media
✅ **Product Showcase** - Homemade meals, baked goods, and curated items
✅ **Story Section** - Share your unique journey and cultural background
✅ **Mobile-First Design** - Perfect for Instagram and social media traffic
✅ **Smooth Animations** - Professional scroll effects and hover states
✅ **Local Delivery Info** - Clear instructions for National City customers

---

## 🎨 Design

**Color Palette:**
- **Coral Pink** (#FF6B9D) - Filipino sunset warmth
- **Teal/Mint** (#4ECDC4) - Japanese minimalism
- **Gold Accents** (#FFD700) - Premium touch
- **Cream Background** (#FFF8F0) - Soft, inviting

**Typography:**
- Headings: Georgia (elegant serif)
- Body: System fonts (fast, modern)

**Visual Style:**
- Clean, modern layouts
- Warm and inviting atmosphere
- Family-owned, authentic feel
- Cultural fusion aesthetic

---

## 📱 How Customers Can Order

### Primary Method: Text Orders
**Phone:** (619) 621-8962
- Click-to-text button on mobile
- Click-to-call option available
- Fastest way to order!

### Social Media (Add Your Links Below)
**Instagram:** *[Add your Instagram username]*
**Facebook:** *[Add your Facebook page URL]*

**To activate social links:**
1. Open `index.html`
2. Find the Instagram link: `<a href="#" ... id="instagram-link">`
3. Replace `href="#"` with `href="https://instagram.com/YOUR_USERNAME"`
4. Find the Facebook link: `<a href="#" ... id="facebook-link">`
5. Replace `href="#"` with `href="https://facebook.com/YOUR_PAGE"`

### Amazon Shop (Coming Soon)
**To add your Amazon shop:**
1. Open `index.html`
2. Find: `<button class="btn btn-outline" disabled>Coming Soon</button>`
3. Replace with: `<a href="YOUR_AMAZON_SHOP_URL" class="btn btn-primary">Shop on Amazon</a>`
4. Remove the disabled button

### Contact Form
The contact form uses Web3Forms (free service). To activate:
1. Go to https://web3forms.com
2. Get your free API key (no signup required)
3. Open `index.html`
4. Find: `<input type="hidden" name="access_key" value="YOUR_WEB3FORMS_KEY">`
5. Replace `YOUR_WEB3FORMS_KEY` with your actual key

---

## 🚚 Delivery Options

**Local Delivery (National City, CA):**
- Meet at customer's nearest police station
- Cash payment accepted
- Safe and convenient!

**Shipping:**
- Available through Amazon shop (when activated)
- Or contact for special shipping arrangements

---

## 📝 How to Update Content

### Update Product Information
**File:** `index.html`
**Lines:** Search for `<div class="product-card">` (there are 3 of them)

Example:
```html
<h3>Homemade Meals</h3>
<p>Filipino-Japanese fusion dishes...</p>
<p class="product-price">Contact for pricing & menu</p>
```

Just change the text between the tags!

### Update Your Story
**File:** `index.html`
**Section:** Search for `<section id="story">`

The story is broken into paragraphs. Edit any paragraph to update your story:
```html
<p>Born in the Philippines and raised in Japan...</p>
```

### Change Phone Number
**File:** `index.html`
Search for: `(619) 621-8962` and replace all instances with your new number.
Also search for: `+16196218962` (the tel: and sms: links)

### Replace Placeholder Images
All images use free Unsplash photos. To use your own:

1. Take photos of your food/products
2. Upload to an image hosting service (Imgur, Cloudinary, etc.)
3. In `index.html`, find the image URLs:
```html
<img src="https://images.unsplash.com/photo-..." alt="...">
```
4. Replace the `src` with your image URL

**Image Recommendations:**
- Hero section: 1600x900px (landscape)
- Product cards: 800x600px (landscape)
- Story image: 800x800px (square or landscape)

### Update Colors
**File:** `styles.css`
**Lines:** 1-20 (CSS Variables)

Change any color:
```css
--coral-primary: #FF6B9D;  /* Change to any hex color */
--teal-primary: #4ECDC4;   /* Change to any hex color */
```

---

## 🖥️ Tech Stack

- **HTML5** - Semantic, accessible markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript (Vanilla)** - No frameworks, fast loading
- **Web3Forms** - Contact form backend (optional)
- **Responsive Design** - Mobile-first approach

**No dependencies!** Everything runs client-side for maximum speed.

---

## 🚀 Deployment Instructions

### Option 1: Vercel (Recommended)

1. **Sign up for Vercel** (free)
   - Go to https://vercel.com
   - Sign up with GitHub

2. **Import Your Project**
   - Click "Add New" → "Project"
   - Select your GitHub repo: `eBruno-Sec/web-app-generator`
   - Click "Import"

3. **Configure Settings**
   - **Root Directory:** `projects/maze-kusina`
   - **Framework Preset:** Other
   - **Build Command:** (leave empty)
   - **Output Directory:** (leave empty)

4. **Deploy**
   - Click "Deploy"
   - Wait 1-2 minutes
   - Your site will be live at: `https://maze-kusina.vercel.app` (or similar)

5. **Copy Your Live URL**
   - Add it to the top of this README
   - Share it with customers!

### Option 2: GitHub Pages

1. Go to your repo: `https://github.com/eBruno-Sec/web-app-generator`
2. Click "Settings" → "Pages"
3. Source: Deploy from branch
4. Branch: `main`, folder: `/projects/maze-kusina`
5. Click "Save"
6. Your site will be live at: `https://ebruno-sec.github.io/web-app-generator/maze-kusina/`

### Option 3: Netlify

1. Go to https://netlify.com
2. Drag and drop the `maze-kusina` folder
3. Your site is live instantly!

---

## 📱 Recommended Next Steps

### Immediate (Day 1):
1. ✅ Deploy the site (follow instructions above)
2. ✅ Share the URL with friends and family for feedback
3. ✅ Test all links on mobile (most customers will use phones!)
4. ✅ Add your Instagram and Facebook links

### Short Term (Week 1):
1. 📸 Take professional photos of your food/products
2. 📸 Replace all placeholder images with real photos
3. 📧 Set up Web3Forms for contact form (optional)
4. 🛍️ Create Amazon shop account (if desired)
5. 📱 Create Instagram and Facebook business pages

### Medium Term (Month 1):
1. 🌐 Get a custom domain ($10-15/year)
   - GoDaddy: `mazekusina.com`
   - Namecheap: `mazekusina.net`
2. 📊 Add Google Analytics to track visitors
3. 🔍 Add basic SEO (meta descriptions, keywords)
4. 🎨 Create QR code for flyers/business cards

### Long Term:
1. 📖 Start a blog section with recipes
2. 🎥 Add video content (cooking demos)
3. 💳 Consider online payment options
4. 📧 Create email newsletter
5. ⭐ Collect customer reviews/testimonials

---

## 🆘 Troubleshooting

### Issue: Site not loading after deployment
**Solution:** Check that you selected the correct root directory: `projects/maze-kusina`

### Issue: Images not showing
**Solution:** Check your internet connection. Unsplash images require internet. Replace with local images if needed.

### Issue: Mobile menu not working
**Solution:** Check browser console for errors. Clear cache and refresh.

### Issue: Contact form not working
**Solution:** The form needs a Web3Forms API key. Until then, direct customers to text you!

### Issue: Links not working on mobile
**Solution:** 
- Text links (`sms:`) only work on mobile devices
- Call links (`tel:`) only work on devices with phone capability
- This is normal behavior!

---

## 💡 Marketing Tips

### Social Media:
1. Post your food photos daily on Instagram
2. Use hashtags: #NationalCityFood #FilipinoFood #JapaneseFood #AsianFusion #SanDiegoEats
3. Share customer reviews and feedback
4. Behind-the-scenes cooking videos
5. Share your website URL in your bio

### Local Marketing:
1. Print flyers with QR code to your website
2. Leave business cards at local shops
3. Join National City community groups on Facebook
4. Partner with local businesses
5. Offer first-time customer discounts

### Word of Mouth:
1. Ask happy customers to share with friends
2. Create a referral program
3. Attend local farmers markets
4. Participate in community events

---

## 📞 Support

If you need help updating the website:
1. Check this README first
2. Google your question (lots of HTML/CSS tutorials)
3. Ask a tech-savvy friend
4. Consider hiring a freelancer for major changes (Fiverr, Upwork)

---

## 🎉 Success Checklist

Before sharing your site with customers:

- [ ] Site is deployed and accessible via URL
- [ ] All links work (test on mobile!)
- [ ] Phone number is correct
- [ ] Story section is accurate
- [ ] Product information is up-to-date
- [ ] Pricing is clear (even if "Contact for pricing")
- [ ] Delivery options are explained
- [ ] Instagram/Facebook links added (or disabled)
- [ ] Site looks good on phone, tablet, and desktop
- [ ] Someone else has reviewed it

---

## 📄 License

This website was built for Maze Kusina. You own all rights to the content and can modify it however you like!

---

## 🙏 Credits

**Built by:** Claude (AI Assistant) + Your Vision
**Images:** Unsplash (free stock photos)
**Icons:** Unicode Emojis
**Inspiration:** Filipino-Japanese culture and fusion cuisine

---

**Made with ❤️ in National City, California**

*From Philippines to Japan to Your Table*