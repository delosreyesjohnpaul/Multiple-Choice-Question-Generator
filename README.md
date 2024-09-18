# Multiple-Choice Question Generator

This repository contains a Flask-based application for generating multiple-choice questions. The application allows users to upload text or manually input questions, and it automatically generates multiple-choice questions based on the provided content.

## Features

- **Upload Text or Type Questions**: Easily upload a text file or manually type in questions.
- **Automatic Question Generation**: The application uses natural language processing to generate multiple-choice questions automatically.
- **Flask-based Web Interface**: A user-friendly web interface built with Flask.
- **Customizable Options**: Customize the number of choices, difficulty level, and other parameters.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/delosreyesjohnpaul/Multiple-Choice-Question-Generator.git
    cd Multiple-Choice-Question-Generator
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask application:
    ```bash
    flask run
    ```

## Usage

1. Open your web browser and navigate to `http://127.0.0.1:5000`.
2. Upload a text file containing your content or manually type in your questions.
3. Configure the question generation settings as needed.
4. Generate and review your multiple-choice questions.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
