# Basic-E-commerce-Extended - Product Listing API

## Overview
Basic-E-commerce-Extended is an eCommerce platform expanding from fitness products to mobile phones. This API enables product listing, sorting, and filtering functionalities.

## Live Demo & Resources
 <div>
    <a href="https://www.loom.com/share/5ba47010b9ae48fbb199bb5018297270">
      <p>Basic-E-commerce-Extended - Product Listing  - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/5ba47010b9ae48fbb199bb5018297270">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/5ba47010b9ae48fbb199bb5018297270-96fca3390b7bc95a-full-play.gif">
    </a>
  </div>
  
- **StackBlitz URL:** 
   [StackBlitz](https://stackblitz.com/edit/stackblitz-starters-grocl4?file=index.js)
- **Deployed URL:** [Basic-E-commerce-Extended](https://basic-e-commerce-extended-akshay.vercel.app/)
  
## Setup & Deployment
1. Clone the repository:
   ```sh
   git clone https://github.com/AkshAI-2030/Basic-E-commerce-Extended.git
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   node index.js
   
   ```

## API Endpoints
### Product Sorting
- **By Popularity:** `/products/sort/popularity`
- **By Price (High to Low):** `/products/sort/price-high-to-low`
- **By Price (Low to High):** `/products/sort/price-low-to-high`

### Product Filtering
- **By RAM:** `/products/filter/ram?ram=8`
- **By ROM:** `/products/filter/rom?rom=64`
- **By Brand:** `/products/filter/brand?brand=apple`
- **By OS:** `/products/filter/os?os=Android`
- **By Price:** `/products/filter/price?price=30000`

### Retrieve All Products
- **Endpoint:** `/products`
- Returns the original product list.

## Integration with Basic-E-commerce-Extended UI
1. Deploy the backend API to Vercel.
2. Copy the deployment URL.
3. Open [Basic-E-commerce-Extended Frontend](https://bd2-listing-page.vercel.app/).
4. Paste the backend URL in the **Server URL** field and save.

## Features
- Sort products by popularity and price.
- Filter products based on RAM, ROM, brand, OS, and price.
- Seamless integration with Basic-E-commerce-Extended’s frontend.

### Notes
- Ensure `cors` is imported before API endpoints:
  ```javascript
  let cors = require('cors');
  app.use(cors());
  ```
## Conclusion
This API provides efficient sorting and filtering for Basic-E-commerce-Extended's product listings, enabling a seamless e-commerce experience.

