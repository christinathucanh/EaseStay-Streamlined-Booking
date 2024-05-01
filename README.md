# EaseStay-Streamlined-Booking

EaseStay is a full-stack booking application designed to provide users with a seamless and intuitive experience for booking accommodations. Built using the MERN stack (MongoDB, Express.js, React.js, Node.js), EasyStay offers features similar to popular platforms like Airbnb, enabling users to search, book, and manage their stays effortlessly.

## App Demo
<img width="718" alt="Screenshot 2024-05-01 at 12 38 44 AM" src="https://github.com/christinathucanh/EaseStay-Streamlined-Booking/assets/95081865/8e27c619-767e-42e9-ad0f-d94c6cf7010c">
<img width="806" alt="Screenshot 2024-05-01 at 12 36 55 AM" src="https://github.com/christinathucanh/EaseStay-Streamlined-Booking/assets/95081865/cd00bf1b-53e7-4244-9dc0-ca9f9213b53d">
<img width="794" alt="Screenshot 2024-05-01 at 12 36 15 AM" src="https://github.com/christinathucanh/EaseStay-Streamlined-Booking/assets/95081865/5906e7b3-b7f8-4f35-862b-e3e0f0bac621">


## Features

- **User Authentication**: Secure user authentication with JWT-based tokens ensures safe access to the platform, enhancing user privacy and data security.

- **Efficient Data Management**: MongoDB and Mongoose are utilized for efficient data storage and retrieval, resulting in optimized database query performance and reduced data retrieval times.

- **Streamlined Booking Process**: EasyStay offers a streamlined booking process, allowing users to search for accommodations based on their preferences, view detailed listings, and complete bookings seamlessly.

- **Responsive User Interface**: The frontend, built with React.js and Tailwind CSS, features a responsive and intuitive user interface, ensuring optimal user experience across various devices and screen sizes.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/stay-ease.git
cd stay-ease
npm install

```
2. Install dependencies:
```bash
cd stay-ease
npm install
```
3. Set up environment variables:
Create a .env file in the root directory and define the following variables:
```bash
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
S3_ACCESS_KEY=your_aws_s3_access_key
S3_SECRET_ACCESS_KEY=your_aws_s3_secret_access_key
```
4.Start the server:
```bash
npm start
```
5.Start the client:
```bash
cd client
npm start

