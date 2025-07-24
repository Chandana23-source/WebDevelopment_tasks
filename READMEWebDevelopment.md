# Web Applications – Login Form & Multi-Platform Music Detector

This repository contains two web projects created using HTML, CSS, and JavaScript:

1. **Login Form** – A user authentication interface with form validation and success/error messaging.
2. **Music Link Detector** – A web app that identifies a song's platform and displays other available platforms to listen.

Task1:
## 1. Login Form

**File:** `login.html`

### Description:
This form allows users to create an account using a username, email address, and password. 
Once registered, users can log in using their credentials. If incorrect email or password is entered, a relevant error message is shown. 
Upon successful login, a confirmation alert is displayed.

### Features:
- Input validation for empty fields, email format, and password length
- Alerts for:
  - Empty or invalid fields
  - Incorrect Password or mail address
  - Incorrect login credentials
  - Successful login confirmation

### How to run:
Open `login.html` in any browser. Fill in details and click submit to test login flow and alerts.


Task2:
## 2. Multi-Platform Music Link Detector

**File:** `music.html`

### Description:
This application allows users to input a song link from various music platforms including Spotify, JioSaavn, YouTube, Gaana, or Wynk. 
The app detects the origin of the song link and displays where the song can also be heard. RapidAPI (different platforms)is used to fetch and match song data across supported platforms.

### Features:
- Detects the platform of the input link
- Displays availability on other platforms
- Suggests where the same track can be listened to

### How to run:
Open `music.html` in a browser. Enter a valid song link from any supported music platform. 
The application will show which platform the link belongs to and offer alternate streaming options.where you can listen

### Note:
Make sure your RapidAPI credentials are properly configured in your JavaScript code to enable platform detection and data fetching.

## How to Use

1. Clone the repository:
git clone https://github.com/your-username/WebDevelopment_tasks.git

2. Open `login.html` and `music.html` in a browser.

3. Test login functionality and music platform detection.

## Author

Developed by Chandana  
Focus: Simple front-end tools with practical interactivity and user-friendly design.
