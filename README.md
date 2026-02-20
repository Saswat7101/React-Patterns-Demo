# React Patterns & Best Practices

A demonstration project showcasing common React patterns including Compound Components and Render Props.

## Overview

This project demonstrates modern React patterns used for building flexible and reusable components. It features an interactive accordion component for FAQs and a searchable list component for filtering items.

## React Patterns Demonstrated

### 1. Compound Components Pattern (Accordion)

The Accordion component uses the Compound Components pattern, which allows multiple related components to work together while maintaining individual flexibility.

**Components:**

- `Accordion` - Main wrapper component
- `Accordion.Item` - Individual accordion item container
- `Accordion.Title` - Clickable title/header
- `Accordion.Content` - Collapsible content area

### 2. Render Props Pattern (SearchableList)

The SearchableList component uses the Render Props pattern, which allows components to share code and logic by using a prop whose value is a function.

**Features:**

- Text search/filter functionality
- Custom render function for items via render prop
- Custom key function for item identification

## Project Structure

```
src/
├── App.jsx                    # Main app component
├── Place.jsx                  # Place card component
├── main.jsx                   # App entry point
├── index.css                  # Global styles
├── assets/                    # Image assets
│   ├── african-savanna.jpg
│   ├── amazon-river.jpg
│   ├── caribbean-beach.jpg
│   ├── desert-dunes.jpg
│   └── forest-waterfall.jpg
└── components/
    ├── Accordion/             # Compound Components pattern
    │   ├── Accordion.jsx
    │   ├── AccordionItem.jsx
    │   ├── AccordionTitle.jsx
    │   └── AccordionContent.jsx
    └── SearchanbleList/       # Render Props pattern
        └── SearchableList.jsx
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

```
bash
npm install
```

### Development

Start the development server:

```
bash
npm run dev
```

### Build

Create a production build:

```
bash
npm run build
```

### Preview Production Build

```
bash
npm run preview
```

## Technologies

- **React 19** - UI library
- **Vite** - Build tool and development server
- **ESLint** - Code linting

## License

MIT
