# College Application and Verification System

A comprehensive web-based platform designed to streamline the college application process and ensure document authenticity through automated verification.

## Project Overview

The College Application and Verification System is a modern solution for educational institutions to efficiently manage student applications and verify submitted documents. This system offers a user-friendly interface for prospective students to submit applications and upload mark sheets, while providing powerful tools for administrative decision-making.

## Key Features

- Online application submission with secure document upload
- Automated document verification using OCR technology
- Advanced data visualization and customizable dashboards
- Comprehensive report generation
- Real-time notifications for applicants and administrators
- Secure database management with role-based access control

## Technology Stack

- Frontend: React.js
- Backend: Node.js with Express.js
- Database: MongoDB
- OCR: Tesseract OCR (Python integration)
- Data Visualization: D3.js/Chart.js


## Benefits

- Increased administrative efficiency
- Enhanced accuracy in document verification
- Data-driven insights for admissions strategy
- Improved applicant experience
- Robust security and data protection

This project aims to revolutionize the college application process, providing a seamless experience for applicants while empowering institutions with powerful tools for application management and analysis.


##Project Setup Guide
Follow these steps to set up the project on your local machine:

# Setup Guide

Follow these steps to set up the project on your local machine:

## 1. Clone the Repository



```bash

First, clone the repository from GitHub:
git clone <repository-url>
Replace <repository-url> with the actual URL of your GitHub repository.
2. Unzip the Project Files (if applicable)
If you downloaded the ZIP file from GitHub, unzip it:
bashCopyunzip ai_nextgen-main.zip
Replace ai_nextgen-main.zip with the name of your ZIP file.
3. Navigate to the Project Directory
Move into the project directory:
bashCopycd ai_nextgen
4. Create a New React Project (if needed)
If the node_modules directory is missing or you prefer starting fresh, create a new React app (optional, if necessary):
bashCopynpx create-react-app ai_nextgen
Then, move the existing project files into this new React app folder.
5. Install Project Dependencies
Since the node_modules directory is not included in the repository, install all the required dependencies by running:
bashCopynpm install
This will install all dependencies listed in the package.json file.
6. Required Packages
The following dependencies will be installed:

@google-cloud/vertexai: ^1.4.0
@testing-library/jest-dom: ^5.17.0
@testing-library/react: ^13.4.0
@testing-library/user-event: ^13.5.0
axios: ^1.7.2
bcryptjs: ^2.4.3
bootstrap: ^5.3.3
concurrently: ^8.2.2
gridfs-stream: ^1.1.1
js-cookie: ^3.0.5
jsonwebtoken: ^9.0.2
mongoose: ^8.4.4
multer: ^1.4.5-lts.1
multer-gridfs-storage: ^5.0.2
react: ^18.3.1
react-dom: ^18.3.1
react-icons: ^5.2.1
react-router-dom: ^6.24.0
react-scripts: 5.0.1
recharts: ^2.12.7
web-vitals: ^2.1.4
xlsx: ^0.18.5

7. Run the Application
Once the dependencies are installed, start the React app using:
bashCopynpm start
If the project includes a backend, run it concurrently using:
bashCopynpm run both
8. Build the Project (Optional)
To create a production build, run:
bashCopynpm run build
This will create a build/ directory with the optimized production files.
9. Environment Variables (if applicable)
Ensure that you have all necessary environment variables set up in a .env file in the root directory. Check the code or documentation for the required variables.
10. Additional Notes

Ensure Node.js and npm are installed on your machine.
If any dependencies are missing, install them manually using npm install <package-name>.
