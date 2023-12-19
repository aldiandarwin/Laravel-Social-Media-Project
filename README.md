# Laravel Social Media Project Readme

## Project Overview

This Laravel project aims to create a social media platform similar to Instagram, where users can share their thoughts and follow other users in real-time.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/aldiandarwin/Laravel-Social-Media-Project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-social-media-project
   ```

3. Install PHP dependencies using Composer:

   ```bash
   composer install
   ```

4. Install NPM dependencies:

   ```bash
   npm install
   ```

5. Create a copy of the `.env.example` file and rename it to `.env`. Update the database configuration and other necessary settings:

   ```bash
   cp .env.example .env
   ```

6. Generate an application key:

   ```bash
   php artisan key:generate
   ```

7. Migrate the database:

   ```bash
   php artisan migrate
   ```

8. Start the development server:

   ```bash
   php artisan serve
   ```

## Package.json Configuration

The `package.json` file contains scripts and dependencies for managing the frontend assets of the project. Here are some key scripts:

- **Development**: Build assets for development:

  ```bash
  npm run development
  ```

- **Watch**: Watch for changes and recompile:

  ```bash
  npm run watch
  ```

- **Hot Reload**: Enable hot module replacement for faster development:

  ```bash
  npm run hot
  ```

- **Production**: Build assets for production:

  ```bash
  npm run production
  ```

## Features

### 1. Post

Users can create and share posts containing their thoughts, images, or other content.

### 2. Timeline

The timeline displays a chronological feed of posts from the users a person is following, providing real-time updates.

### 3. Follow and Unfollow

Users can follow and unfollow other users, allowing them to customize their timeline based on the content they want to see.

### 4. Profile Dashboard

User profiles act as dashboards, showing key metrics such as the number of followers, following, and total posts.

## Tech Stack

- Laravel
- Tailwind CSS
- Alpine.js
- Axios
- Laravel Mix for asset compilation

## Dependencies

- **@tailwindcss/forms**: Tailwind CSS plugin for styling forms.
- **alpinejs**: A lightweight JavaScript framework for UI interactions.
- **autoprefixer**: PostCSS plugin to parse CSS and add vendor prefixes.
- **axios**: Promise-based HTTP client for making requests.
- **laravel-mix**: Asset compilation and build tool for Laravel applications.
- **lodash**: Utility library for common JavaScript operations.
- **postcss**: Tool for transforming styles with JS plugins.
- **postcss-import**: PostCSS plugin to inline `@import` statements.
- **tailwindcss**: Utility-first CSS framework for rapid UI development.

## Contributing

Feel free to contribute to the project by submitting issues or pull requests. Your feedback and improvements are highly appreciated!
