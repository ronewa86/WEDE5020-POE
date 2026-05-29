 WEDE5020-POE-Part-1 and 2-Student Welness And Counselling Website

 Student Information 
Name: Ronewa Phuthu
Student Number: ST10534625 
Institution: Rosebank College Braamfointein
Module: WEDE5020 Web Development

Project Overview : A multi-page static website designed to support student mental health by providing information about counselling services, allowing students to book sessions, and offering easy ways to get in touch.


Website Goals & Objectives

-Raise Awareness — Inform students about the importance of mental health and emotional well-being in academic life.
-Provide Accessibility — Make it easy for any student to find support services and understand what is available to them.
-Encourage Help-Seeking — Create a welcoming, stigma-free space that motivates students to reach out when they need help.
-Simplify Booking — Allow students to schedule counselling sessions quickly and easily through an online form.
-Build Trust — Communicate the team's commitment to confidentiality, respect, and professional support.

Changes From part 1 

 The following improvements were made:

 Content & Information
- All pages were expanded with substantially more written content to address the feedback that the site "lacked information"
-about.html — Added team description, qualifications, expanded values section, and a detailed "Why Choose Us" list
- services.html — Grew from four brief paragraphs to six full service cards plus detailed descriptions with bullet points for each service
- contact.html — Added a structured contact information box with email, phone, location, office hours, and a 24/7 crisis line
- book-session.html — Added a referral source dropdown, telephone as a session mode option, and placeholder text to guide users
- index.html — Added a statistics row, service overview cards, three student testimonials, a FAQ accordion section, and an expanded confidentiality section

 Structure & Markup
- Added `<meta name="viewport">` to all pages for proper mobile rendering
- Fixed invalid HTML in `about.html` where `<h2>` and `<p>` tags were incorrectly nested inside a `<ul>`
- Replaced bare `<input>` and `<textarea>` elements in `contact.html` with properly labelled, accessible form fields
- Added `id` attributes to form fields and matching `for` attributes to all labels across all forms
- Added a consistent hero banner section to every page for visual continuity
- Added a shared footer with navigation links on every page

New Files Added 
- style.css 

Key Features & Functionality

Home Page
- Introduction to the Student Wellness platform
- Animated statistics row (students supported, sessions held, counsellors, years of service)
- Service overview cards with icons
- Student testimonials to build trust and relatability
- FAQ accordion section with common questions
- Confidentiality statement reassuring students their information is private
- Call-to-action buttons linking to the Services and Booking pages

 About Us 
- Overview of who the wellness team is
- Clearly stated Mission, Vision, and Values
- Visual values list with checkmarks
- Team composition and qualifications
- "Why Choose Us" section with detailed bullet points


 Services 
 
- Six service cards with icons and descriptions
- Detailed write-ups for each service:
  - Individual Counselling — Private one-on-one sessions
  - Group Workshops — Stress, anxiety, and resilience sessions
  - Peer Support Programme — Student-to-student connection
  - Crisis Support** — Immediate help for urgent emotional distress
  - Academic Stress Support — Help for exam anxiety and burnout
  - Online Counselling — Remote sessions via video or telephone
- Pricing note confirming all services are free for registered students

 Contact 
- Inquiry form with fields for name, email, message, and reason for contact
- structured contact info box displaying email , phone , location , office hours and crisis line
- confidentiality reminder 


Book a Session 
- Structured booking form split into three sections:
  - Personal Information — Full name, student ID, email, phone
  - Session Details — Session type, mode (in-person or online), preferred date and time
  - Additional Information — Description of concerns and preferred contact method
- Submit and reset buttons for easy form control
  
 Typography

The website uses Georgia, a classic serif typeface, as the primary font across all pages. Georgia was chosen because it conveys warmth, professionalism, and calm — qualities appropriate for a mental health platform.

 Site title (h1) , Georgia, serif , 1.6rem , 700 , White on dark green header 
 Page headings (h2) , Georgia, serif , 1.75rem , 700 , Dark green with underline accent 
 Section headings (h3) , Georgia, serif , 1.2rem , 600 , Used inside cards and info boxes 
 Body text (p) , Georgia, serif  ,1.05rem, 400 , Warm mid-grey for readability 
 Navigation links,  Georgia, serif , 0.95rem , 500 , Light green, white on hover 
 Form labels , Georgia, serif , 0.92rem , 600 , Dark text for clear association 
 Footer text , Georgia, serif , 0.9rem , 400 , Soft green on dark background 


Layout


Header
The sticky header uses Flexbox (`display: flex; justify-content: space-between`) to position the site title on the left and navigation links on the right. It remains fixed at the top of the viewport as the user scrolls.

Hero Banner
Each page opens with a full-width hero banner using a linear gradient background. Text is centred using Flexbox and constrained to a maximum width for readability.

Content Sections
Body content is wrapped in a `.content` div with `max-width: 820px` and `margin: 0 auto` to centre it on the page and prevent lines from becoming too wide on large screens.

Cards Grid
Service and feature cards use CSS Grid (`grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))`) to automatically reflow into fewer columns on smaller screens without media queries.

Forms
Booking and contact forms are divided into separate `.form-container` blocks, each with its own white card background and padding. This visually groups related fields and makes long forms feel more manageable.

Footer
The footer uses Flexbox to centre content vertically and horizontally, with a secondary row of navigation links for easy access from the bottom of any page.

Visual Design 

- used green-dark for Header, buttons, headings, footer 
- used green-mid for Accents, card borders, hover states 
- used green-light for Navigation text, decorative elements 
- applied green-pale for Backgrounds, contact info box 
- used cream for Hero banner gradient end colour 
- used warm-white for Page background 
- used text-dark for Primary text 
- used text-mid for Body paragraphs 
- used text-muted` for Secondary text, card descriptions

Responsive Design 

The website is designed to work on desktop, tablet, and mobile screens.
- All widths use `%`, `rem`, or `auto` rather than fixed `px` values where possible
- Images use `width: 100%` and `object-fit: cover` to scale without distortion
- The `<meta name="viewport" content="width=device-width, initial-scale=1.0">` tag is included on every page to ensure correct scaling on mobile devices
- CSS Grid's `auto-fit` and `minmax()` allow the cards grid to reflow automatically without additional media queries

References 

Google Fonts — Typography reference: https://fonts.google.com
South African Depression and Anxiety Group (SADAG) — Reference for crisis support wording: https://www.sadag.org
CSS-Tricks — Flexbox and Grid guides: https://css-tricks.com/snippets/css/a-guide-to-flexbox/ and https://css-tricks.com/snippets/css/complete-guide-grid/
Coolors — Colour palette inspiration: https://coolors.co


 
