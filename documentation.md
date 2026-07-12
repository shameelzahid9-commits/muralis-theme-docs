# Muralis — Theme documentation

Muralis is a premium Shopify theme built for custom print, canvas, photo-tile, and
wall-art stores. It pairs a bold, gallery-style storefront with a guided
"create your own" shopping flow, multi-level navigation, and a complete set of
Online Store 2.0 sections and blocks.

This guide explains how to set up and customize every part of the theme from the
**Shopify theme editor** (Online Store → Themes → Customize). No code is required.
Setting and section names below match exactly what you see in the editor.

- **Theme version:** 1.6.2
- **Support:** see [Support and contact](#support-and-contact) at the end of this guide.
- **Compatibility:** Online Store 2.0, all modern desktop and mobile browsers.

---

## Table of contents

1. [Getting started](#1-getting-started)
2. [Theme settings](#2-theme-settings)
3. [Header](#3-header)
4. [Footer](#4-footer)
5. [Home page](#5-home-page)
6. [Product pages](#6-product-pages)
7. [Collection and collection list pages](#7-collection-and-collection-list-pages)
8. [Search](#8-search)
9. [Cart](#9-cart)
10. [Customer accounts and orders](#10-customer-accounts-and-orders)
11. [Blog and articles](#11-blog-and-articles)
12. [Gift cards](#12-gift-cards)
13. [Pages and the contact form](#13-pages-and-the-contact-form)
14. [Navigation setup](#14-navigation-setup)
15. [Selling in multiple countries and languages](#15-selling-in-multiple-countries-and-languages)
16. [Subscriptions (selling plans)](#16-subscriptions-selling-plans)
17. [Specialized product and collection templates](#17-specialized-product-and-collection-templates)
18. [Performance and accessibility](#18-performance-and-accessibility)
19. [FAQ](#19-faq)
20. [Support and contact](#20-support-and-contact)

---

## 1. Getting started

1. **Add the theme.** From your Shopify admin, the theme appears under
   **Online Store → Themes**.
2. **Preview before publishing.** Use **Actions → Preview** to explore the theme
   without affecting your live store. Use **Customize** to open the theme editor.
3. **Duplicate before major edits.** Before changing settings or code, use
   **Actions → Duplicate** so you always have a working backup.
4. **Publish when ready.** Use **Actions → Publish** to make Muralis your live theme.

> **Tip:** Demo images shown in the theme preview do not transfer when you install
> the theme. Add your own product photos, collection images, and section images.

---

## 2. Theme settings

Open **Customize → Theme settings** (the gear icon at the bottom of the editor).
Settings are grouped as follows.

### Colors
Muralis uses a small, coordinated palette. Each background has a matching text color
so contrast stays readable.

- **Primary / accent** — buttons, links, highlights, and the sale badge.
- **Headings** — color for headings across the theme.
- **Body text** — default paragraph and body color.
- **Borders and dividers** — card borders, separators, and outlines.
- **Soft section background** — the tinted background used by softer sections.
- **Soft section text** — text color used on the soft background.

### Typography
- **Heading font** — font for headings (uses the Shopify font library).
- **Body font** — font for body text.

Bold, italic, and bold-italic variants load automatically for both fonts.

### Layout
- **Maximum page width** — the maximum content width, in pixels.

### Favicon
- **Favicon image** — the small icon shown in browser tabs. A square image of at
  least 32 x 32px is recommended.

---

## 3. Header

Open the **Header** section in the editor.

- **Logo** — upload your store logo. Works with landscape or portrait images. If no
  logo is uploaded, your store name is used.
- **Main menu** — choose the menu shown in the top navigation. On a fresh install
  this defaults to your store's **Main menu**. The header supports up to three
  levels (see [Navigation setup](#14-navigation-setup)):
  - One level → a plain link.
  - Two levels → a dropdown.
  - Three levels → a mega menu (second level becomes column headings, third level
    becomes the links).
- **Show account icon** — show or hide the customer account icon.

The header also includes **predictive search** (suggestions appear as the customer
types) and a cart link with a live item count.

---

## 4. Footer

Open the **Footer** section.

- **Brand name** and **Brand text** — your store name and a short description.
- **Social media icons** — paste the full URLs for Instagram, Facebook, Pinterest,
  and TikTok. Leave a field empty to hide that icon.
- **Follow on Shop** — a "Follow on Shop" button appears automatically when the Shop
  sales channel is available, so customers can follow your store in the Shop app.
- **Support menu** and **All pages menu** — choose menus for the footer columns.
  These default to your store's **Footer** menu on install.
- **Headings** — set the heading text for each footer column.
- **Show payment icons** — show the payment method icons supported by your store.

A **newsletter signup** form and the **country/region** and **language** selectors
also appear in the footer (the selectors appear only when your store sells in more
than one country or language).

---

## 5. Home page

Open **Customize** with the **Home page** template selected. Add, remove, and
reorder sections from the left panel. Available home-page sections include:

- **Announcement bar** — a slim message bar above the header.
- **Hero** — a full-width banner with heading, text, button, and separate desktop
  and mobile images.
- **Benefits row** — short value props (for example, free shipping or easy returns).
- **How it works** — a step-by-step illustration of your ordering process.
- **Best-selling collections** — highlight collections with images and links.
- **Collections hub**, **Rooms hub**, **Styles hub** — curated card grids that guide
  customers to collections by category, room, or style.
- **Product create cards** — promotional cards that lead into your "create your own"
  product flow.
- **Testimonials** — customer reviews with optional photos.
- **Final CTA** — a closing call-to-action band.
- **Custom liquid** — insert custom Liquid or app snippets anywhere.

Every section has its own heading, text, image, and link settings. Add real images
and copy so the layout looks balanced.

---

## 6. Product pages

The product page is built from **blocks** in the **Main product** section, so you can
reorder or hide elements without code. Available blocks:

- **Price** — current price, compare-at price, sale badge, unit price, Shop Pay
  Installments banner, and the tax-included note (when your prices include tax).
- **Vendor** — the product vendor/brand.
- **Description** — the product description.
- **Custom Liquid** — an insertion point for custom Liquid or app snippets.
- **Trust card** — a small reassurance card (quality, packaging, support). Add several.
- **FAQ item** — a question/answer that appears in the product FAQ band. Add several.
- **App blocks** — any app that provides a product block (for example, reviews) can
  be added here.

The product form (variant selectors, quantity, and the **Add to cart** button) is
always present. Section settings let you control:

- **Show quantity selector**, **Show dynamic checkout button** (accelerated checkout,
  on by default), **Show recipient information form for gift card products**.
- Labels: **Variant selector label**, **Quantity label**, **Add to cart label**,
  **Sold out label**, **FAQ eyebrow**, **FAQ heading**, plus fallback text used when
  no product is assigned.

Product page features built in:

- **Variant options** as separate selectors, with **color and image swatches**.
- **Variant images** — the gallery updates to the selected variant's media.
- **Rich media** — images, 3D models, and videos (Shopify-hosted and YouTube/Vimeo),
  switchable from the thumbnails.
- **Product recommendations** — add the **Product recommendations** section and set
  its intent to **Related** or **Complementary** ("Complete the look").
- **Pickup availability**, **Shop Pay Installments**, and **subscriptions** (see
  [Subscriptions](#16-subscriptions-selling-plans)).
- **Gift card recipient form** — for gift card products, buyers can send the card to
  someone else with an optional delivery date.

> **Add 3D or video:** upload the media to the product in **Products → [product] →
> Media** (Shopify hosts 3D and video). Muralis displays it automatically.

---

## 7. Collection and collection list pages

**Collection page** (the **Main collection** section):

- Shows the collection title, description, and image.
- Products appear in a responsive grid (varying image ratios won't break the layout)
  with title, price (including price ranges for products that vary), unit price, and a
  **Sale** badge when applicable.
- **Show sort** — let customers sort the products.
- **Show filters** — show faceted filters. Filters come from the free
  **Shopify Search & Discovery** app (install it and configure filters such as price,
  type, vendor, and variant options).
- Shows a friendly message when a collection is empty, and supports pagination.
- **SEO text** — add an optional rich-text block at the bottom for SEO copy.

**Collection list page** (the **Main list collections** section) shows each
collection's title and featured image, with pagination.

---

## 8. Search

Muralis includes a dedicated search page (the **Main search** section) plus predictive
search in the header.

- Results are grouped into **Products** and **Articles and pages**.
- **Show filters** adds faceted filtering to product search results (also powered by
  Shopify Search & Discovery).
- Add **Quick link** blocks to suggest popular categories.
- A clear "no results" message appears when nothing matches.

---

## 9. Cart

The cart page (the **Main cart** section) shows each line item's title, options,
image, unit and line price, and quantity. It includes:

- Quantity controls that refresh totals automatically.
- **Cart notes** for order instructions.
- **Automatic discounts** and **accelerated checkout** buttons (on by default).
- Subscription (selling plan) details on subscription line items.
- A tax-included note when your prices include tax, and an empty-cart message.

---

## 10. Customer accounts and orders

Customer account pages (account, orders, addresses, login, register, reset and
activate account) are fully styled. Order pages show each line item's unit price,
unit-of-measure pricing where applicable, and the chosen subscription plan.

---

## 11. Blog and articles

- **Blog page** (the **Main blog** section) lists articles with title, image, and
  excerpt, with pagination.
- **Article page** (the **Main article** section) shows the title, published date,
  content, and a paginated **comments** section (comments work without moderation,
  with success and error messages).

---

## 12. Gift cards

When you sell a gift card product, the gift card page shows the card balance and
code, a **QR code** for in-person redemption, an **Add to Apple Wallet** button, and
your store name or logo. On the product page, buyers can choose to send the gift card
to a recipient with a personal message and delivery date.

---

## 13. Pages and the contact form

- **Page** (the **Main page** section) shows the page title and content.
- **Contact page** — Muralis includes a contact-form page template (**page.contact**).
  Create a page and assign the **Contact** template to it to show a working contact
  form. Muralis also ships ready-made page templates for help, FAQ, shipping, returns,
  size guide, upload guide, photo-quality guide, track order, bulk orders, rooms,
  styles, collections hub, and about.

---

## 14. Navigation setup

Menus are managed in **Online Store → Navigation**, then selected in the theme editor.

1. Create your menus (for example, **Main menu** and **Footer**) in Navigation.
2. For multi-level header menus, add nested items: a top item with child items shows
   a dropdown; child items that themselves have children show a mega menu.
3. In the **Header** section, choose your menu under **Main menu**.
4. In the **Footer** section, choose menus for **Support menu** and **All pages menu**.

If you don't choose a menu, the theme falls back to a built-in default so navigation
still works.

---

## 15. Selling in multiple countries and languages

When you sell in more than one country/currency or language (configure these in
**Settings → Markets**), Muralis automatically shows **country/region** and
**language** selectors in the footer. Prices and content update to the customer's
selection. No theme setup is required.

---

## 16. Subscriptions (selling plans)

If you offer subscriptions (via a subscriptions app that uses Shopify selling plans),
a **purchase options** selector appears automatically on the product page so
customers can choose a one-time purchase or a subscription. The chosen plan is shown
in the cart and on the customer's order page. You can rename the selector labels in
the **Main product** section settings.

---

## 17. Specialized product and collection templates

Muralis includes purpose-built templates for print stores. Assign them to a product or
collection from the admin (**[product/collection] → Theme template**):

- **Product templates:** Default product, **Custom canvas**, **Photo tiles**,
  **Wall art**.
- **Collection templates:** Default plus single canvas, framed canvas, canvas sets,
  canvas bundles, photo tiles, wall art, rooms, and styles variants.
- **Page templates:** about, help, FAQ, contact, shipping, returns, size guide,
  upload guide, photo-quality guide, track order, bulk orders, rooms, styles,
  collections hub.

---

## 18. Performance and accessibility

- Images use responsive loading so phones download appropriately sized files.
- Headings, navigation, forms, and interactive elements are keyboard accessible with
  visible focus states.
- Rich-text (headings, lists, quotes) is styled consistently across product,
  collection, and article content.

For best performance, use appropriately sized images and avoid adding very large
uncompressed media.

---

## 19. FAQ

**How do I change theme colors and fonts?**
Open **Customize → Theme settings → Colors** and **Typography**.

**My navigation links go to "Page not found." Why?**
The menu points to pages or collections that don't exist yet. Create the matching
pages/collections in your admin, or edit the menu in **Online Store → Navigation**.

**How do I add filters to collection and search pages?**
Install the free **Shopify Search & Discovery** app and configure filters there, then
make sure **Show filters** is enabled in the Main collection / Main search sections.

**How do I add a 3D model or video to a product?**
Upload it to the product's media in the admin. Muralis displays 3D models and videos
automatically in the gallery.

**Can I reorder the elements on a product page?**
Yes. The product page is block-based — reorder or hide the Price, Vendor,
Description, and other blocks in the **Main product** section.

**How do I show subscription options?**
Install a subscriptions app that uses Shopify selling plans and assign a plan to the
product. The purchase-options selector then appears automatically.

**Will my changes show in the preview?**
Yes — changes made in the theme editor appear in the editor preview immediately.

**Demo images didn't transfer when I installed the theme. Is that a bug?**
No. Shopify doesn't transfer demo images on install. Add your own media.

---

## 20. Support and contact

We're here to help with theme setup and any issues you find.

- **Contact:** use our support contact form (linked from the theme listing page).
- **Response time:** we reply to support requests within **two business days**.
- **What's covered:** setup questions and bug fixes (for example, a broken layout,
  a dead link, or a logical error in the theme) at no extra cost.
- **What's not included in the theme price:** custom code, custom design work, and
  app integrations. We're happy to discuss these as separate services.

> **Before editing theme code,** always duplicate your theme first
> (**Online Store → Themes → Actions → Duplicate**). For larger customizations, we
> recommend hiring a [Shopify Partner](https://www.shopify.com/partners/directory).
