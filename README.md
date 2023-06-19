

# Flask Blog Application

This is a Flask-based blog application that allows users to create, edit, and delete blog posts, leave comments, and view user profiles.

## Prerequisites

- Python 3.x
- Flask
- Flask-CKEditor
- Flask-Bootstrap
- Flask-Login
- Flask-Gravatar

## Installation

1. Clone the repository:

git clone https://github.com/MichaelOgunjimi/mike-blog.git



2. Navigate to the project directory:

cd flask-blog

arduino


3. (Optional) Create a virtual environment:

python3 -m venv venv
source venv/bin/activate



4. Install the required dependencies:

pip install -r requirements.txt


5. Set up the database:

flask db init
flask db migrate
flask db upgrade


6. Set the Flask app environment variable:

export FLASK_APP=app.py

7. Start the Flask development server:

flask run



## Configuration

The following configuration options can be modified in the `app.py` file:

- `SECRET_KEY`: The secret key used for session encryption.
- `SQLALCHEMY_DATABASE_URI`: The URI for the SQLite database.
- `SQLALCHEMY_TRACK_MODIFICATIONS`: Whether to track modifications to database objects.

## Usage

1. Register a new account or log in with an existing account.
2. Navigate to the homepage to view all blog posts.
3. Click on a blog post to view its details and leave comments.
4. As an admin, you can create, edit, and delete blog posts.
5. Visit your user profile to view and edit your profile information.

## Known Issues

- None at the moment.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

For any questions or inquiries, please contact me at your-email@example.com.

