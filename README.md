# Jobby App

Jobby App is a job listing application similar to Naukri.com, where users can log in to search for jobs based on title, salary range, and employment type.

## Features
- **User Authentication**: Users can log in using a username and password.
- **Job Listings**: View a list of jobs with search and filter options.
- **Job Details Page**: Get detailed information about a specific job.
- **Search & Filters**: Filter jobs based on salary range and employment type.
- **Protected Routes**: Only authenticated users can access job listings and job details.
- **Persistent Login**: JWT token is stored in local storage to maintain user login state.

## Technologies Used
- **Frontend**: React.js, JavaScript, CSS, Bootstrap
- **Routing**: React Router
- **Authentication**: JWT Token, Local Storage
- **API Calls**: REST API, Fetch API

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/jobby-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd jobby-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```

## Login Information
- **Username**: rahul
- **Password**: rahul@2021

## API Endpoints
- **Login API**: `POST /login` - Authenticate user
- **Jobs API**: `GET /jobs?search=&employmentType=&salaryRange=` - Fetch jobs
- **Job Details API**: `GET /jobs/:id` - Fetch job details

## Authentication Flow
- Users enter credentials and submit the login form.
- The app sends a POST request to the login API.
- On success, a JWT token is stored in local storage.
- For protected routes, the app checks for a valid token before granting access.

## Future Improvements
- Implement user registration.
- Add pagination for job listings.
- Improve UI with animations and better styling.
- Integrate real-time notifications for job updates.
 
### Design Files

<details>
<summary>Login Route</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Login](https://assets.ccbp.in/frontend/content/react-js/jobby-app-login-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login](https://assets.ccbp.in/frontend/content/react-js/jobby-app-login-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login Failure](https://assets.ccbp.in/frontend/content/react-js/jobby-app-login-failure-lg-output.png)
</details>

<details>
<summary>Home Route</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Home](https://assets.ccbp.in/frontend/content/react-js/jobby-app-home-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Home](https://assets.ccbp.in/frontend/content/react-js/jobby-app-home-lg-output.png)
</details>

<details>
<summary>Jobs Route</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Jobs](https://assets.ccbp.in/frontend/content/react-js/jobby-app-jobs-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Jobs Success](https://assets.ccbp.in/frontend/content/react-js/jobby-app-jobs-success-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - No Jobs](https://assets.ccbp.in/frontend/content/react-js/jobby-app-no-jobs-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Profile Failure](https://assets.ccbp.in/frontend/content/react-js/jooby-app-profile-failure-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Jobs Failure](https://assets.ccbp.in/frontend/content/react-js/jobby-app-jobs-failure-lg-output-v0.png)
</details>

<details>
<summary>Job Item Details Route</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Job Details Success](https://assets.ccbp.in/frontend/content/react-js/jobby-app-job-details-success-sm-output-v0.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Job Details Failure](https://assets.ccbp.in/frontend/content/react-js/jobby-app-job-details-failure-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Job Details Success](https://assets.ccbp.in/frontend/content/react-js/jobby-app-job-details-success-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Job Details Failure](https://assets.ccbp.in/frontend/content/react-js/jobby-app-job-details-failure-lg-output.png)
</details>

<details>
<summary>Not Found Route</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Not Found](https://assets.ccbp.in/frontend/content/react-js/jobby-app-not-found-sm-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Not Found](https://assets.ccbp.in/frontend/content/react-js/jobby-app-not-found-lg-output-v0.png)
</details>
