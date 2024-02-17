# Job-Portal-MVC-Modal

This project implements an MVC (Model-View-Controller) architecture using ExpressJS to separate data handling, interface rendering, and routing control.

## Features Implemented:

- Implemented EJS for server-side templating, providing dynamic HTML generated based on server data.
- Utilized ES6 modules to maintain code modularity and organization.
- Used Express sessions for managing user sessions and cookies-based tracking of the last visit.
- Employed in-memory data structure for user and job management operations.
- Implemented a login and registration system, allowing recruiters to create and log into their accounts.
- Allowed job-seekers to view all jobs, view job details, and apply to a job by providing their details.
- Enabled recruiters to create, update, delete, and view job postings, with necessary validations for each field in the job postings.
- Enabled recruiters to view all applicants of a job, including their submitted resume file.
- Implemented an email system to send confirmation emails to applicants after they apply to a job.
- Used middleware for handling authentications, tracking of the last visit, file uploading, and sending confirmation emails.
- Stored the resume file on the server using file upload middleware.
- Ensured original and high-quality code with comprehensive documentation.

## Installation and Setup:

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/Job-Portal-MVC-Modal.git
   ```

2. Navigate to the project directory.
   ```bash
   cd Job-Portal-MVC-Modal
   ```

3. Install dependencies.
   ```bash
   npm install
   ```

4. Run the server.
   ```bash
   npm start
   ```

5. Open your web browser and go to `http://localhost:3000` to access the application.

## Reference Video:

[Click here to watch the reference video](https://www.youtube.com/watch?v=z_46m-Rkk28)

## Additional Notes:

- Make sure to configure your email settings in the project's configuration files to enable email functionalities.
- Customize the application further as per your requirements.

Feel free to explore and contribute to this project! If you encounter any issues or have suggestions for improvements, please open an issue or pull request on GitHub. Happy coding!
