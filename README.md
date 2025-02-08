Marketplace Web Application
Overview
This is a marketplace web application where users can browse through products, filter them by different categories, view product details, and add items to their cart. It's built with Next.js and Sanity CMS, making it easy to manage the content.

Key Features
Product Listings: Shows a list of products with their images, prices, and details.
Product Detail Pages: Click on products for more information on each item.
Search and Filters: Search for products and filter them by category, price, or discount.
Shopping Cart: Add products to the cart and proceed to checkout.
Responsive Design: The site is mobile-friendly and adjusts to different screen sizes.

Technologies Used
Frontend: React, Next.js, Tailwind CSS
Backend: Sanity CMS for content management
Other Libraries: SweetAlert2 for pop-up notifications, React Spinners for loading effects, Lodash for debouncing search input
Testing: React Testing Library for component testing

How to Set It Up
Clone the repository:
git clone <repository-url>

Install dependencies:
npm install

Set up environment variables: Create a .env.local file and add the following:
NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
NEXT_PUBLIC_SANITY_DATASET=your_dataset

Start the development server:
npm run dev
You can now visit http://localhost:3000 to see the project in action.

Testing
Test the key features like product search, filtering, and cart functionality.
For performance testing, use tools like Lighthouse to ensure the app loads quickly.
How to Deploy
You can deploy this project to platforms like Vercel or Netlify. During deployment, make sure to connect it to your Sanity dataset.

License
This project is under the MIT License.
