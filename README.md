# Phone Catalog (Nice Gadgets)

A responsive single-page e-commerce web application built for browsing, searching, and managing consumer electronics, including phones, tablets, and accessories. The platform features dynamic filtering, URL-synchronized state management, shopping cart operations, favorites tracking, and a unified theme toggle.

## Live Preview

[View Live Demo](https://eksonurit.github.io/phone-catalog/)

## Design Reference

[Figma Design Prototype](<https://www.figma.com/file/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog-(V2)-Original>)

## Technologies Used

- React (Hooks, Context API)
- TypeScript
- React Router (URL SearchParams synchronization)
- SCSS / SASS (CSS Modules, BEM methodology, theme variables)
- Vite (Build tool and development server)
- LocalStorage API (Cart, favorites, and theme state persistence)

## Getting Started

Follow these instructions to set up the project locally:

Clone the repository:
git clone https://github.com/Eksonurit/phone-catalog.git
cd phone-catalog

Install dependencies:
npm install

Run the project locally:
npm start

Build for production:
npm run build

## Features

- Dynamic Catalog and Filtering: Filter products by category, sort by price, year, or discount, and paginate results with full URL query persistence.
- Debounced Search Engine: Search input with integrated debounce (~300ms) that dynamically updates URL search parameters and renders dedicated empty states when no items match.
- State Persistence: Cart items, favorite products, and theme preference are synchronized with LocalStorage across browser sessions.
- Theme Management: Seamless switching between light and dark modes powered by Context API and CSS custom properties.
- Skeleton Loading and Micro-Interactions: Polished UI states using animated skeletons during asynchronous data fetching, smooth card lift effects, bounce animations on action buttons, and automated scroll-to-top navigation.
- Zero-Lag Performance: Centralized product context caching that prevents duplicate network calls and manages data flow cleanly across views.
