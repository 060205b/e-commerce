# Project Registration System

## Overview
This project is a web-based application consisting of multiple pages designed for user registration, e-commerce functionalities, personal portfolio display, and a polling selection system.

## Project Structure

### 1. Base Page (base.html)
- **Features:**
  - This HTML file serves as the template for the Project Registration page, containing the layout and styling for user input.
 
### 2. Project Registration Page (index.html)
- **Features:**
  - A form for user input including fields for name, number, email, height, weight, blood group, age, gender, and qualification.
  - Functionality to submit the form data to a local server using a `fetch` request.
  - A reset button to clear the form inputs.

### 3. E-Commerce Page (e-commerce.html)
- **Features:**
  - Display of products with images, descriptions, and "Add to Cart" buttons.
  - A shopping cart that updates dynamically based on user interaction.

### 4. Portfolio Page (personal_portfolio.html)
- **Features:**
  - A page showcasing personal information, work experience, education, certifications, and skills.

### 5. Polling Selection Page (polling_selection.html)
- **Features:**
  - A polling system that allows users to vote for images of dogs or cats.
  - A form to collect demographic information from users.

### 6. Form Data (formdata.json)
- **Purpose:** 
  - This JSON file is used to store the submitted form data in a structured format.

### 7. Server File (server.js)
- **Purpose:** 
  - This JavaScript file sets up a local server using Express. It handles form submissions and saves the data to `formdata.json`.

## Installation
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the necessary dependencies by running:
   npm install express body-parser

Start the server by executing:
node server.js

Usage

Open the desired HTML page in your web browser to access its features.
Follow the instructions on each page for interacting with the forms and functionalities.
