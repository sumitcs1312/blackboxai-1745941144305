
Built by https://www.blackbox.ai

---

```markdown
# Course Tracker

## Project Overview

Course Tracker is a web application designed to help users manage and track their courses. With a user-friendly interface, users can log in, view their enrolled courses, mark them as completed, and add new courses. The application utilizes local storage for data persistence and can be installed as a Progressive Web Application (PWA).

## Installation

To run the Course Tracker locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd course-tracker
   ```

2. **Open `index.html` in a web browser:**
   Simply double-click the `index.html` file, or open it using a web server for best practice.

## Usage

1. **Login**
   - Enter your username and password. Use the default credentials:
     - Username: `user1`, Password: `password1`
     - Username: `user2`, Password: `password2`
   
2. **View/Edit Courses**
   - After logging in, the "My Courses" section will display your courses.
   - You can edit the status of each course (mark as completed or in progress).
   - Remove or add new courses through the respective form fields.

3. **Logout**
   - Click the "Logout" button to exit your session.

## Features

- User authentication (login/logout)
- Manage courses (add, complete, or edit)
- Beautifully styled using Tailwind CSS
- Progressive Web Application (PWA) capabilities
- Offline support with service worker caching
- Data persistence using local storage

## Dependencies

This project does not require additional dependencies beyond the following external libraries:

- **Tailwind CSS** - For styling, included via CDN.
- **Font Awesome** - For icons, included via CDN.

**Note:** No local package management is required as the project does not utilize a `package.json` file.

## Project Structure

```
course-tracker/
├── index.html           # Main HTML file for the application
├── manifest.json        # Configuration file for PWA
├── service-worker.js    # Service worker for caching and offline capabilities
```

### index.html
The main file that contains the layout and functionality of the Course Tracker application. It includes forms for login and course management.

### manifest.json
Defines the settings for the Progressive Web Application, such as name, theme color, and icons.

### service-worker.js
Handles caching strategies to enable offline availability and improve loading performance.

## Conclusion

Course Tracker provides a streamlined solution for tracking course progress in a simple, accessible format. Users can easily manage their study materials and keep abreast of course completion status. Enjoy tracking your courses!
```