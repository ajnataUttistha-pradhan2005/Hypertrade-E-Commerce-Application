# Full-Stack E-Commerce Web Application

This is a full-stack e-commerce web platform built with separate **vendor** and **customer** roles. It supports product management, order tracking, dynamic pricing, discounts, and real-time analytics, all wrapped in a responsive user interface.

## Features

* **User Roles**

  * Vendor and Customer authentication
  * Role-based access and dashboards

* **Product & Inventory Management**

  * Add, update, and remove products
  * Inventory tracking in real time
  * Dynamic pricing and discount support

* **Orders**

  * Order placement and tracking
  * Vendor-side order management

* **Reviews**

  * Customers can leave product reviews and ratings

* **Media Uploads**

  * Image uploads using **Multer**
  * Media storage handled via **Cloudinary**

* **Analytics**

  * Real-time sales and performance insights for vendors


## Tech Stack

* **Frontend:** React JS
* **Backend:** Node.js, Express
* **Database:** MongoDB
* **File Uploads:** Multer + Cloudinary
* **Authentication:** Role-based auth (JWT)

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/ajnataUttistha-pradhan2005/Hypertrade-E-Commerce-Application)
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure environment variables:

   * MongoDB connection string
   * Cloudinary credentials
   * Authentication secrets

4. Run the application:

   ```bash
   npm run dev
   ```

## Future Improvements

* Payment gateway integration
* Advanced analytics and reporting
* Wishlist and recommendation system

## License

This project is for learning and demonstration purposes.

---

