# Text-to-image

A modern web application that transforms text prompts into stunning images using AI, with user authentication, credit purchases, and engaging UI components built with React, Tailwind CSS, and Vite.
This project enables users to generate unique AI-driven images from text prompts in a seamless web app. Featuring authentication, credit-based usage, responsive design, and intuitive UI, it streamlines creative image generation for personal, artistic, and business needs.

# Features
-  Generate images from creative text prompts
-  User authentication (Login and Register)
-  Credit-based image generation system
-  Purchase credits through various plans
-  Responsive, attractive UI using Tailwind CSS and motion animations
-  Customer testimonials and step-by-step flow

# Installation
Clone the repository

git clone https://github.com/your-username/ai-image-generator.git

Navigate to the project directory
cd ai-image-generator

Install dependencies

npm install

Configure environment variables
Copy .env.example to .env and fill in your API endpoints, e.g.:

VITE_BACKENDURL=https://your-api-url.com/

Run the development server
npm run dev

# Usage

-  Generate Images: Enter a prompt and use available credits to generate unique images.
-  Purchase Credits: Buy additional credits to continue generating images.
-  Authentication: Create an account or log in to use the service and manage your credits.
-  Responsive Design: Use on both desktop and mobile devices.


# Project Structure
/components — UI and functional components: Navbar, Header, Steps, Testimonials, BuyCredit, Result
/context — Global state management with React Context API (for authentication and credits)
/assets — Icons and image assets (used by components)
main.jsx and vite.config.js — Entrypoint and configuration


# Technologies Used
React
Tailwind CSS
Vite
Axios
React Router
Framer Motion


# Contribution
Contributions are welcome! Open issues or pull requests for new features, bug fixes, or suggestions.


# License
MIT License. See LICENSE file for details.

# Acknowledgements
Thanks to all contributors and the open source community.
