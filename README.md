# Password Manager

This is a simple Password Manager application built using Python and Tkinter. It allows users to generate strong passwords, save them securely, and retrieve them when needed. The passwords are stored in a JSON file.

## Features

- **Generate Password:** Generate a strong password with a mix of letters, numbers, and symbols.
- **Save Password:** Save the website, email/username, and password to a JSON file.
- **Find Password:** Retrieve the saved password for a specific website.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/password-manager.git
    cd password-manager
    ```
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```sh
    python main.py
    ```
2. The application window will open. You can use the following functionalities:
    - **Generate Password:** Click the "Generate Password" button to create a strong password. The generated password will be copied to your clipboard.
    - **Save Password:** Enter the website, email/username, and password. Click the "Add" button to save the details to `data.json`.
    - **Find Password:** Enter the website name and click the "Search" button to retrieve the email/username and password for that website.

## Project Structure

- `main.py`: The main application script.
- `data.json`: The JSON file where the passwords are saved.
- `logo.png`: The logo displayed in the application.

## Dependencies

- `tkinter`: For the GUI.
- `pyperclip`: To copy the generated password to the clipboard.
- `json`: To handle JSON operations.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgments

Feel free to open an issue if you have any questions or suggestions. Enjoy managing your passwords securely!
