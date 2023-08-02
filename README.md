# Flask Notes App

This is a simple web application built with Flask that allows users to create and manage notes.

**⚠️ WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead. ⚠️**

## Features

- Users can create, view, and delete their notes.
- User authentication using email and password.

## Setup

1. Clone the repository by running the following command in your terminal or command prompt:
   ```bash
   git clone https://github.com/your-username/flask-notes-app.git
Replace `your-username` with your GitHub username and `flask-notes-app` with the name of your repository.
2. Create a virtual environment to isolate project dependencies (optional but recommended).
   - On Windows:
     ```
     python -m venv venv
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```
     python3 -m venv venv
     source venv/bin/activate
     ```
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Create the database by running `python main.py`.
5. Run the Flask development server with `python main.py`.

## Usage

1. Navigate to `http://localhost:5000/login` to access the login page.
2. If you don't have an account, click on "Sign Up" to create a new account.
3. Log in using your email and password.
4. On the home page, you can view your existing notes or add new ones.
5. To delete a note, click on the close button (X) next to the note.

## Screenshots

(optional) Add some screenshots of your application in action.

## Contributing

If you find any issues or want to contribute to the project, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Future Plans

- Implement a search functionality for notes.
- Add support for organizing notes into categories.
- ...
