# rn-assignment4-11046896

markdown
Copy code
# Jobizz App

Jobizz is a job search application that allows users to browse and apply for various job positions. This README provides an overview of the application structure and functionality.

## Components

### LoginScreen

The `LoginScreen` component is responsible for user authentication. Users can input their name and email to log in. Upon successful login, users are navigated to the Home screen.

### HomeScreen

The `HomeScreen` component displays the main interface of the application after logging in. It consists of the following sections:

- **Header**: Displays the user's name, email, and a profile picture.
- **Search Bar**: Allows users to search for specific job positions.
- **Featured Jobs**: Shows a selection of featured job cards. Users can see all featured jobs or collapse the list.
- **Popular Jobs**: Displays popular job cards. Users can expand or collapse the list to view more jobs.

#### JobCard Component

The `JobCard` component is a functional component used to render individual job cards. It accepts props such as title, company, salary, location, and icon to display job details.

### Custom Components

Throughout the application, custom components like `JobCard` are used to ensure modularity and reusability of UI elements.

## Screenshots

Below are screenshots of the application to illustrate its appearance:

- **Login Screen**
  ![Login Screen](./myrnapp/assets/LoginPagescreenshot.jpg)

- **Home Screen**
  ![Home Screen](./myrnapp/assets/HomePagescreenshot.jpg)

## Usage

To run the application locally:

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies with `npm install` or `yarn install`.
4. Start the application with `npm start` or `yarn start`.

Make sure you have Node.js and a suitable development environment set up for React Native.

## Technologies Used

- React Native
- JavaScript
- Node.js
