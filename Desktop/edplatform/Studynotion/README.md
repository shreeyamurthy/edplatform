## Study Notion EDTECH Platform

StudyNotion is a fully functional ed-tech learning platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack , which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

## StudyNotion aims to provide:
- A seamless and interactive learning experience for students, making education more accessible and engaging.
- A platform for instructors to showcase their expertise and connect with learners across the globe.

## Front-end
The front end of StudyNotion has all the necessary pages that an ed-tech platform should have. Some of these pages are:

**For Students:**
- **Homepage**: This page will have a brief introduction to the platform, as well as links to the course list and user details.
- **Course List**: This page will have a list of all the courses available on the platform, along with their descriptions and ratings.
- **Wishlist**: This page will display all the courses that a student has added to their wishlist.
- **Cart Checkout**: This page will allow the user to complete the course purchase.
- **Course Content**: This page will have the course content for a particular course, including videos, and other related material.
- **User Details**: This page will have details about the student's account, including their name, email, and other relevant information.
- **User Edit Details**: This page will allow the student to edit their account details.

**For Instructors:**
- **Dashboard**: This page will have an overview of the instructor's courses, as well as the ratings and feedback for each course.
- **Insights**: This page will have detailed insights into the instructor's courses, including the number of views, clicks, and other relevant metrics.
- **Course Management Pages**: These pages will allow the instructor to create, update, and delete courses, as well as manage the course content and pricing.
- **View and Edit Profile Details**: These pages will allow the instructor to view and edit their account details.

**For Admin**
- **Dashboard**: This page will have an overview of the platform's courses, instructors, and students.
- **Insights**: This page will have detailed insights into the platform's metrics, including the number of registered users, courses, and revenue.
- **Instructor Management**: This page will allow the admin to manage the platform's instructors, including their account details, courses, and ratings.
- **Other Relevant Pages**: The admin will also have access to other relevant pages, such as user management and course management pages.

## Back-end
The back end of StudyNotion provides a range of features and functionalities, including:

1. **User authentication and authorization**: Students and instructors can sign up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
2. **Course management**: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
3. **Payment Integration**: Students will purchase and enroll in courses by completing the checkout flow that is followed by Razorpay integration for payment handling.
4. **Cloud-based media management**: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
5. **Markdown formatting**: Course content in document format is stored in Markdown format, which allows for easier display and rendering on the front end.
   
**Back-end Frameworks, Libraries, and Tools**  
The back-end of StudyNotion uses various frameworks, libraries, and tools to ensure its functionality and performance, including:

- **Node.js**: Used as the primary framework for the back-end.
- **Express.js**: Used as a web application framework, providing a range of features and tools for building web applications.
- **MongoDB**: Used as the primary database, providing a flexible and scalable data storage solution.
- **JWT (JSON Web Tokens)**: Used for authentication and authorization, providing a secure and reliable way to manage user credentials.
- **Bcrypt**: Used for password hashing, adding an extra layer of security to user data.
- **Mongoose**: Used as an Object Data Modeling (ODM) library, providing a way to interact with MongoDB using JavaScript.

  **Data Models and Database Schema**  
  The back end of StudyNotion uses several data models and database schemas to manage data, including:

- **Student Schema**: Includes fields such as name, email, password, and course details for each student.
- **Instructor Schema**: Includes fields such as name, email, password, and course details for each instructor.
- **Course Schema**: Includes fields such as course name, description, instructor details, and media content.
## Database
The database for the platform is built using MongoDB, a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data. The database stores the course content, user data, and other relevant information related to the platform.

![image](https://github.com/LokeshKumar710/Study-Notion-EDTECH-platform/assets/139546242/f5ecd3c5-6ad1-4a3e-82ba-41057c2e15c4)

## Architecture Diagram
Below is a high-level diagram that illustrates the architecture of the StudyNotion EdTech platform:

![image](https://github.com/LokeshKumar710/Study-Notion-EDTECH-platform/assets/139546242/7178a1e0-78ca-48d9-9b25-99dd177eb72f)

## API Design
The StudyNotion platform's API is designed following the REST architectural style. The API is implemented using Node.js and Express.js. It uses JSON for data exchange and follows standard HTTP request methods such as GET, POST, PUT, and DELETE.

## Installation and Setup
This starter pack includes a basic setup for using Tailwind CSS with React. To start building your own components and styles, follow these steps:

1. Clone the repository to your local machine.

   ```sh
    git clone https://github.com/LokeshKumar710/Study-Notion-EDTECH-platform.git

2. Install the required packages.

     ```sh
      npm install
3. Start the development server.
    ```sh
    npm run dev

4. Open the project in your browser at http://localhost:3000 to view your project.

 
  
## Contributing

Contributions are welcome! If you have any suggestions or find any issues, please feel free to open an issue or a pull request.
