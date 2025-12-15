# LGU Student Portal

A web-based student portal for Lahore Garrison University (LGU) providing students with access to their academic information, attendance, courses, and fee details.

## Features

- **Dashboard**: Overview of enrolled semester, outstanding fees, CGPA, and class section
- **Attendance**: Track attendance across all courses
- **Courses**: View enrolled courses and instructors
- **Fee/Challan**: Access and print fee challans
- **Academic Calendar**: View important academic dates and events
- **Profile**: Student profile information

## Branding

The portal uses the official LGU logo located at `assets/lgu.png`. The logo appears in:
- Login page header
- Dashboard navbar (top navigation)
- Sidebar navigation
- Profile page

Logo specifications:
- Size: 148x148px
- Display height: 38px (automatically scaled with CSS)
- Format: JPEG (`.png` extension)

## Project Structure

```
.
├── index.html          # Main dashboard page
├── login.html          # Login page
├── styles.css          # Custom styles
├── app.js             # Application logic
├── data.js            # Sample data
└── assets/
    └── lgu.png        # LGU logo
```

## Usage

1. Open `login.html` in a web browser
2. Login credentials:
   - Roll Number: `fa-23-bscs-567` (format: fa-YY-program-XXX)
   - Password: `12345`
3. Navigate through the portal using the sidebar menu

## Technologies

- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5.3.2
- Font Awesome 6.5.0
- Chart.js 4.4.1

## License

© Copyright 2025 Develop By ERP Team.
