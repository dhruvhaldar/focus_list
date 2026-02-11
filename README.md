# Focus List

A simple, modern To-Do List application built with Python (Flask) and HTML/CSS. This project is designed as a beginner-friendly introduction to web development and CRUD operations.

## Features

- **Add Tasks**: Quickly add new tasks to your list.
- **Delete Tasks**: Remove tasks once they are completed.
- **Data Persistence**: Tasks are saved to a JSON file (`tasks.json`), so they survive server restarts.
- **Modern UI**: Clean, dark-mode interface designed with CSS3 and Flexbox.

## Project Structure

```
focus_list/
├── app.py              # Main Flask backend application
├── tasks.json          # Data storage (auto-generated)
├── requirements.txt    # Python dependencies
├── static/
│   └── style.css       # Custom CSS styling
└── templates/
    └── index.html      # HTML template
```

## Setup & Installation

1.  **Clone or Download** the repository.

2.  **Create a Virtual Environment**:
    It's recommended to use a virtual environment to manage dependencies.
    ```bash
    python3 -m venv venv
    ```

3.  **Activate the Virtual Environment**:
    - On Linux/macOS:
        ```bash
        source venv/bin/activate
        ```
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```

4.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

1.  Make sure your virtual environment is activated.

2.  Run the Flask app:
    ```bash
    python app.py
    ```

3.  Open your web browser and navigate to:
    `http://127.0.0.1:5000`

## Technologies Used

- **Python**: Backend logic
- **Flask**: Web framework
- **HTML5**: Structure
- **CSS3**: Styling
- **JSON**: Simple data storage
