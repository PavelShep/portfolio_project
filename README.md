# Portfolio website with Admin Panel

## Project Description

This project is a dynamic portfolio website designed to showcase skills, projects, and professional experience. It features an **Admin Panel** that allows for seamless content management, enabling updates to the portfolio without modifying the code, includes a **Live Chat** feature for real-time communication with visitors, and also utilizes a simple **Google Translate** integration for language translation. 

### Screenshot
![Project Screenshot](https://raw.githubusercontent.com/PavelShep/PavelShep/main/uploads/portfolio_project.png)  
*Example of the portfolio's main page layout.*  

![Project Screenshot](https://raw.githubusercontent.com/PavelShep/PavelShep/main/uploads/portfolio_project_admin.png)  
*Example of the portfolio's Admin page.*  

---

## Features
- **About:** Brief introduction and professional background and overview of the technologies and tools I use.    
- **Portfolio:** A curated list of projects with descriptions, source code links, and live demos (if available).  
- **Contact:** Allows visitors to send me messages directly from the website.
  
---

## Technologies Used
### Frontend:
- **HTML**: For the structure of the site.  
- **CSS**: For styling and layout design.  
- **JavaScript**: For interactive functionality and animations.    

### Backend:
- **PHP**: Server-side logic.  

### Other:
- **AdminLTE**: A responsive admin dashboard template
- **Tawk.to**: A free live chat tool
- **Google Translate Widget**: Allows users to translate website content into different languages 
---

## Installation and Setup
To run the project locally, follow these steps:  

1. Clone the repository:
   ```bash
   git clone https://github.com/PavelShep/portfolio_project.git
2. Navigate to the project directory:
   ```bash
   cd portfolio_project
3. Set up the database:
   - Import the myportfolio.sql file.
   - Update the database connection settings in db.php to match your local database configuration
   - Signup / Login in [tawk.to](https://www.tawk.to/) and impliment Direct Chat Link to line 432 in index.php
4. Start the server and database (for example, by using Xammp)
5. Access the application:
   - Portfolio Website: http://localhost:3000/portfolio_project
   - Admin Panel: http://localhost:3000/portfolio_project/admin
