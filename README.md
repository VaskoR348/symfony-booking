# Symfony Booking Application

A comprehensive booking management system built with Symfony 4.4.

## Features

- User authentication and registration
- Business owner management
- Listing creation and management
- Booking system with calendar integration
- Review and rating system
- Blog with comments and likes
- Wishlist functionality
- Real-time notifications
- Google OAuth integration
- Multi-city support with categories

## Requirements

- PHP >= 7.1.3
- Composer
- MySQL/MariaDB
- Symfony 4.4

## Installation

1. Clone the repository
2. Install dependencies:
   ```
   composer install
   ```
3. Configure your database in `.env`
4. Run migrations:
   ```
   php bin/console doctrine:migrations:migrate
   ```
5. Load seed data:
   ```
   php bin/console doctrine:seed
   ```
6. Start the development server:
   ```
   php bin/console server:run
   ```

## Project Structure

- `src/Controller/` - Application controllers
- `src/Entity/` - Doctrine entities
- `src/Repository/` - Database repositories
- `src/Form/` - Form types
- `templates/` - Twig templates
- `public/` - Public assets

## Key Entities

- **User**: Application users
- **Businessowner**: Business account management
- **Listing**: Service/venue listings
- **Booking**: Reservation management
- **Review**: User reviews and ratings
- **Blog**: Content management system
- **Category**: Listing categorization
- **City**: Location management

## License

Proprietary
