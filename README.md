# Modern Student Portal

A lightweight, single-file student portal built with HTML, CSS, and JavaScript. This application provides a clean, modern interface for students to access their courses and assignments.

![Student Portal Screenshot](https://placeholder-image.com/student-portal-screenshot.png)

## Features

- **Simple Authentication** - Login screen with username and password
- **Responsive Dashboard** - Works seamlessly on desktop and mobile devices
- **Course Management** - View all enrolled courses
- **Assignment Tracking** - Monitor pending and submitted assignments with due dates
- **Modern UI** - Clean design with cards, shadows, and interactive elements

## Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required

### Installation

1. Clone the repository or download the HTML file
   ```
   git clone https://github.com/yourusername/student-portal.git
   ```
   
2. Open the `index.html` file in your web browser

That's it! No build process, no dependencies to install.

## Usage

1. Open the application in your browser
2. Enter any username and password to log in (demo mode)
3. Explore the dashboard with sample student data
4. Use the "Logout" button to return to the login screen

## Demo Credentials

- **Username:** student123
- **Password:** any password will work in demo mode

## Customization

### Changing the Color Scheme

The application uses CSS variables for easy customization. Edit the following variables in the `<style>` section:

```css
:root {
  --primary: #4361ee;   /* Main brand color */
  --dark: #2b2d42;      /* Text and dark elements */
  --light: #f8f9fa;     /* Background color */
  --accent: #ef476f;    /* Accent elements like badges */
}
```

### Adding Real Data

In a production environment, modify the `userData` object in the JavaScript section to connect to your backend:

```javascript
// Replace this with API calls to your backend
const userData = {
  username: 'student123',
  name: 'Alex Johnson',
  courses: ['Mathematics', 'Physics', 'Computer Science'],
  assignments: [
    { title: 'Math HW 3', due: '2025-03-10', status: 'Pending' }, 
    { title: 'Physics Lab', due: '2025-03-15', status: 'Submitted' }
  ]
};
```

## Technical Details

- **Total Size:** Under 100 lines of code (excluding whitespace)
- **No External Dependencies:** Everything is contained in a single HTML file
- **Modern JavaScript:** Uses ES6+ features for clean code

## Future Enhancements

- Add local storage for persistent sessions
- Implement form validation
- Add grade reports section
- Create announcement board
- Integrate calendar for scheduling

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Design inspired by modern dashboard UIs
- Created for educational purposes

---

*Last updated: March 7, 2025*

---

## Copyright

All Rights Reserved @Yeswanth Soma

## Contact

Email:
