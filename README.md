This file contains instructions for how to set up and run a project:

Installation & Setup

Clone the repository:
git clone https://github.com/yourusername/online-store-api.git  
cd online-store-api 

Install dependencies:

composer install  
Configure environment (.env file) and database.
Run migrations & seed data:

php artisan migrate --seed  
Start the server:
php artisan serve 

API Endpoints

GET /api/categories – Retrieve all categories
GET /api/categories/{id} – Retrieve a specific category
POST /api/categories – Create a new category (XML request)
PUT /api/categories/{id} – Update a category (XML request)
DELETE /api/categories/{id} – Delete a category

Testing

Run unit tests:
php artisan test  
Deployment
Configure production database

Run:

php artisan migrate --seed  
php artisan config:cache

This is how to set up and run project, Thank you!
