# FDP PRIMEAI-2025 Website

## 📋 Overview

Professional standalone HTML website for the Faculty Development Programme on **Process-centric and Reward-based Interpretable Models in Explainable AI (PRIMEAI-2025)**.

**Event Dates**: December 23-30, 2025 (8 Days)  
**Organized By**: Department of Computer Science & Engineering, MMMUT Gorakhpur

---

## 🚀 Features

- ✅ **Fully Standalone**: All CSS embedded, no external dependencies
- ✅ **Responsive Design**: Mobile, tablet, and desktop optimized
- ✅ **Image Support**: Carousel, logos, speaker photos with SVG fallbacks
- ✅ **Professional Design**: Gradient backgrounds, smooth animations, hover effects
- ✅ **Fast Loading**: Optimized code, minimal file size
- ✅ **Easy Deployment**: Works on any static hosting platform

---

## 📄 Pages

### 🏠 Home (`index.html`)
- Rotating carousel with 4 background images
- Event highlights (8 days, 10+ speakers, hybrid mode, registration fees)
- NIRF rankings display
- Call-to-action section with registration details
- MMMUT logo in navigation

### ℹ️ About (`about.html`)
- FDP overview and objectives
- About MMMUT and CSE Department
- Programme learning outcomes
- Target audience information
- Key highlights and training areas

### 📅 Schedule (`schedule.html`)
- Complete 8-day session schedule (Dec 23-30, 2025)
- 11 expert-led sessions with topics and speakers
- Organizing committee with photos
  - Patron: Prof. Jay Prakash Saini
  - Chairman: Prof. Rakesh Kumar
  - Convener: Dr. Satya Prakash Yadav
  - Coordinators team
- Important information section

### 👤 Speakers (`speakers.html`)
- 10 distinguished speakers with professional cards
- Photo placeholders with SVG fallbacks
- Expertise tags for each speaker
- International & industry experts:
  - Prof. Peter Peer (University of Ljubljana, Slovenia)
  - Nagendra Sharma (Google Cloud Platform)
  - Venkat Desai (Microsoft Japan)
  - Prof. Satish Kumar Singh (IIIT Allahabad)
  - Dr. Shivram Dubey (IIIT Allahabad)
  - Dr. Soumendu Chakrabourty (IIIT Lucknow)
  - Dr. Sandeep Singh Sengar (Cardiff School of Technologies, UK)
  - Dr. Nayaneesh Kumar Mishra (CEO, N-Code Sutram)
  - Prof. Rakesh Kumar (MMMUT)
  - Dr. Satya Prakash Yadav (MMMUT)

---

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#1976d2` (navigation, headings)
- **Primary Orange**: `#f57c00` (accents, CTAs)
- **Success Green**: `#4caf50` (highlights)
- **Error Red**: `#d32f2f` (important text)
- **Gradients**: Multiple gradient combinations for visual appeal

### Typography
- **Font Family**: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Headings**: Bold (700-900 weight)
- **Body**: Regular (400 weight)
- **Line Height**: 1.6 for readability

### Responsive Breakpoints
- **Mobile**: < 768px
- **Tablet/Desktop**: ≥ 768px

---

## 📂 File Structure

```
PrimeAI-HTML/
├── index.html              # Homepage with carousel
├── about.html              # About FDP & MMMUT
├── schedule.html           # Schedule & organizers
├── speakers.html           # Speaker profiles
├── IMAGES-NEEDED.md        # Image requirements guide
├── README.md               # This file
└── images/                 # Image directory
    ├── mmmut-logo.png
    ├── carrousel-1.jpg
    ├── carrousel-2.jpg
    ├── carrousel-3.jpg
    ├── carrousel-4.jpg
    ├── speaker-*.jpg       # 10 speaker photos
    ├── patron.jpg
    ├── chairman.jpg
    └── convener.jpg
```

---

## 🖼️ Image Requirements

### Required Images (23 total)

1. **Logo**: `mmmut-logo.png` (200x200px, transparent PNG)
2. **Carousel**: 4 images (`carrousel-1.jpg` to `carrousel-4.jpg`, 1920x1080px)
3. **Speakers**: 10 photos (400x400px each)
4. **Organizers**: 3 photos (300x300px each)

**See `IMAGES-NEEDED.md` for complete details.**

### Fallback Behavior
- Missing images display SVG placeholders with initials
- Logo hides if not found
- Website remains fully functional without images

---

## 🌐 Deployment

### Option 1: GitHub Pages
1. Create a new GitHub repository
2. Upload all HTML files and `images/` folder
3. Go to Settings → Pages
4. Select `main` branch → Save
5. Website will be live at `https://username.github.io/repo-name`

### Option 2: Netlify
1. Drag & drop the `PrimeAI-HTML` folder to [netlify.com/drop](https://netlify.com/drop)
2. Instant deployment with custom domain support

### Option 3: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the `PrimeAI-HTML` directory
3. Follow the prompts

### Option 4: Any Web Host
Upload files via FTP to any web hosting service (cPanel, HostGator, etc.)

---

## ✅ Pre-Deployment Checklist

- [ ] Add all images to `images/` folder
- [ ] Test carousel rotation on homepage
- [ ] Verify all navigation links work
- [ ] Check responsive design on mobile
- [ ] Update registration link (currently shows alert)
- [ ] Test on multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Optimize image file sizes if needed
- [ ] Add favicon if desired

---

## 🔧 Customization

### Update Registration Link
In `index.html`, find:
```html
<a href="#" class="btn btn-secondary" onclick="alert('Registration link will be updated soon'); return false;">
```
Replace with:
```html
<a href="YOUR_GOOGLE_FORM_LINK" class="btn btn-secondary" target="_blank">
```

### Modify Colors
Search for color codes in any HTML file and replace:
- `#1976d2` (blue)
- `#f57c00` (orange)
- `#4caf50` (green)

### Add More Speakers
Copy a speaker card block in `speakers.html` and update:
- Image source
- Name, role, organization
- Expertise tags

---

## 📊 Event Information

### Registration Fees
- **₹250**: MMMUT-affiliated & online participants
- **₹1000**: Offline external candidates

### Eligibility
- Faculty members
- PG students
- Research scholars
- Industry professionals

### Mode
Hybrid (Online + Offline)

### Certificate
Awarded to participants with minimum 80% attendance

---

## 🛠️ Technical Details

### Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- All pages < 100KB (without images)
- No external dependencies
- Fast load times
- SEO-friendly semantic HTML

### Accessibility
- Semantic HTML5 tags
- Alt text support for images
- Keyboard navigation friendly
- High contrast text

---

## 📞 Contact Information

**Convener**  
Dr. Satya Prakash Yadav  
Associate Professor, Dept. of CSE  
Email: spycs@mmmut.ac.in  
Mobile: +91-7678647454

**Coordinators**  
Dr. Sumit Kumar: skcs@mmmut.ac.in (+91-8127710956)  
Dr. Pradeep Kumar Singh: pkcse@mmmut.ac.in  
Dr. Pawan Kumar Mall: pkmcse@mmmut.ac.in

---

## 📝 License

© 2025 FDP PRIMEAI-2025 | Department of Computer Science & Engineering, MMMUT Gorakhpur

---

## 🎯 Next Steps

1. ✅ Add images to `images/` folder (see `IMAGES-NEEDED.md`)
2. ✅ Update registration link in homepage
3. ✅ Test on mobile devices
4. ✅ Deploy to your preferred hosting platform
5. ✅ Share the website link with participants!

---

**Website is ready to go live! 🚀**
