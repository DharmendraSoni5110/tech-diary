# Tech Diary

**Tech Diary** is a full-stack web application built with Django, designed to help users document, share, and explore technology-related articles, tutorials, and experiences. Whether you're a software developer, data scientist, or tech enthusiast, Tech Diary is the perfect platform for sharing your knowledge and learning from others.
---

## Features

- **User Authentication**: Secure login and registration system, including password recovery.
- **Article Management**: Create, edit, and delete articles with rich text formatting, code snippets, and syntax highlighting.
- **Categories and Tags**: Organize articles by categories and tags for easy navigation.
- **Search Functionality**: Find articles based on keywords, tags, and categories.
- **User Profiles**: Users can manage their profiles and view their authored articles.
- **Comments**: Engage with articles through comments.
- **Likes and Bookmarks**: Users can like and bookmark articles.
- **Responsive Design**: Optimized for desktop and mobile devices.

---

## Tech Stack

- **Backend**: Django, Django REST Framework
- **Frontend**: HTML, CSS, JavaScript, Bootstrap 5
- **Database**: PostgreSQL
- **Authentication**: Django Authentication System (supports social logins via Google, GitHub, etc.)
- **Deployment**: Deployed on [Heroku](https://www.heroku.com/)

---

## Installation

### Prerequisites

Before running the app locally, make sure you have the following installed:

- Python 3.x
- PostgreSQL (or any other database)
- Git

### Steps to Set Up Locally

1. **Clone the repository**:

   ```
   git clone https://github.com/your-username/tech-diary.git
   cd tech-diary
   ```
Create a virtual environment:

python3 -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
Install backend dependencies:

pip install -r requirements.txt
Set up your database:

python manage.py migrate

python manage.py runserver

Access the application:

Open your browser and go to http://127.0.0.1:8000/.

Usage
Sign Up / Log In: Users can sign up using email, Google, or GitHub authentication.
Create an Article: After logging in, users can write and publish articles.
Search: Use the search bar to explore articles by keywords, categories, or tags.
Interact: Like, comment, and bookmark articles that interest you.
Contributing
We welcome contributions! If you'd like to contribute, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature-name).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push your changes to your fork (git push origin feature/your-feature-name).
Open a Pull Request.
Please make sure to follow the coding guidelines and write tests for new features.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
Your Name - Dharmendra Soni (Keshav)
Email - dharmendrasoni2005@gmail.com
