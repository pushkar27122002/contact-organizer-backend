# Contact Organizer Backend

This repository contains the backend implementation for a Contact Organizer application built using Node.js and Express.js. The application provides functionalities to manage contacts securely using JWT authentication.

## Prerequisites
- Node.js installed on your system. You can download it from [nodejs.org](https://nodejs.org/).

## Installation
1. Clone this repository to your local machine using:
   ```bash
   git clone https://github.com/yourusername/contact-organizer-backend.git
   ```
2. Navigate into the cloned directory:
   ```bash
   cd contact-organizer-backend
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Configuration
1. Create a `.env` file in the root directory of the project.
2. Define the following environment variables in the `.env` file:
   ```env
   JWT_SECRET=your_secret_key_here
   ```
   
## Authentication
- Authentication is implemented using JSON Web Tokens (JWT). When a user successfully logs in or registers, a JWT token is generated and returned, which must be included in subsequent requests in the `Authorization` header as `Bearer <token>`.

## Security
- This application uses JWT to securely authenticate users and manage their contacts.
- It's important to keep the `JWT_SECRET` environment variable secure and not expose it publicly.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request.

## Contact
For any inquiries or support, please contact pushkarkallurkar@gmail.com.
