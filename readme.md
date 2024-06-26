# Music Application with Django REST Framework

This is a music application built using Django REST Framework with SQLite3 as the backend database. The frontend is developed using HTML, CSS, JavaScript, and Bootstrap framework.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely.
- **Browse Music**: Users can browse through a collection of songs.

## Technologies Used

- **Backend**:
  - Django: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
  - Django REST Framework: A powerful and flexible toolkit for building Web APIs in Django.
  - SQLite3: A lightweight, serverless database engine.
  
- **Frontend**:
  - HTML: The standard markup language for creating web pages.
  - CSS: The language used for styling the HTML elements.
  - JavaScript: A programming language that enables dynamic interactions on web pages.
  - Bootstrap: A popular CSS framework for building responsive and mobile-first websites.
  
## Installation

1. Clone the repository:
    ```
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```
    cd music_application
    ```

3. Install Python dependencies:
    ```
    pip install -r requirements.txt
    ```

4. Apply database migrations:
    ```
    python manage.py migrate
    ```

5. Run the development server:
    ```
    python manage.py runserver
    ```

6. Access the application at `http://localhost:8000` in your web browser.

## Usage

- **User Authentication**:
  - Visit `/signup` to create a new account.
  - Visit `/login` to log in to your account.
  - Visit `/logout` to log out of your account.
  
- **Browse Music**:
  - Visit `/music` to browse through the collection of songs.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).
