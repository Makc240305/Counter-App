# React Counter Application

This project is a simple counter application built with React and styled using SCSS. It allows users to increment and decrement a counter value by interacting with buttons.

## Features

- **Increment and Decrement**: Users can increase or decrease the counter value by clicking the respective buttons.
- **Dynamic Styling**: Buttons and counter display are styled dynamically with SCSS for a polished look.
- **Responsive Design**: The application is designed to fit various screen sizes.

## Technologies Used

- **React**: Frontend library for building the user interface.
- **SCSS**: CSS preprocessor for styling.
- **Vite**: Build tool for fast development and optimized builds.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Makc240305/Counter-App
   ```
2. Navigate to the project directory:
   ```bash
   cd Counter-App
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Build

To create an optimized production build, run:
```bash
npm run build
```
This will generate static files in the `dist` directory.

## Deployment

You can deploy this application to GitHub Pages, Vercel, or Netlify. For GitHub Pages:

1. Install `gh-pages`:
   ```bash
   npm install gh-pages --save-dev
   ```
2. Add the following scripts to your `package.json`:
   ```json
   "scripts": {
     "build": "vite build",
     "deploy": "gh-pages -d dist"
   }
   ```
3. Deploy the project:
   ```bash
   npm run deploy
   ```
4. Your application will be available at:
   ```
   https://Makc240305.github.io/Counter-App/
   ```

## SCSS Styling

The application is styled using SCSS. Key features include:

- Dynamic color adjustments for buttons.
- Responsive layout with Flexbox.

Example SCSS snippet:
```scss
button {
  &.plus {
    background-color: #2a9d8f;
    color: #fff;
    &:hover {
      transform: translateY(-2px);
    }
  }

  &.minus {
    background-color: #e63946;
    color: #fff;
    &:hover {
      transform: translateY(-2px);
    }
  }
}
```
