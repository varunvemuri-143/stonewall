
# Stonewall Blog Platform

Stonewall is a web application that allows users to create, share, and explore blogs. It provides an intuitive interface for users to log in, upload their blogs, and read content from others. With a simple and interactive design, Stonewall serves as a platform for diverse thoughts and ideas.

## Features

- **User Authentication**: Secure login system to manage user sessions.
- **Blog Management**: Users can upload blogs, save drafts, and view content shared by others.
- **Interactive Interface**: Easy navigation and user-friendly design for seamless interaction.
- **Image Upload**: Supports image uploads for a richer blogging experience.
- **Template-Based Design**: Leveraging Django templates for dynamic and responsive pages.

## Project Structure

```
Stonewall/
│
├── Stonewall2/           # Main application directory
├── static/               # Static files (CSS, JS, images)
├── stonewall/            # Core Django project settings
├── templates/            # HTML templates for the web pages
├── uploads/              # Uploaded files (images, etc.)
├── Procfile              # For deployment on platforms like Heroku
├── README.md             # Project documentation
├── db.sqlite3            # SQLite database
├── manage.py             # Django project management script
└── requirements.txt      # Python dependencies
```

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite
- **Deployment**: Configured with Procfile for deployment on platforms like Heroku

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/stonewall.git
   cd stonewall
   ```

2. **Install Dependencies**:
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Migrations**:
   Set up the database:
   ```bash
   python manage.py migrate
   ```

4. **Start the Server**:
   Run the development server:
   ```bash
   python manage.py runserver
   ```

5. **Access the Application**:
   Open your web browser and visit:
   ```
   http://127.0.0.1:8000/
   ```

## Contribution

Feel free to contribute to Stonewall by submitting pull requests or reporting issues. Together, we can make this platform better!



---

Happy Blogging!
