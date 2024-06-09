# Raily Landing Page

This project recreates the landing page of [Raily.app](https://raily.app) using PHP/Laravel framework.

## Setup and Run the Project

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/shuaibu78/raily-landing.git
cd raily-landing
```

### 2. Install Dependencies

Install the necessary dependencies for both PHP and Node.js:

```bash
composer install
npm install
```

### 3. Create and Configure .env File

Copy the example environment configuration file and generate an application key:

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Set Up the Database

Create a SQLite database file and run the migrations to set up the database schema:

```bash
touch database/database.sqlite
php artisan migrate
```

### 5. Run Vite for Asset Bundling

Ensure that Vite is set up correctly and run it:

```bash
npm run dev
```

### 6. Serve the Application

Start the Laravel development server:

```bash
php artisan serve
```

Your application should now be accessible at http://127.0.0.1:8000.

## Assumptions and Decisions

-   Database: Used SQLite for simplicity in local development.
-   Design: Added footer from the rail design

## Challenges

-   CSS Design: Matching the exact CSS design required detailed inspection.
-   Deployment: Deploying on Digital Ocean involved setting up the LAMP stack and configuring the environment.
