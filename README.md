# Portfolio AI Demo

> A polished Next.js portfolio website for a professor and AI researcher, built with RTL-first content, smooth motion, and a clean modular structure.

[![Live Preview](https://img.shields.io/badge/Live%20Preview-Add%20your%20link%20here-2563eb?style=for-the-badge)](#live-preview)
[![GitHub Repository](https://img.shields.io/badge/GitHub-mobindeimekar%2Fmodern--academic--portfolio--next.js-111827?style=for-the-badge)](https://github.com/mobindeimekar/modern-academic-portfolio-next.js)
[![فارسی README](https://img.shields.io/badge/README-فارسی-0f766e?style=for-the-badge)](./README.fa.md)

![Hero section preview](./public/images/readme/hero-section.png)

## Overview

This project is a personal portfolio experience centered on an academic and research-focused identity. The site introduces the person in the hero section, highlights about and research areas, presents a history/timeline section, showcases selected work, and provides a contact flow for direct communication.

The codebase is built with Next.js App Router and organized into small reusable components, so the layout stays maintainable while still feeling visually refined.

## Live Preview

portfoliodemo.mobincodes.com

## Repository

Source code:

**This repository**

## Highlights

- RTL-first Persian content with a polished academic tone.
- Strong hero section with a profile image, clear typography, and soft background glow.
- Sections for About, Research Areas, History, Selected Work, and Contact.
- Smooth animation layer using Framer Motion and reusable reveal wrappers.
- Modular component structure for easy edits and future expansion.
- Swiper-powered selected work carousel.
- Theme controls included in the layout for a more dynamic portfolio experience.

## Tech Stack

| Area | Tools |
| --- | --- |
| Framework | Next.js 16, React 19 |
| Styling | Tailwind CSS 4 |
| Animation | Framer Motion |
| Carousel | Swiper |
| State | Redux Toolkit, React Redux |

## Project Structure

```txt
src/
  app/                     App Router pages, layout, and global styles
  components/              Hero, about, history, selected work, contact, footer, navigation
  data/                    Content and section data
  icons/                   Custom icon components
  redux/                   Store and UI state
  utils/                   Shared helpers

public/
  images/                  Portfolio images used throughout the site
```

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Then open `http://localhost:3000`.

## Available Scripts

```bash
npm run dev      # Start the local development server
npm run build    # Build for production
npm run start    # Run the production server
npm run lint     # Run ESLint
```

## Notes

- The hero preview image used in this README comes from the project assets.
- If you publish this portfolio, replace the Live Preview badge link with the final deployment URL.

## README Language

- فارسی: [README.fa.md](./README.fa.md)
