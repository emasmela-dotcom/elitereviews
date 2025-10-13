# How to Update EliteReviews
## Your Monday Update Guide (2-3 hours)

---

## 🎯 QUICK START

Every Monday, you'll add 2 new product reviews to your site. This guide shows you exactly how.

**Time Required:** 2-3 hours
**Difficulty:** Easy (copy-paste!)
**Frequency:** Once per week

---

## 📋 YOUR MONDAY CHECKLIST

Print this out and check boxes as you go:

```
☐ 1. Pick 2 products to review (15 min)
☐ 2. Research product #1 (15 min)
☐ 3. Write review #1 with AI (30 min)
☐ 4. Research product #2 (15 min)
☐ 5. Write review #2 with AI (30 min)
☐ 6. Add both reviews to website (30 min)
☐ 7. Deploy to live site (5 min)
☐ 8. Share on social media (10 min)
☐ 9. Update calendar for next week (10 min)
```

**Total: ~2.5 hours**

---

## 🔍 STEP 1: PICK YOUR PRODUCTS (15 min)

### Where to Find Products:

**Tech:**
- Amazon Best Sellers → Electronics
- BestBuy.com → New & Trending
- Check what's popular this week

**Powersports:**
- ATVTrader.com → Most Viewed
- RevZilla.com → Best Sellers
- Check seasonal trends (spring = more interest)

**Watersports:**
- PWCTrader.com → Popular Models
- Manufacturer sites (Yamaha, Sea-Doo)

**Vehicles:**
- Edmunds.com → Top Rated
- Car and Driver → New Reviews
- AutoTrader → Most Searched

**Vacation Packages:**
- TripAdvisor → Trending Destinations
- Expedia → Popular Packages
- Seasonal (beach in summer, ski in winter)

### Quick Selection Rules:

1. **Pick products people actually search for**
   - Use Google: "best [product] 2025"
   - See what comes up

2. **Rotate categories**
   - Week 1: Tech + Powersports
   - Week 2: Watersports + Vehicles
   - Week 3: Vacation + Tech
   - Week 4: Powersports + Watersports

3. **Mix price points**
   - One high-ticket ($5K+)
   - One mid-range ($500-$5K)

---

## 📝 STEP 2: RESEARCH YOUR PRODUCT (15 min per product)

### What You Need:

**Basic Info:**
- ✅ Product name (exact)
- ✅ Price (current)
- ✅ Manufacturer
- ✅ Model year (if applicable)

**Specs:**
- ✅ 5-10 key specifications
- ✅ What makes it unique
- ✅ Technical details

