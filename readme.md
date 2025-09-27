# Ecommerce Website

A simple Ecommerce website backend implemented in Python.

## Features
- User authentication and registration
- Product listing and management
- Shopping cart functionality
- Order processing
- Utility functions for common tasks

## Project Structure
```
Ecommerce-website/
├── __init__.py
├── forms.py
├── settings.py
├── urls.py
├── utils.py
├── views.py
├── wsgi.py
├── __pycache__/
└── readme.md
```

## Getting Started

### Prerequisites
- Python 3.10 or higher
- pip (Python package manager)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Harshitagupta24/Ecommerce-website.git
   cd Ecommerce-website
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   *(Create a `requirements.txt` if not present, listing all dependencies)*

### Running the Application
1. Set up environment variables as needed (see `settings.py`).
2. Start the server:
   ```sh
   python wsgi.py
   ```

## File Descriptions
- `forms.py`: Contains form classes for user input and validation.
- `settings.py`: Configuration and settings for the project.
- `urls.py`: URL routing for the application.
- `utils.py`: Utility functions used across the project.
- `views.py`: View functions handling HTTP requests and responses.
- `wsgi.py`: Entry point for running the application with a WSGI server.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.
