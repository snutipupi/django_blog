# Django Blog Application

A modern, feature-rich blog application built with Django 5.0 and Bootstrap 5. This application provides a clean, responsive interface for creating and managing blog posts with user authentication and commenting system.

## Features

### User Management
- User registration with email support
- Secure login/logout functionality
- User-specific content management
- Admin interface for site management

### Blog Functionality
- Create, read, update, and delete blog posts
- Rich text content support
- Image upload capability for posts
- Comment system on posts
- Pagination for blog posts
- Mobile-responsive design

### UI/UX Features
- Modern Bootstrap 5 design
- Responsive navigation
- User-friendly forms
- Flash messages for user feedback
- Clean and intuitive interface
- Font Awesome icons integration

## Technology Stack

- **Backend**: Django 5.0
- **Frontend**: Bootstrap 5, Font Awesome
- **Database**: SQLite (default)
- **Image Handling**: Pillow
- **Environment**: python-dotenv

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd django_blog
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate virtual environment:
- Windows:
```bash
venv\Scripts\activate
```
- Unix or MacOS:
```bash
source venv/bin/activate
```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Run migrations:
```bash
python manage.py migrate
```

6. Create superuser (admin account):
```bash
python manage.py createsuperuser
```

7. Run development server:
```bash
python manage.py runserver
```

## Usage

1. Visit http://127.0.0.1:8000/ to access the blog
2. Register a new account or login with existing credentials
3. Create, edit, or delete your posts
4. Comment on posts
5. Access admin interface at http://127.0.0.1:8000/admin

## Project Structure

```
django_blog/
├── blog_project/        # Project settings and main URLs
├── blogapp/            # Main application
│   ├── migrations/     # Database migrations
│   ├── templates/     # HTML templates
│   ├── admin.py      # Admin interface configuration
│   ├── forms.py      # Form definitions
│   ├── models.py     # Database models
│   ├── urls.py       # URL routing
│   └── views.py      # View logic
├── static/           # Static files (CSS, JS, images)
├── media/           # User-uploaded files
├── requirements.txt  # Project dependencies
└── manage.py        # Django management script
```

## Features in Detail

### Post Management
- Create new posts with title, content, and optional image
- Edit existing posts
- Delete posts with confirmation
- View post details with comments
- Pagination for post lists

### User Authentication
- User registration with email
- Login/logout functionality
- Password validation
- User-specific post management
- Protected routes for authenticated users

### Comments System
- Add comments to posts
- View all comments on a post
- Comment author tracking
- Timestamp for comments

### Admin Interface
- Manage users, posts, and comments
- Monitor user activity
- Content moderation
- User management

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is open-source and available under the MIT License.

## Contact

For any queries or support, please open an issue in the repository.
