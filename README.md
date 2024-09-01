# 📝 **Blog Application**

Welcome to the Blog Application! This Django-powered blog allows users to create, edit, and delete posts, as well as manage user accounts with login and registration functionalities.

## 🚀 **Features**

- **Post Management:** Create, view, edit, and delete blog posts.
- **User Authentication:** Register, log in, and manage user sessions.
- **Responsive Design:** Beautifully styled pages using a black, lime, pink, and purple color scheme.

## 🛠️ **Getting Started**

Follow these steps to set up and run the application:

### 1. **Clone the Repository**

```bash
git clone https://github.com/Jazaltron10/JangoBlog.git
cd JangoBlog
```

### 2. **Install Dependencies**

Ensure you have Python installed. Install the required packages using:

```bash
pip install django mysqlclient python-dotenv djangorestframework djangorestframework-simplejwt
```

### 3. **Apply Migrations**

Set up your database by applying migrations:

```bash
python manage.py migrate
```

### 4. **Create a Superuser**

Create an admin account to access the Django admin interface:

```bash
python manage.py createsuperuser
```

### 5. **Run the Development Server**

Start the Django development server:

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your web browser to see the application in action.

## 📜 **Templates Overview**

Here are the key templates in the application:

- **`list_posts.html`**: Displays a list of all blog posts with options to create a new post or log out.
- **`register.html`**: Allows users to register a new account.
- **`login.html`**: Provides a login form for existing users.
- **`create_post.html`**: Form for creating a new blog post.
- **`edit_post.html`**: Form for editing an existing blog post.
- **`delete_post.html`**: Confirmation page for deleting a blog post.

## 🎨 **Styling**

The application uses a stylish color scheme:

- **Primary Colors:** Black and Lime
- **Secondary Color:** Pink
- **Tertiary Color:** Purple

## 🧩 **Contributing**

If you wish to contribute to this project, please fork the repository and submit a pull request with your changes. Make sure to follow the coding standards and include tests for your contributions.

## 📧 **Contact**

For any questions or feedback, please reach out to [jazaltron.jan@gmail.com](mailto:jazaltron.jan@gmail.com).
