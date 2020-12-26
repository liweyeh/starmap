## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Design System & Styling
Design system is avalible in variable.scss. However, further Styling should be done in web component.

To view design system: 
https://www.figma.com/file/rKFcp1IojqLPAEb46K3zxT/Starmap-Colors?node-id=0%3A1

## Folder Structure
- /abstract
    This is for storing scss variables.
- /assets
    This is for storing images and text.
- /components
    This is for storing component, which is composed of JSX elements, simple third party elements, or one or two other components. Building blocks for the website.
- /constants
    This is for storing constants (endpoints, screen-size...etc).
- /pages
    This is for storing pages, which is composed of multiple widgets, JSX elements, or components. A place that everything is put together.
- /public
    This is just for favicon at the moment. 
- /store
    This is the central for state management
- /utils
    This is for storing util function if I don't end up using everything in Lodash
- /widgets
    This is for storing widgets, which is composed of JSX elements, components, or complex third party elements.