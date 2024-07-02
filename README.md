# Google_login_using_codeigiter
Step-by-Step Guide
Install Composer:
Navigate to your CodeIgniter project directory and run the following command in the terminal:
bash
Copy code
composer requires google/apiclient:^2.10
Setup Google API Configuration:

Create a new project on the Google Developers Console.
Enable the Google+ API (or the required API for authentication).
Create OAuth 2.0 credentials and download the JSON file.
Save the JSON file in your CodeIgniter project, e.g., application/config/google_client_secret.json.
Configure CodeIgniter for Google Login:

Load the Google API Client Library in your controller.
Implement the login and callback methods.
