# Interactive Gym Web Application

A dynamic and feature-rich web application designed to enhance user engagement and streamline communication for gym enthusiasts. Built with modern web technologies, the application offers interactive tools and a seamless user experience.

## Features

- **Responsive Frontend**: Built with React to ensure a user-friendly and responsive interface across devices.
- **BMI Calculator**: An interactive tool to calculate Body Mass Index and provide users with health insights.
- **Contact Form**: Facilitates effective communication, with form submissions handled seamlessly through the backend.
- **Email Functionality**: Integrated Nodemailer for email notifications, enhancing user interaction and support.
- **Smooth Navigation**: Utilized React Router for effortless and dynamic navigation between different sections of the site.
- **Secure Requests**: Implemented CORS to manage secure cross-origin resource sharing.
- **Environment Management**: Used `dotenv` to securely manage environment variables.

## Tech Stack

### Frontend:
- **React**: For creating a dynamic and interactive user interface.
- **CSS/SCSS**: To style the application and ensure a visually appealing design.
- **React Router**: For seamless page transitions and navigation.

### Backend:
- **Node.js**: For server-side operations.
- **Express.js**: To build a robust and scalable backend.
- **Nodemailer**: For handling email functionality.
- **CORS**: To enable secure cross-origin requests.
- **dotenv**: For managing sensitive environment variables.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/interactive-gym-web-app.git
   cd interactive-gym-web-app
   ```

2. **Install Dependencies**:

   - Frontend:
     ```bash
     cd frontend
     npm install
     ```
   - Backend:
     ```bash
     cd backend
     npm install
     ```

3. **Setup Environment Variables**:
   - Create a `.env` file in the `backend` directory and add the following:
     ```plaintext
     EMAIL_SERVICE=<your-email-service>
     EMAIL_USER=<your-email-address>
     EMAIL_PASS=<your-email-password>
     ```

4. **Start the Application**:
   - Backend:
     ```bash
     cd backend
     npm start
     ```
   - Frontend:
     ```bash
     cd frontend
     npm start
     ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

- **BMI Calculator**: Navigate to the BMI Calculator section, input your height and weight, and get instant health insights.
- **Contact Form**: Fill out the contact form to send inquiries or feedback. Emails will be sent using Nodemailer.
- **Explore**: Use the React Router-powered navigation to explore different sections of the app effortlessly.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
