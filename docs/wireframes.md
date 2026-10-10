# Low-Fidelity Wireframes Documentation

## Overview
This document outlines the low-fidelity wireframes created for the Core Consumer Flow of the Multi-Vendor Marketplace App during Week 1. The designs focus on structure, layout, and content hierarchy without introducing colors or images, providing a solid foundation for the subsequent design system and high-fidelity UI phases.

## Core Consumer Flow

### 1. Home Page
- **Header:** Fixed search bar to allow quick product and vendor discovery.
- **Hero Banner:** Placeholder for promotional content (e.g., Autumn Sale).
- **Top Vendors:** A horizontally scrollable carousel featuring vendor profiles (e.g., UrbanNest, SoundHub) to encourage brand exploration.
- **Daily Deals:** A 2-column grid showcasing discounted items to drive immediate engagement.
- **Navigation:** Fixed bottom navigation bar with Home set as the active state.

### 2. Category Search Page
- **Header:** Retains the fixed search bar for context continuity.
- **Filters:** Includes "Filter" and "Sort" pill buttons immediately below the search to refine results.
- **Results Grid:** A 2-column product grid specifically for a chosen category (e.g., Headphones).
- **Navigation:** Bottom navigation bar with "Categories" set as the active state.

### 3. Product Detail Page (PDP)
- **Gallery:** Large image placeholder with pagination dots, along with back and wishlist buttons.
- **Product Details:** Title, price, and a 4-out-of-5-star rating placeholder.
- **Vendor Information:** A dedicated "Sold by: [Vendor Name]" block to build trust in individual sellers.
- **Description:** A 4-line text block for product details.
- **Call to Action (CTA):** A sticky, full-width "Add to Cart" button in the darkest gray to ensure prominence.

### 4. Cart Page
- **Header:** Displays the total item count (e.g., "Your Cart (3 items)").
- **Cart Items:** A vertical list showing the product image, title, vendor name, price, and a quantity stepper (- 1 +).
- **Order Summary:** A breakdown of Subtotal, Tax, Shipping, and Total.
- **Call to Action (CTA):** A sticky, full-width "Proceed to Checkout" button.

## Design Specifications & Notes

- **Layout:** All frames are built using Figma Auto-Layout, logically dividing the screen into status bar, fixed header, scrollable content, and fixed bottom navigation.
- **Typography:** The *Inter* typeface is used exclusively to establish hierarchy (Bold for headings, Semi Bold for labels, Regular for body text).
- **Grid System:** The layout strictly adheres to an 8pt grid system. Frame region heights and padding are multiples of 8. Product cards (172.5px) appropriately split the 361px content width.
- **Color Palette:** Strictly grayscale, utilizing contrast to draw attention to primary actions (e.g., darkest gray for CTAs).
- **Structural Improvements:** Currently, elements like cards, the nav, buttons, and the search bar are repeated frames. In Week 2 (Design System), these should be turned into Master Components with variants (e.g., nav active states, button hover states) and linked to color and text variables to improve reusability.
