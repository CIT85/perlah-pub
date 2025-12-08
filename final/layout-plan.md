
## Standards I will follow

I am using a mobile first approach based on the common media query breakpoints.  
For this project my CSS only needs two implemented breakpoints:

- **0–767px:** Mobile devices and small tablets (default styles, no media query needed)
- **768px and up:** Tablets, small laptops, and desktops (main layout and grid changes)
- **1201px and up:** Very large screens and TVs (small enhancement only, such as the fixed “Back to top” button)


## My Responsiveness using Media Queries

### Homepage layout
Header (Flexbox)
├─ Site Title (left)
└─ Nav Menu (right)

Main (Stacked Sections)
├─ Hero Section
│  ├─ Heading
│  ├─ Full-width image
│  └─ Paragraph
├─ Explore Section
│  ├─ Card 1
│  ├─ Card 2
│  └─ Card 3
├─ Ratings Section
│  └─ Ratings Table
├─ FAQs Section
│  └─ FAQ List
└─ Quotes Section (multi-column flow)

Footer (Flexbox)
├─ Footer Links
└─ Contact Info

Back-to-Top Button (Fixed Position)

## **Homepage Responsiveness**

### **Mobile (0–767px)**
- Hero layout uses **one column**  
  - Heading on top  
  - Full-width image  
  - Paragraph underneath  
- Explore cards display **one per row**  
- Navigation wraps naturally and stays centered  
- Ratings table stays 100% width with wrapping text  
- FAQ cards stack vertically  
- Quotes display in natural multi-column flow that collapses gracefully  

### **768px and Up**
- Header switches to a **horizontal** layout  
- Hero section becomes **two columns**  
  - One text column  
  - One image column  
- Explore section becomes a **three-column grid**  
- All typography scales slightly for readability  
- More gap/padding is added to provide breathing room  


### Extra large screens (1201px and up)
- Layout matches the 768px and up version  
- A fixed "Back to top" button appears in the lower right corner of the viewport

---

# **DNF Page**

**Main Layout Using Grid**
- Heading  
- Hero image  
- Rules section with two articles  
- DNF table  
- Donate/Repurpose section  

## **DNF Page Responsiveness**

### **Mobile (0–767px)**
- Everything displays in a **single column**  
- No vertical divider line  
- Table fills container width  

### **768px and Up**
- Page switches to **two-column grid**  
- Decorative gradient divider appears between columns  
- Table and donation section expand across **full width** below the columns  

---

# **Reading Tools Page **

**Content Includes:**
- Hero banner with overlay title  
- Everyday Helpers section  
- Two-column tools section (Distraction Blockers + Formats & Engagement)  
- Comparison table  

## **Reading Tools Responsiveness**

### **Mobile (0–767px)**
- Hero image is full-width  
- Everyday Helpers text stacks naturally  
- Tools layout uses **one column**  
- Comparison table stays readable with wrapped text  

### **768px and Up**
- Tools layout becomes a **two-column grid**  
- Hero heading scales up  
- Section spacing increases for clarity  

---

# **Kept Shelf Page **

**Sections:**
- Intro with hero image and paragraph  
- House rules  
- Table of kept books  
- Favorite quotes  

## **Kept Shelf Responsiveness**

### **Mobile (0–767px)**
- Intro uses a **single column**  
- Rules, table, and quotes stack vertically  

### **768px and Up**
- Intro becomes **two columns**  
  - Heading centered across top  
  - Image and text sit side by side  
- Favorite quotes get increased padding  

---

# **Newsletter Page**

**Sections:**
- Intro with image + paragraph  
- Newsletter Focus  
- Reoccurrence  

## **Newsletter Responsiveness**

### **Mobile (0–767px)**
- Intro image sits above paragraph  
- Focus and Reoccurrence articles stack vertically  

### **768px and Up**
- Intro switches to **image + text side by side**  
- Focus and Reoccurrence switch to **two-column grids**  

---


# **Quotes Page**

**Sections:**
- Page intro with heading, image, and short paragraph  
- Quote Groups section with three themed quote blocks  
- Aside section inviting users to share quotes  

## **Quotes Page Responsiveness**

### **Mobile (0–767px)**
- Intro section stacks vertically with the image centered  
- Quote groups display in a single column for easier reading  
- Blockquotes remain full width and use left padding for visual structure  
- The “share a quote” aside appears as a full-width card below the quotes  

### **768px and Up**
- More spacing is added around each quote group  
- Cards stretch naturally inside the centered layout  
- Blockquotes maintain their formatting but have more horizontal room  
- Layout remains single-column because the content is primarily text-based, but spacing, readability, and balance improve at larger sizes  


# **Site Info / Sitemap Page**

### **Mobile**
- Image sits above list  
- List items stack clearly  

### **768px and Up**
- Content stays centered  
- Image and list have more natural spacing based on wider container  
