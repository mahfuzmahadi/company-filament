# Starline Project with Laravel and Filament

This is a Laravel-based project integrated with Filament, designed to manage and display dynamic content efficiently.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- PHP >= 8.1
- Composer
- Node.js and npm
- MySQL >= 8.0
- Laravel >= 10.x
- Filament PHP >= 3.x

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**
   ```bash
   git clone git@github.com:<username>/<repository>.git
   cd <repository>
   ```

2. **Install Dependencies**
   ```bash
   composer install
   npm install && npm run dev
   ```

3. **Set Up Environment**
   Copy `.env.example` to `.env`:
   ```bash
   cp .env.example .env
   ```
   Update database credentials and other necessary configurations in `.env`.

4. **Generate Application Key**
   ```bash
   php artisan key:generate
   ```

5. **Run Migrations and Seeders**
   ```bash
   php artisan migrate --seed
   ```

6. **Start the Development Server**
   ```bash
   php artisan serve
   ```

## Features

- Admin panel powered by Filament for managing resources.
- Dynamic content rendering in the frontend.
- Integration of rich text and media features.

## Usage

Access the admin panel at:
```
http://127.0.0.1:8000/1/login
```

Use the following credentials (or update them via a seeder or admin setup):
- **Email**: `admin@gmail.com`
- **Password**: `01913644880`
