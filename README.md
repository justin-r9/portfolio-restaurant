# The Native Grill 🔥
**Upscale Culinary Web Experience**

A highly performant, multi-page web application designed for a modern, upscale Nigerian restaurant. Escaping the "generic template" trap, this project utilizes a custom "Refined Embers" design system to deliver a moody, cinematic, and friction-free mobile-first experience.

---

## 🏗️ Tech Stack
- **Framework:** Astro 5
- **Styling:** Tailwind CSS v4
- **Architecture:** Multi-Page Application (MPA)

## ✨ Key Features

### 1. "Refined Embers" Design System
A meticulously crafted aesthetic directive tailored to high-end Nigerian cuisine:
- **Color Palette:** Deep charcoal bases (`surface: #131313`) contrasted with Suya-red and burnt orange accents.
- **Typography:** Editorial pairing of **Playfair Display** (display/headings) and **Inter** (body/labels).
- **Textures:** Extensive use of `backdrop-blur` glassmorphism and subtle gradient overlays to simulate a dimly lit, smoky atmosphere.

### 2. High-Performance Architecture
Built with Astro to prioritize speed and SEO. By leaning into a Multi-Page Architecture (MPA), the site ships near-zero client-side JavaScript. Interactivity (like the mobile slide-out drawer) is handled with vanilla, DOM-direct JavaScript, ensuring instant load times and peak Core Web Vitals.

### 3. Friction-Free User Experience
- **Mobile-First Layouts:** Optimized for one-handed navigation, featuring sticky category headers on the Menu page.
- **Micro-Interactions:** Subtle hover states, `active:scale-95` tactile feedback, and smooth view transitions.
- **Narrative Assembly:** A masonry-style "Our Story" layout that integrates typography with imagery to visually tell the brand's heritage.

## 🚀 Getting Started

### Prerequisites
- **Node.js 22+**
- npm / yarn / pnpm

### Installation
Clone the repository:
```bash
git clone https://github.com/justin-r9/portfolio-restaurant.git
cd portfolio-restaurant
```

Install dependencies:
```bash
npm install
```

Run the development server:
```bash
npm run dev
```
Open `http://localhost:4321` with your browser to see the result.

## 📂 Project Brief / Case Study

**Objective:** The goal was to engineer a distinct, personality-driven restaurant website for the Nigerian market. Instead of relying on a bland "insert-food-here" template, the site was built to act as a high-impact hub. It allows potential customers to find crucial information immediately (hours, location) while providing clear, cinematic pathways to explore the full menu and the restaurant's story.

**Constraint:** The application needed to balance heavy, atmospheric imagery and complex CSS effects (glassmorphism, arbitrary shadows) with peak web performance. This was solved by adopting Astro to statically generate the pages, stripping away the heavy JavaScript bundles typically associated with modern UI frameworks, and natively integrating Tailwind v4's optimized CSS engine.