**Find This Info:**
- Manufacturer website
- Amazon product page
- Dealer websites
- Existing reviews (for inspiration, DON'T copy!)

**Pro Tip:** Open 3-4 tabs with info about the product before writing!

---

## 🤖 STEP 3: WRITE WITH AI (30 min per product)

### Use This Exact Prompt:

**Copy-paste into ChatGPT or Claude:**

```
Write a detailed, honest product review for: [PRODUCT NAME]

Category: [Tech/Powersports/Watersports/Vehicles/Vacation]
Price: [PRICE]

Include these sections:
1. Overview (2-3 sentences - what it is and why it matters)
2. Who It's For (target buyer)
3. Key Features (5-7 bullet points)
4. Pros (5 specific advantages)
5. Cons (3-5 honest drawbacks)
6. Performance Analysis (200 words - how it actually performs)
7. Value for Money (is it worth the price?)
8. Final Verdict (clear recommendation)

Write in a friendly, expert tone. Be honest about both strengths and weaknesses. 
Target length: 800-1000 words.
```

### Then:

1. **Get AI draft** (takes 30 seconds)
2. **Read through it** (2 minutes)
3. **Edit for accuracy** (10 minutes)
   - Fix any wrong specs
   - Add your own insights
   - Make it sound natural
4. **Add personal touches** (5 minutes)
   - "In my research..."
   - "What stands out is..."
   - "Compared to similar products..."
5. **Proofread** (3 minutes)

---

## 💻 STEP 4: ADD TO YOUR WEBSITE (30 min for both reviews)

### Open Your Files:

**Location:** `/Documents/local web/elitereviews/`

**File to Edit:** `index.html`

**Open With:** VS Code, Sublime Text, or any text editor

### Find the Products Section:

Press `Cmd + F` (Mac) or `Ctrl + F` (Windows)

Search for: `<!-- Product Card 1 -->`

You'll see the existing products.

### Copy an Existing Product Card:

**Example Product Card Structure:**

```html
<!-- Product Card X -->
<a href="#" class="product-card">
    <div class="product-image" style="background-image: url('IMAGE_URL');">
        <span class="product-badge">New</span>
    </div>
    <div class="product-content">
        <div class="product-category">CATEGORY</div>
        <h3 class="product-title">PRODUCT NAME</h3>
        <p class="product-description">SHORT DESCRIPTION</p>
        <div class="product-rating">
            <div class="stars">★★★★★</div>
            <span class="rating-text">4.8/5</span>
        </div>
        <div class="product-footer">
            <div class="product-price">$X,XXX</div>
            <div class="product-cta">View Deal →</div>
        </div>
    </div>
</a>
```

### What to Change:

1. **IMAGE_URL** → Product image URL (see Image Guide)
2. **product-badge** → "New", "Hot Deal", "Editor's Pick", or remove
3. **CATEGORY** → Tech, Powersports, Watersports, Vehicles, Vacation
4. **PRODUCT NAME** → Exact product name
5. **SHORT DESCRIPTION** → 1-2 sentences from your review
6. **Stars** → Your rating (★★★★★ = 5 stars, ★★★★☆ = 4 stars)
7. **Rating number** → Your rating number
8. **$X,XXX** → Actual price

### Save Your Changes:

**Mac:** `Cmd + S`
**Windows:** `Ctrl + S`

---

## 🖼️ STEP 5: GET PRODUCT IMAGES

### Best Sources:

**1. Amazon (BEST for affiliates)**
- Go to product page
- Right-click main image
- "Copy Image Address"
- Paste into IMAGE_URL

**2. Manufacturer Website**
- Go to official product page
- Right-click product image
- "Copy Image Address"

**3. Unsplash (Generic tech/lifestyle)**
- Unsplash.com
- Search: "laptop", "motorcycle", "beach vacation"
- Download or copy URL

**Pro Tip:** Use high-quality images! Bad images = no sales.

---

## 🚀 STEP 6: DEPLOY TO LIVE SITE (5 min)

### Option A: Using Vercel (Recommended)

**Open Terminal:**

```bash
cd "/Users/ericmasmela/Documents/local web/elitereviews"
git add .
git commit -m "Added 2 new reviews - [Date]"
git push
```

**That's it!** Vercel auto-deploys in 30 seconds.

### Option B: Manual Upload

1. Go to vercel.com
2. Click your project
3. Upload `index.html`
4. Deploy

---

## 📱 STEP 7: PROMOTE ON SOCIAL MEDIA (10 min)

### Quick Posts:

**Twitter/X:**
```
Just published: [Product Name] Review 🔥

[2-sentence summary of what makes it special]

Read the full review: [YOUR-URL]

#ProductReview #[Category]
```

**LinkedIn:**
```
New review on EliteReviews: 

[Product Name] - Is it worth $X,XXX?

After extensive research, here's what you need to know:

✅ [Top Pro]
✅ [Top Pro]
❌ [Main Con]

Full review: [YOUR-URL]
```

**Instagram Stories (if you have one):**
- Screenshot product image
- Add text: "New review live!"
- Link to your site

---

## 📅 STEP 8: UPDATE YOUR CALENDAR (10 min)

**Open:** `90-DAY-CALENDAR.md`

**Mark this week complete:** ✅

**Plan next week:**
- Pick 2 new products
- Choose different categories
- Add to calendar

---

## ❓ TROUBLESHOOTING

### "I can't find where to paste the new product!"

Look for this comment in `index.html`:

```html
<!-- ADD NEW PRODUCTS HERE -->
```

Paste your new product card right after this line.

### "The image isn't showing!"

1. Check the image URL works (paste in browser)
2. Make sure it starts with `https://`
3. Try a different image source

### "How do I know what rating to give?"

Based on your research:
- 5 stars: Exceptional, best in class
- 4.5 stars: Excellent with minor flaws
- 4 stars: Very good, solid choice
- 3.5 stars: Good but has issues
- 3 stars: Average, has pros and cons

### "The site won't deploy!"

1. Make sure you saved the file (`Cmd + S`)
2. Check for syntax errors (missing `>` or `</`)
3. Try again in 5 minutes

### "I'm stuck!"

**Don't stress!**
- Skip that review, do it next week
- Use a simpler product
- Copy an existing review structure exactly

---

## ⏱️ TIME-SAVING TIPS

### Week 1: Will take 3 hours
- You're learning
- That's normal!

### Week 4: Will take 2 hours
- You'll have a rhythm
- Faster at everything

### Week 8: Will take 90 minutes
- Total routine
- Could do it in your sleep!

### Shortcuts:

1. **Batch your research** (both products at once)
2. **Use the same AI prompt** (just change product name)
3. **Keep a template file** (copy-paste product card)
4. **Pre-schedule posts** (write social media on Friday)

---

## 🎯 YOUR FIRST MONDAY GOALS

**Keep it simple:**
- ✅ Add 2 new reviews
- ✅ Get them live
- ✅ Share on social

**Don't worry about:**
- ❌ Being perfect
- ❌ Long reviews (800 words is fine)
- ❌ Pro photography (Amazon images are fine)

**Just get it done! Consistency beats perfection! 💪**

---

## 📊 WHAT SUCCESS LOOKS LIKE

**Month 1:**
- 8 new reviews added
- Site has 58-108 total reviews
- First Google impressions

**Month 2:**
- 8 more reviews
- 66-116 total reviews
- Starting to rank for keywords

**Month 3:**
- 8 more reviews
- 74-124 total reviews
- First affiliate sales! 💰

---

## 🚀 YOU'VE GOT THIS!

Remember:
- ✅ Start next Monday
- ✅ Follow this guide
- ✅ 2-3 hours per week
- ✅ Stay consistent
- ✅ Use the checklist

**See you next Monday! 💪**

