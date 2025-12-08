# Book Nook
I am choosing this topic because reading has always been something that grounds me and lets me escape at the same time. It's one of the few things that combines comfort, creativity, and reflection for me. I thought this would make a meaningful topic for my project because it gives me space to write my own thoughts, stay organized, and create a site feels personal but still structured.

## AI Prompts and Content Samples

**To ChatGPT:** Hi! I want to create a simple site called Book Nook where I share the books I've read, what I loved (and didn't), and cozy recommendations by mood/genre. Can you help me with that? I also need a description for the site and anything else you think would be helpful to my idea. 

**ChatGPT:** That sounds like such a cozy idea! Here’s a short description and some ideas to help you get started.

**Site Description:**  
**Book Nook** is a cozy reading corner where you can share the stories that stuck with you — the ones you loved, didn’t love, or can’t stop thinking about. It’s a warm, calm space that mixes reflection, honesty, and comfort. Each page can focus on a different part of your reading life: what you’re reading now, your go-to cozy picks, and favorite authors who inspire you.

**Page Ideas:**
- **Home:** A welcoming intro that explains what Book Nook is about and what visitors will find.  
- **The DNF Pile:** This page is for the books I didn’t finish. I explain why they didn’t work for me or why I decided to stop reading.
- **Reading Tools**  This page shares helpful tools and apps for reading and staying focused.
- **The Kept Shelf:** This page lists the books I finished and really enjoyed. 

**Tone Suggestions:**  
Keep it personal, warm, and reflective — like you’re talking to a friend over tea. Use gentle language, sensory words (soft light, rain, comfort), and simple structure. Add one or two quotes that stuck with you, and use `<time>` or `<cite>` tags where they fit naturally.

## Menu
- Home
- The DNF Pile
- Reading Tools
- The Kept Shelf

## Typography Enhancements
- For this phase, I created a consistent typography system across all pages. I set a base font size and centered body text, applied a clear h1-h4 hierarchy using font-size, font-weight, letter-spacing, and text-transform, and updated global link styles with hover, focus, and visited states. These changes improve readability. accessibility and keep the Book Nook pages visually consistent.

## Decorative or Positional Enhancements
- For this part I added three elements that use different kinds of positioning. My header uses sticky position so the nav stays visible at the top while scrolling. I also created a back to top button that stays fixed in the bottom corner to make navigating the page easier. For the FAQS, I added a small book icon using absolute positioning inside ech list item to give it a little decoration without changing the layout. 

## Phase 3 Overview
- - Header and footer use Flexbox to align the site title and nav links.
- The home page “Explore” cards use CSS Grid to create a flexible card layout.
- The home page “Welcome” section uses Grid for the text + hero image.
- The Newsletter page uses Flexbox for the intro (image and text side by side) and Grid for the two-column sections.

### DNF Page Refactor
- Updated the DNF page to use a structured 2-column Grid layout.
- Positioned the intro/hero image on the left and the House Rules on the right.
- Moved the book table into its own full-width grid row so it could expand naturally without affecting column height.
- Placed the Donate/Repurpose content in a separate full-width row below the table.
- Adjusted the vertical divider so it stops before the table for a cleaner visual flow.
- Removed duplicate or unnecessary text to streamline the content while keeping all requirements.

### Reading Tools Page
- Added a hero banner with the page title placed over the image.
- Positioned “Everyday Helpers” as the intro section below the hero.
- Built a two-column Grid layout for Distraction Blockers and Formats & Engagement.
- Updated heading levels so Formats includes two subsections for outline requirements.
- Cleaned list alignment and spacing for better readability.


## New Subpage (Newsletter)
- I added a Newsletter page that explains what the Book Nook newsletter would focus on and how often it would show up.
- The page uses semantic sections and includes an intro image with figure and figcaption.
- It is linked from the Site Info page (sitemap) and from the footer navigation on every page.
## Image Optimization
- All feature images include width and height attributes to reduce layout shift.
- Hero and card images are styled with CSS to keep proportions (width: 100%; height: auto where appropriate).
- Non-hero images on the home page use loading="lazy" to improve performance.

## Accessibility
Book Nook is built with accessibility in mind so the content stays readable, clear, and easy to navigate for a wide range of users. The site includes the following considerations:

- **Consistent heading hierarchy** across all pages to help screen readers understand the structure of the content.
- **Semantic HTML elements** such as header, nav, main, section, article, and footer, which improve navigation for assistive technologies.
- **Descriptive alt text** on all images so users who cannot see the image still understand its purpose.
- **Clear and meaningful link text** rather than vague phrases, which helps both usability and screen reader clarity.
- **Color choices with strong readability** between text and background so content remains legible.
- **ARIA labels on navigation** to support users who rely on screen readers.
- **Responsive layout**, allowing content to reflow naturally on different screen sizes without forcing horizontal scrolling.

