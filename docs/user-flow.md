# Core Consumer User Flow

## 1. Overview

This document describes the core consumer journey for the Retail & E-commerce Multi-Vendor Marketplace App.

The flow illustrates how users navigate from the Home Page to the Cart Page, including potential edge cases that could interrupt the shopping experience.

**Objective:** To provide a simple, intuitive, and reliable shopping experience while ensuring users receive helpful feedback when something goes wrong.

## 2. Core User Flow (Happy Path)

The primary shopping journey consists of four steps:

### Step 1: Home — Entry Point
The user opens the application and begins exploring available products.

**Primary Action:**
- Browse featured products or categories.
- Start searching for a product.

**Edge Case: Slow Network**
- Display skeleton loading placeholders while content loads.
- Keep the interface responsive.
- Avoid showing a blank screen during loading.

### Step 2: Results — Filter & Sort
The user browses search results and refines the available products.

**Primary Actions:**
- Browse product listings.
- Apply filters.
- Sort products according to preferences.

**Edge Case: No Results**
- Display a clear "No results found" message.
- Suggest trying different search terms.
- Allow the user to modify filters or start a new search.

### Step 3: Product Page — Compare & Choose
The user opens a product detail page to evaluate the product before purchasing.

**Primary Actions:**
- Review product images and information.
- Check price and availability.
- Review seller information.
- Compare available options and choose a product.

**Edge Case: Out of Stock**
- Clearly indicate that the product is unavailable.
- Provide a "Notify Me" option if supported.
- Suggest similar or alternative products where appropriate.

### Step 4: Cart — Review Order
The user reviews the selected products before proceeding to checkout.

**Primary Actions:**
- Review selected products.
- Update quantities or remove items.
- Review the order summary.
- Continue to checkout.

**Edge Case: Empty Cart**
- Display a clear "Your cart is empty" message.
- Provide a "Start Shopping" action.
- Show trending or recommended products to encourage product discovery.

## 3. User Flow Diagram

Home
  |
  |--------------------> Slow Network
  |                       Show skeletons
  |
  v
Results
  |
  |--------------------> No Results
  |                       Try other terms
  |
  v
Product Page
  |
  |--------------------> Out of Stock
  |                       Notify me
  |
  v
Cart
  |
  |--------------------> Empty Cart
                          Show trending

## 4. Edge Case Handling

| Stage | Edge Case | UX Solution |
|---|---|---|
| Home | Slow network | Show skeleton loading placeholders |
| Results | No results | Suggest alternative search terms |
| Product Page | Out of stock | Offer a notification option |
| Cart | Empty cart | Show trending or recommended products |

## 5. UX Design Principles

The user flow follows these principles:

- **Visibility of System Status:** Skeleton screens communicate that content is loading.
- **Error Prevention and Recovery:** Helpful suggestions allow users to recover from unsuccessful searches.
- **User Control:** Users can modify searches, filters, and cart contents.
- **Consistency:** Error and empty states should use clear, consistent messaging.
- **User Guidance:** Provide meaningful next steps instead of leaving users at a dead end.

## 6. Expected Outcome

The flow aims to help users discover products, evaluate their options, and add items to their cart with minimal confusion.

By designing for both the happy path and edge cases, the application can provide a more reliable and user-friendly shopping experience.

## 7. Design Reference

**Project:** Retail & E-commerce — Multi-Vendor Marketplace App

**Figma Page:** 02_Research & Flows

**Flow Diagram:** Core Consumer Flow

**Figma Link:** https://www.figma.com/board/erAmhwLawxRCDPtujUlWlU/IA---UF?node-id=0-1&t=cjsHjIxk6QiJmeZ0-1

**Status:** Completed
