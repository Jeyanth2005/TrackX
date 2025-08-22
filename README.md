# TrackX: A Comprehensive Expense Tracking System

TrackX is a modern, full-stack web application designed to help individuals efficiently manage their personal finances. The system provides a centralized, secure, and user-friendly platform for tracking, categorizing, and analyzing daily expenses and incomes in real-time.

---

## Key Features

The application is built to address common challenges in personal finance management, such as a lack of real-time reporting, manual data entry, and fragmented systems. Its core functionalities include:

### Expense and Income Management
Users can easily input, categorize, and manage their financial transactions in real-time. The system allows for adding new expenses and incomes, which are then reflected in the total balance.

### Unified Platform
All financial tracking activities are consolidated into one cohesive platform, reducing the risk of errors and the need for redundant data entry.

### Data Visualization
The application provides detailed reports and data visualizations, such as charts, to help users analyze spending patterns and income trends.

### Transaction History
Users can view a list of all their transactions, with the ability to delete individual entries to keep their records up-to-date.

### Enhanced Security
The system uses JSON Web Tokens (JWT) for secure user authentication and session management. Financial data is securely stored in a cloud-based database with regular backups to ensure data integrity and prevent unauthorized access.

---

## Technologies Used

TrackX is built on a robust and scalable architecture, leveraging a modern technology stack to ensure a seamless and efficient user experience.

### Frontend
The user interface is developed with:
- **React** for component-based architecture
- **React Hooks** for state management
- **React Router** for navigation
- **Chart.js** for data visualization

### Backend
The server-side of the application is powered by:
- **Node.js** and **Express.js** for RESTful API endpoints handling authentication, expense and income management, and report generation

### Database
- **MongoDB** for managing and storing user data, including expenses, income records, and user profiles  
- **Mongoose** for data modeling and validation

### Deployment
- **Vercel** for frontend deployment, providing a serverless environment and global CDN  
- **Back4App** for backend deployment and MongoDB database management

---

## License
This project is licensed for personal and educational use. Check the repository for more details if a license file is provided.
