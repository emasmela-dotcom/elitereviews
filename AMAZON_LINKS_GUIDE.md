# Amazon Affiliate Links Setup Guide

## Quick Setup

1. **Get Your Amazon Associates Tag**
   - Log into your Amazon Associates account
   - Your tag looks like: `yourname-20` or `elitereviews-21`
   - Replace `YOUR_TAG` in all links with your actual tag

2. **Find Each Product's ASIN**
   - Go to Amazon.com
   - Search for each product
   - The ASIN is in the product URL: `amazon.com/dp/B08XXXXXXX` (the B08... part)
   - Or find it in the product details section

3. **Replace in index.html**
   - Find each product link
   - Replace `PRODUCT_ASIN` with the actual ASIN
   - Replace `YOUR_TAG` with your Associates tag

## Product List (in order of appearance)

### Tech Products:
1. **MacBook Pro 16" M3 Max** - Search: "MacBook Pro M3 Max 16 inch"
2. **iPhone 15 Pro Max** - Search: "iPhone 15 Pro Max"
3. **Dell XPS 15 (2025)** - Search: "Dell XPS 15 2025"
4. **Sony WH-1000XM5** - Search: "Sony WH-1000XM5 headphones"
5. **LG C3 OLED 65"** - Search: "LG C3 OLED 65 inch TV"
6. **Sony A7 IV Mirrorless** - Search: "Sony A7 IV camera"
7. **Samsung Galaxy S24 Ultra** - Search: "Samsung Galaxy S24 Ultra"
8. **iPad Pro 12.9" M2** - Search: "iPad Pro 12.9 M2"
9. **ASUS ROG Zephyrus G14** - Search: "ASUS ROG Zephyrus G14"
10. **DJI Mini 4 Pro Drone** - Search: "DJI Mini 4 Pro"

### Powersports Products:
11. **Honda CRF450R** - Search: "Honda CRF450R"
12. **Harley-Davidson Street Bob 114** - Search: "Harley Street Bob 114"
13. **Polaris RZR Pro XP 4** - Search: "Polaris RZR Pro XP 4"
14. **Yamaha YZ450F** - Search: "Yamaha YZ450F"
15. **Can-Am Maverick X3 Turbo RR** - Search: "Can-Am Maverick X3 Turbo RR"
16. **Honda Talon 1000X-4** - Search: "Honda Talon 1000X"
17. **Yamaha Raptor 700R** - Search: "Yamaha Raptor 700R"
18. **Kawasaki Ninja ZX-6R** - Search: "Kawasaki Ninja ZX-6R"
19. **BMW R 1250 GS Adventure** - Search: "BMW R 1250 GS Adventure"
20. **KTM 450 SX-F** - Search: "KTM 450 SX-F"

### Watersports Products:
21. **Yamaha WaveRunner VX** - Search: "Yamaha WaveRunner VX"
22. **Sea-Doo Spark Trixx** - Search: "Sea-Doo Spark Trixx"
23. **Hobie Mirage Pro Angler** - Search: "Hobie Mirage Pro Angler"
24. **Kawasaki Jet Ski Ultra** - Search: "Kawasaki Jet Ski Ultra"
25. **Red Paddle Co SUP** - Search: "Red Paddle Co SUP"
26. **Tracker Fishing Boat** - Search: "Tracker fishing boat"
27. **Bennington Pontoon** - Search: "Bennington pontoon boat"
28. **Sea-Doo Wake Pro** - Search: "Sea-Doo Wake Pro"
29. **Boston Whaler Montauk** - Search: "Boston Whaler Montauk"
30. **Perception Pescador Kayak** - Search: "Perception Pescador kayak"

### Vehicles:
31. **2025 Ford F-150 Lightning** - Search: "Ford F-150 Lightning 2025"
32. **2025 Honda CR-V Hybrid** - Search: "Honda CR-V Hybrid 2025"
33. **2025 Tesla Model 3** - Search: "Tesla Model 3 2025"
34. **2025 BMW X5 M60i** - Search: "BMW X5 M60i 2025"
35. **2025 Mazda CX-5 Turbo** - Search: "Mazda CX-5 Turbo 2025"
36. **2025 RAM 1500 Limited** - Search: "RAM 1500 Limited 2025"
37. **2025 Toyota RAV4 Prime** - Search: "Toyota RAV4 Prime 2025"
38. **2025 Porsche Cayenne S** - Search: "Porsche Cayenne S 2025"
39. **2025 Subaru Outback Wilderness** - Search: "Subaru Outback Wilderness 2025"
40. **2025 Chevrolet Silverado** - Search: "Chevrolet Silverado 2025"

### Vacation Packages:
41-50. **Vacation Packages** - These typically use Expedia, Booking.com, or other travel affiliate programs, not Amazon

## Example Link Format

**Before:**
```html
<a href="https://www.amazon.com/dp/PRODUCT_ASIN?tag=YOUR_TAG" ...>
```

**After (example):**
```html
<a href="https://www.amazon.com/dp/B0CHX1W1XY?tag=elitereviews-21" ...>
```

## Quick Find & Replace

1. Open `index.html` in a text editor
2. Use Find & Replace:
   - Find: `YOUR_TAG`
   - Replace: `your-actual-tag-here`
   - Replace All

3. Then for each product, find the link and replace `PRODUCT_ASIN` with the actual ASIN

## Tips

- Use Amazon's SiteStripe tool (browser extension) to generate links automatically
- ASINs are always 10 characters (letters and numbers)
- Test each link after updating to make sure it goes to the correct product
- Some products might not be available on Amazon - use alternative retailers or remove those products

