# Image Classes Reference Guide

## How to Add Your Images

Each timeline activity now has a unique `<img>` tag with a unique class. Replace the empty `src=""` with your image URL.

### Format:
```html
<img class="timeline-item-image img-activity-1" src="YOUR-IMAGE-URL.jpg" alt="Activity description">
```

---

## All 35 Image Classes

Below is the complete list of all image classes in order of appearance:

### Day 1: La Sagrada Familia + Las Ramblas + Camp Nou
1. `img-activity-1` - فطور (Breakfast at Brunch & Cake)
2. `img-activity-2` - La Sagrada Familia visit
3. `img-activity-3` - غداء (Lunch at Honest Greens)
4. `img-activity-4` - عشاء (Dinner at Aladdin Lebanese)

### Day 2: البحر والدراجات + عرض فلامنكو
5. `img-activity-5` - فطور (Breakfast at Soul Cafe)
6. `img-activity-6` - التمشية (Walk at the beach mall)
7. `img-activity-7` - Bike rental activity
8. `img-activity-8` - غداء (Lunch at Restaurant 75)
9. `img-activity-9` - جلسة بحرية (Beach sunset at Lemon Tree Cafe)
10. `img-activity-10` - عرض فلامنكو (Flamenco show)

### Day 3: Park Güell + تجربة السيارة الرياضية
11. `img-activity-11` - فطور (Breakfast at Billy Brunch)
12. `img-activity-12` - Sports car experience
13. `img-activity-13` - غداء (Lunch at Bacoa Burger)
14. `img-activity-14` - Park Güell visit
15. `img-activity-15` - عشاء (Dinner at Soul Cafe)

### Day 4: Montserrat + La Boqueria
16. `img-activity-16` - فطور (Breakfast)
17. `img-activity-17` - Montserrat monastery trip
18. `img-activity-18` - غداء (Lunch at La Boqueria)
19. `img-activity-19` - Magic fountain show
20. `img-activity-20` - عشاء (Dinner at Honest Greens)

### Day 5: Casa Batlló + Shopping
21. `img-activity-21` - فطور (Breakfast at Federal Cafe)
22. `img-activity-22` - Casa Batlló visit
23. `img-activity-23` - Shopping at Passeig de Gràcia
24. `img-activity-24` - Gothic Quarter walking tour
25. `img-activity-25` - Tapas tasting at Cervecería Catalana
26. `img-activity-26` - عشاء (Dinner at Restaurant 75)

### Day 6: Tibidabo + Port Vell
27. `img-activity-27` - فطور (Breakfast at Billy Brunch)
28. `img-activity-28` - Tibidabo amusement park
29. `img-activity-29` - Cable car ride
30. `img-activity-30` - غداء (Lunch at Honest Greens)
31. `img-activity-31` - Port Vell marina walk
32. `img-activity-32` - عشاء (Dinner at Bacoa Burger)

### Day 7: Shopping + Farewell
33. `img-activity-33` - فطور (Breakfast at Brunch & Cake)
34. `img-activity-34` - Shopping at La Roca Village
35. `img-activity-35` - Farewell dinner at Aladdin Lebanese

---

## CSS Styling

All images will automatically:
- Fill the square container (120×120px on desktop, 80×80px on mobile)
- Maintain aspect ratio with `object-fit: cover`
- Have rounded corners (15px on desktop, 12px on mobile)
- Scale on hover (1.05x)
- Show placeholder with shimmer effect when `src=""` is empty

---

## Example Usage

### Adding a Single Image:
Find this in the HTML:
```html
<img class="timeline-item-image img-activity-1" src="" alt="Activity 1">
```

Replace with:
```html
<img class="timeline-item-image img-activity-1" src="images/sagrada-familia.jpg" alt="La Sagrada Familia">
```

### Adding Multiple Images via CSS:
You can also set images via CSS if you prefer:
```css
.img-activity-1 {
    content: url('images/sagrada-familia.jpg');
}

.img-activity-2 {
    content: url('images/sagrada-tickets.jpg');
}

/* ... and so on */
```

### Or Add Background Images:
```css
.img-activity-1 {
    background-image: url('images/sagrada-familia.jpg');
    background-size: cover;
    background-position: center;
}
```

---

## Image Recommendations

### Dimensions:
- Minimum: 300×300px
- Recommended: 600×600px
- Maximum: 1000×1000px

### Format:
- WebP (best compression)
- JPEG (universal support)
- PNG (for images with transparency)

### File Size:
- Keep under 200KB per image
- Use image optimization tools

### Sources:
- Your own Barcelona photos
- Unsplash (free, high-quality)
- Pexels (free, no attribution required)

---

## Quick Reference Table

| Class | Day | Activity Type | Description |
|-------|-----|---------------|-------------|
| img-activity-1 | 1 | Breakfast | Brunch & Cake |
| img-activity-2 | 1 | Attraction | La Sagrada Familia |
| img-activity-3 | 1 | Lunch | Honest Greens |
| img-activity-4 | 1 | Dinner | Aladdin Lebanese |
| img-activity-5 | 2 | Breakfast | Soul Cafe |
| img-activity-6 | 2 | Activity | Beach walk |
| img-activity-7 | 2 | Activity | Bike rental |
| img-activity-8 | 2 | Lunch | Restaurant 75 |
| img-activity-9 | 2 | Activity | Beach sunset |
| img-activity-10 | 2 | Show | Flamenco |
| img-activity-11 | 3 | Breakfast | Billy Brunch |
| img-activity-12 | 3 | Activity | Sports car |
| img-activity-13 | 3 | Lunch | Bacoa Burger |
| img-activity-14 | 3 | Attraction | Park Güell |
| img-activity-15 | 3 | Dinner | Soul Cafe |
| img-activity-16 | 4 | Breakfast | - |
| img-activity-17 | 4 | Trip | Montserrat |
| img-activity-18 | 4 | Lunch | La Boqueria |
| img-activity-19 | 4 | Show | Magic fountain |
| img-activity-20 | 4 | Dinner | Honest Greens |
| img-activity-21 | 5 | Breakfast | Federal Cafe |
| img-activity-22 | 5 | Attraction | Casa Batlló |
| img-activity-23 | 5 | Shopping | Passeig de Gràcia |
| img-activity-24 | 5 | Tour | Gothic Quarter |
| img-activity-25 | 5 | Food | Tapas tasting |
| img-activity-26 | 5 | Dinner | Restaurant 75 |
| img-activity-27 | 6 | Breakfast | Billy Brunch |
| img-activity-28 | 6 | Activity | Tibidabo park |
| img-activity-29 | 6 | Activity | Cable car |
| img-activity-30 | 6 | Lunch | Honest Greens |
| img-activity-31 | 6 | Activity | Port Vell |
| img-activity-32 | 6 | Dinner | Bacoa Burger |
| img-activity-33 | 7 | Breakfast | Brunch & Cake |
| img-activity-34 | 7 | Shopping | La Roca Village |
| img-activity-35 | 7 | Dinner | Aladdin Lebanese |

---

**Note:** The design remains exactly the same. Images will fill the square containers perfectly with `object-fit: cover`.
