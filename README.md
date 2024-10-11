# MyBlog

A minimalistic blogging platform built with **React** and **Next.js**, using a structured database with **XAMPP** for storing blog posts and user data. The platform provides full **CRUD** functionality and user authentication through **Google login**. The user interface is designed with **Tailwind CSS** for a clean and responsive experience.

## Features

- User Authentication via Google login
- Full CRUD operations for blog posts
- Responsive and clean UI built with Tailwind CSS
- Dynamic blog sections for new and trending posts
- Account management for user blogs and details
- Minimalistic grid-based design for easy navigation

## Technologies Used

- **React**
- **Next.js**
- **Tailwind CSS**
- **XAMPP (for the database)**
- **Google Cloud API (for login)**
- **Prisma (for database management)**

## Setup Instructions

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/myblog.git
    cd myblog
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up the database:**

   Ensure XAMPP is installed and running. Configure your database settings in the `.env` file (if applicable).

4. **Configure Google API for login:**

   Set up your Google Cloud account and obtain the necessary credentials. Place them in the `.env` file.

5. **Run the development server:**

    ```bash
    npm run dev
    ```

    Navigate to `http://localhost:3000` to view the app.

## Folder Structure

- `/pages`: Contains the routes and pages.
- `/components`: Reusable UI components.
- `/prisma`: Database schema and management files.
- `/styles`: Tailwind CSS configuration and styles.

## Contributing

Feel free to submit pull requests to improve features, fix bugs, or enhance documentation.



