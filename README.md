# Flask-Blog

### Project Structure

#### **`static/`**
The `static/` folder contains all the static files required by the application, such as CSS stylesheets, JavaScript files, and images. In this project:
- **`form.css`**: Styles the forms used in the blog application.
- **`styles.css`**: Provides general styling for the blog's layout and design.

#### **`templates/`**
The `templates/` folder holds all the HTML files used for rendering web pages via Flask's templating engine, enabling dynamic content insertion. This folder includes:
- **`create.html`**: For creating new blog posts.
- **`edit.html`**: For editing existing posts.
- **`index.html`**: Displays the homepage with all blog posts.
- **`post.html`**: Used for viewing individual blog posts.

#### **`app.py`**
This is the main application file containing the core logic. It defines the routes, processes requests, and renders the appropriate responses for the application.

#### **Database-Related Files**
- **`database.db`**: The SQLite database file where blog posts and other data are stored.
- **`schema.sql`**: Defines the structure of the database, including the tables and fields used in the application.
- **`init_db.py`**: A script used to initialize the database, ensuring it adheres to the structure defined in `schema.sql`.

