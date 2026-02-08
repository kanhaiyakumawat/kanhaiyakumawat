# Website Structure Documentation

## Overview
This document provides an overview of the website's structure and setup instructions for developers.

## Directory Structure
- **/src**: Contains all source files.
  - **/components**: Reusable UI components.
  - **/pages**: Contains page components for routing.
  - **/styles**: Global and component-specific stylesheets.
- **/public**: Public assets like images and fonts.
- **/config**: Configuration files and environment variables.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/kanhaiyakumawat/kanhaiyakumawat.git
   ```
2. Navigate into the project directory:
   ```bash
   cd kanhaiyakumawat
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and go to `http://localhost:3000` to view the website.

## Additional Notes
- Ensure you have Node.js and npm installed before running the project.
- For production build, use `npm run build`.