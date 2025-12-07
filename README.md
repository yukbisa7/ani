# Aikacungwen HTML

This project was created using the Aikacungwen HTML AI-powered web development environment.

## Project Structure

- `public/`: Contains the user-facing website.
  - `index.html`: The main landing page displaying a list of anime titles.
  - `pages/detail.html`: A template for displaying details of a specific anime title and its episodes.
  - `pages/episode.html`: A template for playing a specific episode of an anime.
  - `js/main.js`: Client-side JavaScript for fetching data and rendering content.
- `admin/`: Contains the administration panel for managing content.
  - `login.html`: New admin login page.
  - `index.html`: Admin dashboard with links to manage titles and episodes.
  - `create-title.html`: Form to add a new anime title.
  - `edit-title.html`: Form to edit an existing anime title.
  - `create-episode.html`: Form to add a new episode to a title.
  - `edit-episode.html`: Form to edit an existing episode.
  - `js/admin.js`: Client-side JavaScript for admin panel logic, including authentication.
  - `css/admin.css`: Specific styles for the admin panel.

## Data Source

This project uses a JSON-based data source for content, located at: `https://hosting.nakibo8225.workers.dev/json/b22b00540aee`.

**Note on Admin Authentication:**

The `admin/js/admin.js` now includes client-side authentication logic. For demonstration purposes, it simulates the presence of an admin user (`Aikacungwen` with password `Dragon123`) within the fetched data if no `users` array is present. This is purely for client-side functionality and is **not a secure way to manage user authentication in a production environment.** A real application would use a secure backend for user management, password hashing, and token-based authentication.

**Credentials for admin login (for testing purposes only):**
- **Username:** `Aikacungwen`
- **Password:** `Dragon123`