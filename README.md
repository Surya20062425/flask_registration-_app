Flask User Registration App
A simple Flask web application for user registration with a beautiful UI.
Project Structure
plain
flask_registration_app/
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
├── templates/
│   ├── register.html       # Registration form
│   └── confirmation.html   # Confirmation page
Setup & Run
Install dependencies:
bash
pip install -r requirements.txt
Run the application:
bash
python app.py
Open in browser:
Navigate to http://localhost:5000
Features
Beautiful, responsive registration form
Form validation (all fields required)
Animated confirmation page with submitted details
Gradient design with smooth animations
Mobile-friendly layout
Routes
Table
Route	Method	Description
/	GET	Display registration form
/register	POST	Handle form submission & show confirmation
