
# Setup and Test Instructions

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Eliolocin/CSSECDVNaturelle.git
   cd CSSECDVNaturelle
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Add .env environment variable with following content**
    ```dotenv
    MONGODB_URL = <insert here>
    ```

4. **Start the application**
   ```bash
   npm start
   ```

5. **Access the application**
   - Open your browser and navigate to `http://localhost:3000`

## Testing as Customer

1. **Press "Login" on the top-right corner**

2. **Input the following credentials**
```plaintext
gigiuchinaga@email.com
test1234
```

## Testing as Employee
1. **Navigate to `http://localhost:3000/employee`**

2. **Input the following credentials**
```plaintext
hatdog@gmail.com
hatdog1234
```

## Testing as Admin
1. **Navigate to `http://localhost:3000/admin`**

2. **Input the following credentials**
```plaintext
username
pass1234
```

# STSWENGNaturelle
STSWENG Web Application Project for client Naturelle Salon

## Description
This is a comprehensive salon management web application built for Naturelle Salon. The system allows customers to book salon services, enables employees to manage their assigned reservations, and provides administrators with complete control over the salon operations including employee management, service management, and reservation oversight.

The application features three distinct user roles:
- **Customers**: Can register accounts, browse services, make reservations, and manage their bookings
- **Employees**: Can view assigned reservations, update service statuses, and manage their personal settings
- **Administrators**: Have full access to employee management, service collection management, FAQ management, and system administration

## Tech Stack

### Backend
- **Node.js** with **Express.js** - Web application framework
- **MongoDB** with **Mongoose** - Database and ODM
- **Handlebars (HBS)** - Server-side templating engine
- **bcrypt** - Password hashing and authentication
- **express-session** with **connect-mongo** - Session management
- **dayjs** - Date/time manipulation

### Frontend
- **Bootstrap 5** - CSS framework for responsive design
- **jQuery** - JavaScript library for DOM manipulation
- **Font Awesome** - Icon library
- **Custom CSS/JavaScript** - Additional styling and functionality

### Testing
- **Jest** - Unit testing framework
- **Cypress** - End-to-end testing framework

### Development Tools
- **ESLint** - Code linting (if configured)
- **Git** - Version control