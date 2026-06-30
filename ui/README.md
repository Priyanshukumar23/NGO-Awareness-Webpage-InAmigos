# InAmigos Foundation – NGO Website Feature Enhancement Proposal

## Overview
This design proposal introduces modern, user-centric features to the existing InAmigos Foundation NGO website. The focus is on improving donor trust, volunteer engagement, and providing a transparent, live view of the NGO's impact. 

## Features Proposed

### 1. Smart Donation Dashboard
- **Feature:** A centralized donation card with pre-defined donation amounts (₹500, ₹1000, ₹2000, Custom) and a progress tracker for ongoing campaigns (e.g., EduCare 2024).
- **Benefit:** Enhances donor trust, provides transparency on where funds are going, and increases conversion by making the donation process frictionless.

### 2. Volunteer Registration Portal
- **Feature:** A modern, streamlined form allowing users to easily sign up with their details, skills, and preferred roles (Event Coordinator, Social Media, Field Volunteer).
- **Benefit:** Boosts community engagement and makes it easy to categorize and contact volunteers based on their skill sets.

### 3. Live Impact Dashboard
- **Feature:** Dynamic statistic cards highlighting key achievements: 50,000+ Beneficiaries, 200+ Volunteers, 28 States, and 6 Active Projects.
- **Benefit:** Instantly communicates the scale and success of the foundation's work to new visitors.

### 4. Success Stories & Testimonials
- **Feature:** A dedicated section for reviews from volunteers, donors, and project leads, featuring 5-star ratings and modern card layouts.
- **Benefit:** Builds social proof and credibility for the foundation.

### 5. Upcoming Campaign Timeline
- **Feature:** A vertical timeline showcasing upcoming initiatives (Education Drive, Tree Plantation, Food Distribution, Blood Donation).
- **Benefit:** Keeps the community informed and encourages advance registration for upcoming events.

### 6. AI Assistant Widget
- **Feature:** A floating, responsive chatbot widget offering quick answers to common queries (How to volunteer, How to donate, etc.).
- **Benefit:** Improves user experience by providing instant support and reducing the barrier to entry for potential donors and volunteers.

---

## Deliverables & Implementation Guide

As an AI, I cannot natively export binary `.fig`, `.png`, or `.pdf` files. However, I have provided a **pixel-perfect, high-fidelity HTML/CSS prototype** (`design.html`) that matches the requested 1440x2200 Desktop Frame specifications exactly. 

You can use this file to instantly generate your deliverables:

### 1. Editable Figma File (.fig)
1. Open Figma and create a new design file.
2. Install the **[html.to.design](https://www.figma.com/community/plugin/1159123024924406060/html-to-design)** plugin from the Figma Community.
3. Open `design.html` in your web browser.
4. Use the plugin's browser extension or paste the local file URL into the plugin within Figma.
5. Figma will instantly convert the HTML layout into fully editable, auto-layout Figma components.
6. Save the file as `NGO_Feature_Proposal.fig` inside the `ui/` folder.

### 2. High-Resolution PNG
1. Open `design.html` in Google Chrome or Edge.
2. Open Developer Tools (F12).
3. Press `Ctrl + Shift + P` (or `Cmd + Shift + P` on Mac) to open the command menu.
4. Type `Capture full size screenshot` and press Enter.
5. Save the resulting image as `NGO_Feature_Proposal.png` inside the `ui/` folder.

### 3. PDF Export
1. Open `design.html` in your web browser.
2. Press `Ctrl + P` (or `Cmd + P` on Mac) to open the Print dialog.
3. Set the destination to **Save as PDF**.
4. Set margins to "None" and ensure "Background graphics" is enabled.
5. Save the file as `NGO_Feature_Proposal.pdf` inside the `ui/` folder.

---

## Future Integration Steps (HTML/CSS/JS)
To implement these features into your existing `index.html`, `style.css`, and `script.js` files:

1. **Modular Components:** Copy the specific HTML blocks (e.g., `<div class="card">...</div>`) from `design.html` and place them into new sections within your `index.html`.
2. **CSS Variables:** Add the color variables (`--primary`, `--primary-light`, etc.) from `design.html` into the `:root` pseudo-class of your existing `style.css`.
3. **Typography:** Ensure the `Inter` font is imported in your global stylesheet to maintain the modern typography.
4. **JavaScript Interactivity:**
   - **Donation Buttons:** Add event listeners in `script.js` to toggle the `.active` class on the donation buttons when clicked.
   - **AI Chatbot:** Implement a simple toggle function in `script.js` to hide/show the chatbot widget when the robot icon is clicked.
   - **Live Impact Dashboard:** Use `setInterval` in `script.js` to create an animated number counter effect for the statistics when the section scrolls into view.
