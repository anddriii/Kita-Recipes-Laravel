# Kita Recipes

Kita Recipes is a web platform designed for sharing and discovering food recipes. With Kita Recipes, users can search for their desired recipes and share their own recipes for others to explore and use. Each recipe includes detailed instructions, videos, and files to ensure clarity and ease of use.

## Features
- Recipe Search: Quickly find recipes based on your preferences.
- Comprehensive Recipe Details: Each recipe includes a video tutorial and supporting files for easy understanding.

# Installation Guide

## Prerequisites

- PHP (>= 8.0)
- Composer
- MySQL or PostgreSQL 
- Node.js & npm 

## Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/anddriii/Kita-Recipes-Laravel.git
cd kita-recipes-laravel
```

### 2. Install Dependencies
```bash
composer install
```

### 3. Copy and Configure Environment File
```bash
cp .env.example .env
```
Edit the `.env` file and update the database configuration:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

### 4. Generate Application Key
```bash
php artisan key:generate
```

### 5. Run Migrations and Seed Database
```bash
php artisan migrate --seed
```

### 6. Start the Development Server
```bash
php artisan serve
```

### 7. Install Dependencies & Build Assets
```bash
npm install
npm run dev
```

### Running Tests
```bash
php artisan test
```

