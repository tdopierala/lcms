# LCMS Aisle

LCMS Aisle is a Content Management System (CMS) application built using PHP with the Laravel framework. It provides a user-friendly interface for managing content, including articles, pages, categories, and more.

## Features

- **User Management:** Manage user accounts with roles and permissions.
- **Content Management:** Create, edit, and delete articles, pages, and categories.
- **Media Management:** Upload and manage media files such as images and videos.
- **Customizable Themes:** Choose from a variety of themes or create your own.
- **SEO-Friendly:** Easily optimize content for search engines with built-in SEO tools.
- **Localization:** Support for multiple languages.
- **Extensibility:** Extend functionality with plugins and modules.

## Requirements

- PHP >= 7.4
- Composer
- Node.js & NPM
- MySQL or SQLite

## Installation

1. Clone the repository: `git clone https://github.com/your-username/lcms-aisle.git`
2. Navigate to the project directory: `cd lcms-aisle`
3. Install PHP dependencies: `composer install`
4. Install NPM dependencies: `npm install`
5. Copy the `.env.example` file to `.env` and configure your environment variables.
6. Generate application key: `php artisan key:generate`
7. Run database migrations: `php artisan migrate`
8. Seed the database with sample data (optional): `php artisan db:seed`
9. Compile assets: `npm run dev` or `npm run production` for production
10. Serve the application: `php artisan serve`

## Usage

- Visit the application in your web browser.
- Log in with the default administrator account (username: admin@example.com, password: password).
- Start managing your content!

## Contributing

Contributions are welcome! Please follow the [contributing guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
