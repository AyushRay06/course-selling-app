# Course Selling Website Backend

This repository houses the backend for a Course Selling Website, employing Express.js as the backend framework, MongoDB as the database, Zod library for input validation, and Auth for user validation. JSON Web Tokens (JWT) are utilized for secure and stateless authentication.

## Getting Started

To initiate the project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/course-selling-app.git
   ```

2. Install the necessary dependencies:

   ```bash
   cd course-selling-app
   npm install
   ```

3. Configure the environment:

   - Create a `.env` file in the project root and set the following variables:

     ```env
     PORT=3000
     MONGODB_URI=mongodb://localhost:27017/course_selling_db
     JWT_SECRET=your_jwt_secret_key
     ```

4. Launch the application:

   ```bash
   node index.js
   ```

   The server will run on the specified port (default is 3000).

## Dependencies

- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: NoSQL database for storing and retrieving data.
- **Zod**: TypeScript-first schema declaration and validation library.
- **JWT**: JSON Web Tokens for secure authentication.
