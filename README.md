<div align="center">

<!-- Hero Banner & Header Logo -->
<a href="https://github.com/parvesmosarof35/beautyShop">
  <img src="./public/images/logo.png" alt="LUNEL Beauty Logo" width="220" />
</a>

<br />
<br />

<a id="overview"></a>

# LUNEL Beauty — Modern Full-Stack E-Commerce Platform

**A premier, cloud-optimized e-commerce platform and administrative content management suite for luxury beauty and skincare, delivering seamless shopping experiences, dynamic catalog filtering, real-time cart persistence, and end-to-end order governance.**

<br />

<a id="tech-stack"></a>

<!-- Tech Stack Badges (for-the-badge style) -->

[![Next.js 16](https://img.shields.io/badge/Next.js%2016-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React 19](https://img.shields.io/badge/React%2019-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![TypeScript 5](https://img.shields.io/badge/TypeScript%205-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux-toolkit.js.org/)
[![Ant Design](https://img.shields.io/badge/Ant%20Design-0170FE?style=for-the-badge&logo=antdesign&logoColor=white)](https://ant.design/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge&logo=recharts&logoColor=white)](https://recharts.org/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](#license)

<br />

<a id="cta-links"></a>

<!-- Live Demo & CTA Links -->
<p align="center">
  <a href="https://lunelwellness.com/"><b>Explore Live</b></a> &nbsp;•&nbsp;
  <a href="#architecture"><b>Architecture</b></a> &nbsp;•&nbsp;
  <a href="#core-features"><b>Core Features</b></a> &nbsp;•&nbsp;
  <a href="https://github.com/TAIJULAMAN/LUNEL-Modern-Telehealth-Healthcare-E-Commerce-Platform/issues"><b>Report Bug</b></a> &nbsp;•&nbsp;
  <a href="https://github.com/TAIJULAMAN/LUNEL-Modern-Telehealth-Healthcare-E-Commerce-Platform/issues"><b>Request Feature</b></a>
</p>

<br />

<!-- Hero Banner Graphic -->
<img src="./public/images/hero-bg.png" alt="LUNEL Beauty Platform Overview" width="100%" />

</div>

---

## Table of Contents

- [ Title & Value Proposition](#overview)
- [ Tech Stack Badges](#tech-stack)
- [ Live Demo & CTA Links](#cta-links)
- [ Interface Preview](#interface-preview)
- [ Core Features & Platform Modules](#core-features)
  - [ Customer Storefront & Catalog Discovery](#storefront-catalog)
  - [ Dynamic Cart, Wishlist & Checkout System](#cart-checkout)
  - [ User Account, Security & OTP Authentication](#user-auth)
  - [ Centralized Admin Dashboard & Sales Analytics](#admin-analytics)
  - [ Inventory & Product Lifecycle Management](#product-management)
  - [ Order Processing & Fulfillment Hub](#order-fulfillment)
  - [ Dynamic Editorial Blog & Content CMS](#editorial-cms)
- [ Engineering Highlights & Architecture](#architecture)
  - [ System Architecture Overview](#system-architecture)
  - [ Role & Domain Access Matrix](#rbac-matrix)
- [ Project Directory Structure](#project-structure)
- [ Developer Info & Socials](#developer-info)
- [ License & Proprietary Notice](#license)

---

<a id="interface-preview"></a>

## Interface Preview

Discover a refined aesthetic, intuitive customer journeys, and responsive administrative dashboards crafted with Next.js 16, Tailwind CSS, Ant Design, and Recharts.

|                             **Luxury Skincare & Hero Showcase**                             |                                   **Curated Product Collections**                                    |
| :-----------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: |
| <img src="./public/images/a-hero.png" alt="Hero Showcase & Brand Experience" width="480" /> | <img src="./public/images/collection1.webp" alt="Curated Collections & Seasonal Sets" width="480" /> |
|                   _High-converting storefront hero & brand storytelling_                    |                         _Curated seasonal bundles & trending skincare lines_                         |

|                         **Product Showcase & Presentation**                          |                           **Editorial Beauty Journal**                            |
| :----------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------: |
| <img src="./public/images/p1.png" alt="Product Presentation Showcase" width="480" /> | <img src="./public/images/b1.png" alt="Editorial Beauty Blog Post" width="480" /> |
|                    _Detailed product attributes & pricing badges_                    |                _Engaging editorial blog articles & skincare tips_                 |

---

<a id="core-features"></a>

## Core Features & Platform Modules

LUNEL Beauty is engineered with a dual-engine architecture: a high-speed customer shopping experience and a comprehensive administrative portal for operational precision.

<a id="storefront-catalog"></a>

### **Customer Storefront & Catalog Discovery**

- **Faceted Product Exploration**: Filter by price brackets, category classifications, skin concerns, and availability in real time.
- **Hero & Promotional Banners**: Dynamic homepage carousels showcasing seasonal product drops and limited-time offers.
- **Rich Product Detail Pages**: High-resolution gallery view, ingredient breakdown, usage guides, and customer review aggregates.
- **Client-Side Search**: Fast, responsive search index with instant autocomplete suggestions.

<a id="cart-checkout"></a>

### **Dynamic Cart, Wishlist & Checkout System**

- **Persistent Shopping Cart**: Cross-session state persistence powered by Redux Persist and server-synchronized RTK Query endpoints.
- **Interactive Wishlist**: One-click product bookmarking allowing customers to save favorites and transfer directly to cart.
- **Celebratory Checkout UX**: Integrated `react-confetti` celebrations upon successful order placement.
- **Transparent Order Totals**: Automated subtotal calculations, dynamic shipping fees, and promotional coupon discounts.

<a id="user-auth"></a>

### **User Account, Security & OTP Authentication**

- **JWT-Powered Security**: Secure token issuance, storage, and automated header injection via RTK Query interceptors.
- **One-Time Password (OTP) Verification**: Email verification and multi-step OTP security flows for account validation.
- **Password Recovery Pipeline**: Seamless forgot-password and reset-password workflows with time-limited tokens.
- **Customer Self-Service Hub**: Centralized account dashboard with personal profile updates, delivery addresses, and past order history.

<a id="admin-analytics"></a>

### **Centralized Admin Dashboard & Sales Analytics**

- **Executive KPI Dashboard**: Instant visibility into total revenue, order count, registered customer volume, and monthly sales growth.
- **Interactive Sales Charts**: Visual trend graphs powered by Recharts comparing revenue and order volume across time horizons.
- **Recent Activity Ledger**: Real-time view of latest purchases, customer signups, and stock alert notifications.

<a id="product-management"></a>

### **Inventory & Product Lifecycle Management**

- **Full Product CRUD**: Create, edit, and archive products with SKU identifiers, multiple image URLs, category tags, and pricing tiers.
- **Collection Curation**: Group products into seasonal collections with customized marketing banners and promotional copy.
- **Stock & Inventory Oversight**: Real-time inventory tracking preventing overselling and highlighting low-stock items.

<a id="order-fulfillment"></a>

### **Order Processing & Fulfillment Hub**

- **Lifecycle Order Tracking**: Manage orders through Pending, Processing, Dispatched, Delivered, and Cancelled stages.
- **Customer Purchase Insights**: Detailed breakdown of ordered items, shipping addresses, transaction totals, and payment status.
- **Instant Alerts**: User feedback and administrative confirmations using SweetAlert2 dialogs.

<a id="editorial-cms"></a>

### **Dynamic Editorial Blog & Content CMS**

- **Integrated Rich Text Editor**: Compose and format rich skincare blog posts with `jodit-react`.
- **Dynamic Legal & Brand CMS**: Manage About Us, Frequently Asked Questions (FAQ), Privacy Policy, and Terms & Conditions directly from the admin panel.
- **Newsletter Subscription Hub**: Capture visitor email leads with automated subscriber list management.

---

<a id="architecture"></a>

## Engineering Highlights & Architecture

<a id="system-architecture"></a>

### System Architecture Overview

LUNEL Beauty employs modern web patterns featuring Next.js 16 App Router route grouping `(admin)` and `(user)`, Redux Toolkit for predictable client state, and RESTful API endpoints.

```
+-----------------------------------------------------------------------------------+
|                              Storefront & Admin UI (Browser)                      |
|   Next.js 16 App Router | React 19 | Tailwind CSS | Ant Design | Recharts         |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼ (Typed Hooks: useAppDispatch / useAppSelector)
+-----------------------------------------------------------------------------------+
|                             State & Persistence Layer                             |
|   Redux Toolkit Store | Redux Persist | authSlice.ts | LocalStorage Token Cache   |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼ (RTK Query API Slices / baseApi.ts)
+-----------------------------------------------------------------------------------+
|                             Backend API Gateway Layer                             |
|   Express / REST API | JWT Bearer Interceptors | Rate Limiting | Validation Rules |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼
+-----------------------------------------------------------------------------------+
|                             Database & Cloud Infrastructure                       |
|   MongoDB Database | Firebase Services | Cloudinary / Unsplash Media CDN          |
+-----------------------------------------------------------------------------------+
```

<a id="rbac-matrix"></a>

### Role & Domain Access Matrix

| Feature / Domain             | Store Guest | Registered Customer | Admin Staff | Super Admin |
| :--------------------------- | :---------: | :-----------------: | :---------: | :---------: |
| **Browse Catalog & Blog**    | Full Access |     Full Access     | Full Access | Full Access |
| **Shopping Cart & Wishlist** | Full Access |     Full Access     | Full Access | Full Access |
| **Order Placement**          | Full Access |     Full Access     |     ❌      |     ❌      |
| **Order History & Profile**  |     ❌      |     Full Access     | View (All)  | Full Access |
| **Sales & Revenue Charts**   |     ❌      |         ❌          | Full Access | Full Access |
| **Product & Stock CRUD**     |     ❌      |         ❌          | Full Access | Full Access |
| **Collection Management**    |     ❌      |         ❌          | Full Access | Full Access |
| **Content CMS & Blog Admin** |     ❌      |         ❌          | Full Access | Full Access |
| **Staff & Admin Management** |     ❌      |         ❌          |  View Only  | Full Access |

---

<a id="project-structure"></a>

## Project Directory Structure

```plaintext
beautyShop/
├── app/                                # Next.js 16 App Router (Admin & Storefront Route Groups)
│   ├── (admin)/                        # Administrative portal routes
│   │   ├── admin/
│   │   │   ├── dashboard/              # Analytics, sales charts, revenue metrics & overview
│   │   │   ├── products/               # Product CRUD, inventory control, pricing & media uploads
│   │   │   ├── collections/            # Seasonal & curated product collection management
│   │   │   ├── orders/                 # Order tracking, dispatch statuses & invoice details
│   │   │   ├── customers/              # Registered customer directory & purchase history
│   │   │   ├── blog/                   # Rich-text blog post editor (Jodit React) & publishing
│   │   │   ├── admins/                 # Administrator credentials & role assignments
│   │   │   ├── profile/                # Admin profile settings & security preferences
│   │   │   ├── about-us/               # Dynamic CMS for About Us brand story
│   │   │   ├── contact/                # Contact inquiry management & support channels
│   │   │   ├── faq/                    # Frequently asked questions management
│   │   │   ├── privacy-policy/         # Privacy policy terms & compliance CMS
│   │   │   └── terms/                  # Terms of service management
│   │   └── layout.tsx                  # Admin portal shell with responsive sidebar navigation
│   ├── (user)/                         # Customer-facing storefront routes
│   │   ├── about/                      # Brand story & ethical beauty philosophy
│   │   ├── account/                    # Customer profile, saved addresses & order history
│   │   ├── blog/                       # Beauty editorial articles, skincare guides & tutorials
│   │   ├── cart/                       # Interactive shopping cart drawer & item counter
│   │   ├── contact/                    # Customer support request form & inquiries
│   │   ├── cookies/                    # Cookie policy & consent details
│   │   ├── faq/                        # Customer self-service help & FAQs
│   │   ├── forgot-password/            # Password recovery initiation
│   │   ├── login/                      # Customer & staff authentication login
│   │   ├── otp/                        # One-time passcode (OTP) verification
│   │   ├── privacy/                    # Privacy policy legal documentation
│   │   ├── products/                   # Detailed single product view, zoom & reviews
│   │   ├── register/                   # New customer registration portal
│   │   ├── reset-password/             # Token-based secure password reset
│   │   ├── shop/                       # Faceted product catalog with filters & search
│   │   ├── terms/                      # Terms & conditions documentation
│   │   ├── verify-email/               # Email verification callback handler
│   │   ├── wishlist/                   # User saved favorite items & quick-cart transfer
│   │   └── page.tsx                    # Storefront homepage (Hero, Curated Collections, Art of Beauty)
│   ├── actions/                        # Next.js server actions & server-side operations
│   ├── components/                     # Storefront & dashboard presentation components
│   │   ├── dashboard/                  # Administrative analytics widgets & data tables
│   │   ├── ui/                         # Atomic interface primitives
│   │   ├── ArtOfPureBeauty.tsx         # Brand value proposition presentation section
│   │   ├── CollectionSection.tsx       # Dynamic product collections showcase
│   │   ├── FeaturedCollection.tsx      # Curated seasonal featured items gallery
│   │   ├── FilterComponent.tsx         # Multi-criteria filter options & price sliders
│   │   ├── FilterSidebar.tsx           # Faceted drawer sidebar for catalog filtering
│   │   ├── Footer.tsx                  # Storefront footer with links & newsletter signup
│   │   ├── Header.tsx                  # Main header with search, cart badge & profile menu
│   │   ├── HeroSection.tsx             # Promotional hero carousel & seasonal banners
│   │   ├── LunelPromise.tsx            # Guarantee, cruelty-free & authenticity badges
│   │   ├── Popup.tsx                   # Special promotional & discount modal overlay
│   │   └── ProductCard.tsx             # Reusable product display card with hover actions
│   ├── context/                        # React Context state providers
│   ├── data/                           # Static datasets, categories & mock configurations
│   ├── store/                          # Centralized Redux Toolkit state architecture
│   │   ├── api/                        # RTK Query API slice endpoints
│   │   │   ├── aboutUsApi.ts           # About Us CMS content endpoint
│   │   │   ├── adminApi.ts             # Administrator account endpoints
│   │   │   ├── analyticsApi.ts         # Sales, order & customer growth metrics
│   │   │   ├── authApi.ts              # Authentication, login, signup & OTP endpoints
│   │   │   ├── baseApi.ts              # RTK Query base configuration with JWT interceptors
│   │   │   ├── blogApi.ts              # Editorial blog CRUD endpoints
│   │   │   ├── cartApi.ts              # Server-synchronized shopping cart endpoints
│   │   │   ├── collectionApi.ts        # Product collections & curated bundles
│   │   │   ├── contactApi.ts           # Contact messages & customer inquiries
│   │   │   ├── dashboardStatsApi.ts    # Dashboard KPI metrics & summary charts
│   │   │   ├── faqApi.ts               # Frequently asked questions endpoints
│   │   │   ├── orderApi.ts             # Order lifecycle, status updates & invoice API
│   │   │   ├── privacyApi.ts           # Privacy policy content endpoints
│   │   │   ├── productApi.ts           # Product details, search & filtering API
│   │   │   ├── productsApi.ts          # Catalog endpoints & product batch operations
│   │   │   ├── reviewsApi.ts           # Customer product reviews & ratings
│   │   │   ├── settingsApi.ts          # Store configuration & metadata settings
│   │   │   ├── subscriberApi.ts        # Newsletter subscription registry
│   │   │   ├── termsApi.ts             # Terms of service content endpoints
│   │   │   ├── userApi.ts              # Customer profile & account management
│   │   │   ├── webContentApi.ts        # Dynamic site-wide banner & marketing content
│   │   │   └── wishlistApi.ts          # Customer wishlist synchronization
│   │   ├── config/                     # Environment & third-party service configs
│   │   │   ├── envConfig.ts            # Base API URL resolvers & WebSocket setup
│   │   │   └── firebase.ts             # Firebase client SDK initialization
│   │   ├── authSlice.ts                # Redux authentication slice with JWT decoding
│   │   ├── hooks.ts                    # Typed Redux hooks (useAppDispatch, useAppSelector)
│   │   └── index.ts                    # Root Redux store configuration with Redux Persist
│   ├── favicon.ico                     # Storefront favicon
│   ├── globals.css                     # Global styles & Tailwind CSS declarations
│   └── providers.tsx                   # Client-side store hydration & provider wrappers
├── components/                         # Global shared UI components (Radix & Tailwind)
│   └── ui/                             # Primitive components (Button, Label, Dialog, Slot)
├── lib/                                # Core utility functions & CSS class mergers (cn)
├── public/                             # Public static assets & media
│   └── images/                         # Logos, hero graphics, collection banners & products
├── components.json                     # shadcn/ui component registry manifest
├── Dockerfile                          # Containerized deployment blueprint
├── next.config.js                      # Next.js compiler & remote image domains (Unsplash, Cloudinary)
├── package.json                        # Project dependencies, scripts & metadata
├── pnpm-lock.yaml                      # Deterministic dependency lockfile
├── postcss.config.js                   # PostCSS & Tailwind CSS processing pipeline
├── tailwind.config.js                  # Tailwind design system, typography & color tokens
└── tsconfig.json                       # TypeScript compiler options & module aliasing (@/*)
```

---

<a id="developer-info"></a>

## Developer Info & Socials

LUNEL Beauty is developed and maintained by experienced full-stack web and e-commerce software engineers.

- **Md. Parves Mosarof** — _Lead Full-Stack Software Engineer & Maintainer_
  - 🌐 GitHub: [@parvesmosarof35](https://github.com/parvesmosarof35)
  - 📧 Email: [parvesmosarof35@gmail.com](mailto:parvesmosarof35@gmail.com)

- **Md Shah Aman Patwary** — _Full-Stack Software Engineer & Architectural Contributor_
  - 🌐 GitHub: [@TAIJULAMAN](https://github.com/TAIJULAMAN)
  - 📧 Email: [mdshahamanpatwary@gmail.com](mailto:mdshahamanpatwary@gmail.com)

---

<a id="license"></a>

## License & Proprietary Notice

Copyright © 2026 LUNEL Beauty. All rights reserved.

This software, including its user interface design, administrative dashboard logic, and underlying codebase, is private and proprietary. Unauthorized copying, modification, redistribution, or commercial use without prior written consent from the copyright owners is strictly prohibited.

<div align="center">
  <b>Built with ❤️ for luxury skincare and seamless e-commerce experiences</b>
</div>
