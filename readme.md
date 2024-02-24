# Simple Form Submission with Flask and OpenAI Integration

This project, developed by Team RamRod, is a Flask-based web application designed to gather information from users through a simple form, process it using OpenAI's API, and display a final landing page with congratulations and GIFs from Tenor and Giphy. It features two main components: 

## Key Features

1. **Information Gathering Form:** Users can submit personal details such as name, email, phone, school, and employment organization. Upon submission, the form data is sent to a Flask backend.

2. **AI-Driven Query Form:** This form allows users to submit queries that are processed by OpenAI's API, demonstrating the integration of AI within web applications.

The project showcases frontend HTML/CSS for user interface design, JavaScript for client-side logic including form submission handling and displaying loading animations, and Python Flask for server-side operations including routing, form handling, and integration with OpenAI and web scraping functionalities.

### Installation

1. Ensure Python 3 and Flask are installed on your system.
2. Clone this repository to your local machine.
3. Install required Python packages using `pip install -r requirements.txt`, where `requirements.txt` includes Flask, requests, BeautifulSoup4, and openai.

### Setting Up OpenAI API Key

- Obtain an API key from OpenAI.
- Store your API key in the `OPENAI_API_KEY.py` file or set it as an environment variable.

### Running the Application

1. Navigate to the project directory in your terminal.
2. Run the Flask application by executing `flask run`.
3. Access the web application by navigating to `http://127.0.0.1:5000/` in your web browser.

## Using the Application

- **Form Submission:**
  - Fill in the "Team RamRod Looking For Suspects" form with the requested information and submit.
  - You will see a loading animation while the form is processed.

- **AI-Driven Queries:**
  - Use the second form to input a query for the OpenAI API.
  - Submit the form to see the AI-generated response displayed on the page.

- **Final Landing Page:**
  - After interacting with the forms, you can navigate to the final landing page to view congratulatory messages and GIFs.

## Note

This application is designed for educational purposes and demonstrates basic integration with OpenAI and web technologies.

