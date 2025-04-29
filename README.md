
Built by https://www.blackbox.ai

---

```markdown
# Online Scoreboard

## Project Overview
The **Online Scoreboard** is a web application designed to manage and display scores for different teams in real time. Users can increase or decrease team scores, and an admin login system ensures secure access to the main scoreboard.

## Installation
To run the Online Scoreboard locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd online-scoreboard
   ```
3. Open the `index.html` file in your preferred web browser.

*Note: No additional setup or installations are necessary as this is a static HTML/CSS/JavaScript project.*

## Usage
1. **Admin Login**: Navigate to `admin.html` to log in using the credentials:
   - Username: `WEIWEI`
   - Password: `GMIS2025SCOREBOARD`
   
2. Upon successful login, you'll be redirected to the **Online Scoreboard** where you can manage scores:
   - Click the "+" or "-" buttons to increase or decrease the scores of each team.
   - Press the "Publish Scores" button to view the current scores in an alert.

## Features
- Real-time score updating for multiple teams.
- Secure admin login functionality.
- User-friendly interface with responsive design.
- Score publishing functionality with alert confirmation.

## Dependencies
This project uses the following external libraries:
- **Tailwind CSS** for styling; imported via CDN.
- **Font Awesome** for icons; imported via CDN.

## Project Structure
The project consists of the following files:
```
/online-scoreboard
│
├── index.html        # Main scoreboard interface for users
└── admin.html        # Admin login form to access the scoreboard
```

## License
This project is licensed under the MIT License.
```