
# React Router Project

This project is a demonstration of routing between different components and pages using React Router. It includes components for forms, navigation, and route protection, along with several pages like `Home`, `Dashboard`, `Login`, and `Signup`.

## Project Structure

### Components

- **LoginForm.js**: Handles the login form.
- **SignupForm.js**: Manages the signup form.
- **Navbar.js**: Contains the navigation bar for navigating between different routes.
- **PrivateRoute.js**: A higher-order component that guards private routes, ensuring that only authenticated users can access them.
- **Template.js**: Acts as a layout component for wrapping other components or pages.

### Pages

- **Dashboard.js**: The dashboard page, accessible only after logging in.
- **Home.js**: The homepage of the application.
- **Login.js**: The page that contains the `LoginForm` component for user authentication.
- **Signup.js**: The page that contains the `SignupForm` component for new user registration.

## Installation

### Prerequisites

- **Node.js**: Ensure you have Node.js installed. You can download it from [here](https://nodejs.org/).

### Steps

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```
   
2. **Navigate to the project directory**:
   ```bash
   cd react-router-project
   ```
   
3. **Install dependencies**:
   ```bash
   npm install
   ```

## Running the Project

1. **Start the development server**:
   ```bash
   npm start
   ```

2. **Open your browser and navigate to**:
   ```
   http://localhost:3000
   ```

## Routing Setup

The project uses `react-router-dom` to manage the routing between different pages. Here's how the routing is configured:

- **Home Route (`/`)**: Renders the `Home` component.
- **Login Route (`/login`)**: Renders the `Login` component.
- **Signup Route (`/signup`)**: Renders the `Signup` component.
- **Dashboard Route (`/dashboard`)**: Renders the `Dashboard` component and is protected by `PrivateRoute`.

## Screenshots
![image](https://github.com/user-attachments/assets/ccf267a6-5e2a-4a71-b23c-180dce09ba11)

![image](https://github.com/user-attachments/assets/5ef3dda7-56e0-4fd4-ac69-c136b08619fd)

![image](https://github.com/user-attachments/assets/bc8061e8-35ea-4291-8cfd-62bc00239597)


