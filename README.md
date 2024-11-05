# StudyNotion - EdTech Platform
StudyNotion is a fully functional EdTech platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

![img-1](https://github.com/user-attachments/assets/5501613e-8d72-4c70-98c2-dd82b4c9c953)
## Introduction
StudyNotion aims to provide a seamless and interactive learning experience for students, making education more accessible and engaging. Additionally, the platform serves as a platform for instructors to showcase their expertise and connect with learners across the globe.
In the following sections, we will cover the technical details of the platform, including the system architecture, API design, installation, usage instructions, and potential future enhancements.

## System Architecture
The StudyNotion EdTech platform consists of three main components: the front-end, the back-end, and the database. The platform follows a client-server architecture, with the front-end serving as the client and the back-end and database serving as the server.

### Front-end
The front-end of the platform is built using ReactJS, which allows for the creation of dynamic and responsive user interfaces, crucial for providing an engaging learning experience to students. The front-end communicates with the back-end using RESTful API calls.

#### Front-end Pages 
For Students: 
* Homepage: A brief introduction to the platform with links to the course list and 
  user details.
* Course List: A list of all the courses available on the platform, along with their 
  descriptions and ratings.
* Wishlist: Displays all the courses that a student has added to their wishlist.
* Cart Checkout: Allows the user to complete course purchases.
* Course Content: Presents the course content for a particular course, including 
  videos and related material.
* User Details: Provides details about the student's account, including their name, 
  email, and other relevant information.
* User Edit Details: Allows students to edit their account details.
  
For Instructors:
* Dashboard: Offers an overview of the instructor's courses, along with ratings and 
  feedback for each course.
* Insights: Provides detailed insights into the instructor's courses, including the 
  number of views, clicks, and other relevant metrics.
* Course Management Pages: Enables instructors to create, update, and delete 
  courses, as well as manage course content and pricing.
* View and Edit Profile Details: Allows instructors to view and edit their account 
  details.

  #### Front-end Tools and Libraries
  To build the front-end, we use frameworks and libraries such as ReactJS, CSS, and 
  Tailwind for styling, and Redux for state management.

  ## Backend
  The back-end of the platform is built using NodeJS and ExpressJS, providing APIs 
  for the front-end to consume. These APIs include functionalities such as user 
  authentication, course creation, and course consumption. The back-end also handles 
  the logic for processing and storing the course content and user data.

  #### Backend Features
  * User Authentication and Authorization: Students and instructors can sign up and 
    log in to the platform using their email addresses and passwords. The platform 
    also supports OTP (One-Time Password) verification and forgot password 
    functionality for added security.
  * Course Management: Instructors can create, read, update, and delete courses, as 
    well as manage course content and media. Students can view and rate courses.
  * Payment Integration: Students will purchase and enroll in courses by completing 
    the checkout flow, followed by Razorpay integration for payment handling.
  * Cloud-based Media Management: StudyNotion uses Cloudinary, a cloud-based media 
    management service, to store and manage all media content, including images, 
    videos, and documents.

 #### Back-end Tools and Libraries
  To build the Back-end, we use frameworks and libraries such as Node.js, 
  Express.js and MongoDB for database, JWT for authentication, Bcrypt for password s 
  security and Mongoose for Object Data Modeling.

  ## Database
  The database for the platform is built using MongoDB, a NoSQL database that 
  provides a flexible and scalable data storage solution. MongoDB allows for the 
  storage of unstructured and semi-structured data. The database stores the course 
  content, user data, and other relevant information related to the platform.

  
  ![db1](https://github.com/user-attachments/assets/f94ae6d4-6a5f-4587-be83-3cc936f1a531)

  ## Installation
  1. Clone the repository: git clone https://github.com/username/repo.git
  2. Navigate to the project directory: cd StudyNotion
  3. Install dependencies: npm install
 
## Feel free to contribute to the project and make it even better!

