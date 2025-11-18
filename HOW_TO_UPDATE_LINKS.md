# How to Update Amazon Links - Step by Step

## Step 1: Replace YOUR_TAG (One-Time, Takes 30 Seconds)

1. Open `index.html` in any text editor (VS Code, Notepad, etc.)
2. Press `Ctrl+F` (or `Cmd+F` on Mac) to open Find & Replace
3. In the "Find" box, type: `YOUR_TAG`
4. In the "Replace" box, type: `your-actual-tag-here` (e.g., `elitereviews-21` or `yourname-20`)
5. Click "Replace All" (or "Replace All" button)
6. Done! This updates all 50 links at once

**Example:**
- Find: `YOUR_TAG`
- Replace: `elitereviews-21`
- Result: All links now have `?tag=elitereviews-21`

---

## Step 2: Replace Each PRODUCT_ASIN (One at a Time)

### How to Find an ASIN:

1. Go to **Amazon.com**
2. Search for the product (e.g., "MacBook Pro M3 Max 16 inch")
3. Click on the product
4. Look at the URL - it will look like:
   ```
   https://www.amazon.com/dp/B0CHX1W1XY/...
   ```
   The **ASIN is the part after `/dp/`** - in this case: `B0CHX1W1XY`

5. Or look in the "Product Details" section - it shows "ASIN: B0CHX1W1XY"

### How to Replace in index.html:

**Method 1: Manual (One at a Time)**
1. Open `index.html`
2. Find the product (use `Ctrl+F` to search for product name like "MacBook Pro")
3. Find the link that says: `href="https://www.amazon.com/dp/PRODUCT_ASIN?tag=..."`
4. Replace `PRODUCT_ASIN` with the actual ASIN
5. Repeat for each product

**Example:**
- **Before:** `href="https://www.amazon.com/dp/PRODUCT_ASIN?tag=elitereviews-21"`
- **After:** `href="https://www.amazon.com/dp/B0CHX1W1XY?tag=elitereviews-21"`

**Method 2: Find & Replace (If you have all ASINs)**
1. Use Find & Replace for each product
2. Find: `PRODUCT_ASIN` (in the context of that specific product)
3. Replace: `B0CHX1W1XY` (the actual ASIN)

---

## Quick Reference: Product Order in index.html

The products appear in this order in the file:

1. MacBook Pro 16" M3 Max
2. iPhone 15 Pro Max
3. Dell XPS 15 (2025)
4. Sony WH-1000XM5
5. LG C3 OLED 65"
6. Sony A7 IV Mirrorless
7. Samsung Galaxy S24 Ultra
8. iPad Pro 12.9" M2
9. ASUS ROG Zephyrus G14
10. DJI Mini 4 Pro Drone
... (and 40 more)

---

## Tips:

1. **Use Amazon's SiteStripe Tool** (if you have it installed):
   - Install Amazon Associates SiteStripe browser extension
   - Visit each product on Amazon
   - Click "Get Link" button
   - Copy the full link - it already has your tag and ASIN!

2. **Test Each Link:**
   - After updating, test the link in a browser
   - Make sure it goes to the correct product page

3. **Work in Batches:**
   - Do all Tech products first (10 products)
   - Then Powersports (10 products)
   - Then Watersports (10 products)
   - Then Vehicles (10 products)
   - Then Vacation Packages (10 products)

4. **Save Frequently:**
   - Save after each batch to avoid losing work

---

## Example Workflow:

1. ✅ Replace `YOUR_TAG` with `elitereviews-21` (30 seconds)
2. 🔍 Search Amazon for "MacBook Pro M3 Max 16 inch"
3. 📋 Copy ASIN: `B0CHX1W1XY`
4. 🔍 In index.html, find "MacBook Pro"
5. ✏️ Replace `PRODUCT_ASIN` with `B0CHX1W1XY`
6. ✅ Test the link
7. 🔄 Repeat for next product

---

## Need Help?

If you want, I can:
- Help you find specific ASINs if you tell me which products
- Create a script to batch-update if you provide all ASINs in a list
- Create a checklist to track which products you've updated

