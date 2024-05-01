# EaseStay-Streamlined-Booking

StayEase is a full-stack booking application designed to provide users with a seamless and intuitive experience for booking accommodations. Built using the MERN stack (MongoDB, Express.js, React.js, Node.js), StayEase offers features similar to popular platforms like Airbnb, enabling users to search, book, and manage their stays effortlessly.

## Features

- **User Authentication**: Secure user authentication with JWT-based tokens ensures safe access to the platform, enhancing user privacy and data security.

- **Efficient Data Management**: MongoDB and Mongoose are utilized for efficient data storage and retrieval, resulting in optimized database query performance and reduced data retrieval times.

- **Streamlined Booking Process**: StayEase offers a streamlined booking process, allowing users to search for accommodations based on their preferences, view detailed listings, and complete bookings seamlessly.

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

