
# Chartered Accountants Portfolio

**A professional, responsive portfolio website for CA Arjun Mehta & Associates, featuring modern design, WhatsApp integration, and multiple color schemes.**  

---

## **🚀 Features**  

✅ **Professional Hero Section**  
- Circular CA portrait with elegant border  
- Centered-left aligned content for better readability  
- Responsive design (desktop, tablet, mobile)  

✅ **Multiple Color Schemes**  
- **Blue (Default):** Corporate & trustworthy  
- **Teal:** Modern & approachable  
- **Maroon:** Traditional & authoritative  

✅ **WhatsApp Integration**  
- Floating WhatsApp button with hover tooltip  
- Pre-filled consultation message  
- Mobile-friendly click-to-chat  

✅ **User-Friendly Navigation**  
- Sticky navbar with smooth scrolling  
- Active section highlighting  
- Mobile hamburger menu  

✅ **Conversion-Optimized**  
- Clear call-to-action buttons  
- Testimonials section for social proof  
- Contact form with Netlify support  

---

## **🛠️ Technologies Used**  

- **HTML5** (Semantic markup)  
- **CSS3** (Flexbox, Grid, Variables)  
- **JavaScript** (Basic interactivity)  
- **Font Awesome** (Icons)  
- **Google Fonts** (Inter font family)  

---

## **🎨 Customization Guide**  

### **1. Replace Placeholder Content**  
- **Hero Section:** Update `CA Arjun Mehta` with your client's name  
- **Services:** Modify in the `services-grid` section  
- **Testimonials:** Add real client quotes in `.testimonial-card`  

### **2. Add Your Images**  
```html
<!-- Replace placeholder image in hero section -->
<img src="your-portrait.jpg" alt="CA Your Name" class="ca-portrait">
```
**Recommended:**  
- **Portrait:** 800×800px, professional attire, neutral background  
- **Office Photos:** Add to About section  

### **3. Set Up WhatsApp**  
```javascript
// Change number and default message
setWhatsAppNumber('919876543210', 'Your Firm Name'); 
```

### **4. Choose Color Scheme**  
Add one of these classes to `<body>`:  
- `color-scheme-teal`  
- `color-scheme-maroon`  
*(Remove color-switcher div for production)*  

---

## **📱 Responsive Behavior**  

| Breakpoint        | Adaptations                          |  
|-------------------|--------------------------------------|  
| **Desktop (>992px)** | Side-by-side layout, full navigation |  
| **Tablet (768px)**   | Stacked content, centered portrait   |  
| **Mobile (<576px)**  | Full-width buttons, compact menu     |  

---

## **⚡ Deployment**  

1. **Free Hosting Options:**  
   - [Netlify](https://www.netlify.com/) (Drag-and-drop `index.html`)  
   - [GitHub Pages](https://pages.github.com/)  

2. **Form Handling:**  
   Add this to your form for Netlify:  
   ```html
   <form netlify>
   ```

---

## **🎯 Why This Portfolio Works**  

✨ **Builds Trust** – Professional design establishes credibility  
✨ **Encourages Contact** – WhatsApp integration matches Indian client preferences  
✨ **Showcases Expertise** – Structured services and testimonials  

---

## **📜 License**  
MIT License - Free for personal and commercial use  

---

**💡 Pro Tip:** Add your client's **CA license number** in the footer for added authenticity!  

**Need Help?**  
👉 Customize further by adding:  
- Dark mode toggle  
- Client logo carousel  
- Hindi/English language switch
