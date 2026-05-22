# Date and Clock App

A simple application that displays the current date and time.

## How to run locally

1. Clone this repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```

## How to build for production

1. Run the build command:
   ```bash
   npm run build
   ```
2. The production files will be in the `dist/` directory.

## Deploying to GitHub Pages

This app is configured to be deployed as a static site. The `vite.config.ts` has been set up with `base: './'` to ensure that assets are resolved correctly when hosted on GitHub Pages or other subdirectories.

1. Ensure you have built the app using `npm run build`.
2. Configure your GitHub repository to deploy the contents of the `dist/` folder.
