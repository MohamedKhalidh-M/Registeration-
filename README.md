User Registration Form

A simple and responsive User Registration Form built using HTML, CSS, and JavaScript. This project collects user details and sends them to a backend API for registration using the Fetch API, with proper success and error handling.

🚀 Features

User-friendly registration form

Responsive design

Client-side form handling

REST API integration using Fetch API

Displays success and error messages

Network error handling

🛠️ Technologies Used

HTML5

CSS3

JavaScript (ES6)

Fetch API

📁 Project Structure
.
├── index.html
├── styles.css
└── README.md

📄 How It Works

The user enters:

Username

Email

Password

On form submission:

JavaScript prevents the default form reload

Form data is converted into a JavaScript object

Data is sent to the backend API as JSON

Based on the server response:

A success message is displayed

Or an error message is shown

🔗 Backend API

The form sends a POST request to the following endpoint:

https://registratin-backend.onrender.com/api/register

Expected Request Body
{
  "username": "your_username",
  "email": "your_email@example.com",
  "password": "your_password"
}

Example Response
{
  "message": "User registered successfully"
}

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/your-repository-name.git


Open the project folder:

cd your-repository-name


Open index.html in your browser

No server setup is required for the frontend.

⚠️ Notes

Passwords should always be hashed on the backend

Ensure the backend API is running and accessible

Use HTTPS in production environments

🌱 Future Improvements

Add password confirmation

Add form validation messages

Improve UI/UX design

Add loading indicator

Add environment-based API URLs
