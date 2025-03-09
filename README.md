# Laravel Project Setup Guide

## Prerequisites
- [XAMPP](https://www.apachefriends.org/)
- [Composer](https://getcomposer.org/)
- [Git](https://git-scm.com/)

## Installation Steps

### 1. Clone the Repository
```bash
# Navigate to XAMPP's htdocs directory
cd C:\xampp\htdocs

# Clone the project
git clone https://github.com/ManishAmFour/Laravel-Project.git

# Enter project directory
cd Laravel-Project
```

### 2. Install Dependencies
```bash
# Install PHP dependencies via Composer
composer install
```

### 3. Environment Setup
```bash
# Create environment file
cp .env.example .env

# Generate application key
php artisan key:generate
```

### 4. Database Configuration
1. Launch XAMPP Control Panel
2. Start both **Apache** and **MySQL** services
3. Open your browser and navigate to [phpMyAdmin](http://localhost/phpmyadmin)
4. Create a new database named `laravel`

### 5. Access the Project
1. Ensure XAMPP services (Apache & MySQL) are running
2. Open your preferred web browser
3. Visit: [http://localhost/Laravel-Project/public](http://localhost/Laravel-Project/public)

## Troubleshooting
- If you encounter any issues, ensure all services in XAMPP are running
- Check if the database name matches the one in your `.env` file
- Make sure all prerequisites are properly installed

## Support
If you need help, please [open an issue](https://github.com/ManishAmFour/Laravel-Project/issues)
