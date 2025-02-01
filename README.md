# Syncwave

# Syncwave - Real-Time Chat Web App with AI Integration

Syncwave is a web application that enables real-time chatting with an AI-powered assistant. It uses WebRTC and Socket.IO for seamless communication, integrates LangChain and Google Vertex AI for AI-driven responses, and is built with Node.js, MongoDB, and JWT authentication.

## Features
-  AI Chat : Intelligent responses powered by LangChain and Google Vertex AI.
- Real-Time Chat : Peer-to-peer communication using WebRTC and Socket.IO.
- User Authentication : Secure login and signup functionality using JWT.
- Frontend Animations: Smooth and interactive UI using GSAP.
- Database: MongoDB is used for storing chat data and user information.

## Technologies Used
- Backend: Node.js, Express, REST API
- AI: LangChain, Google Vertex AI
- Real-Time Communication: WebRTC, Socket.IO
- Frontend: GSAP, EJS (Embedded JavaScript Templates)
- Database: MongoDB
- Authentication: JWT (JSON Web Token)

## Prerequisites
Before running the project, make sure you have the following installed:
- [Node.js](https://nodejs.org/) (version >=14.x)
- [MongoDB](https://www.mongodb.com/) (or use MongoDB Atlas for cloud hosting)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/aksharbisht2002/Syncwave.git
   cd Syncwave
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     PORT=5000
     ```

4. Start the application:
   ```bash
   npm start
   ```

5. Open your browser and go to `http://localhost:5000`

## Usage
- Sign up or log in to access the chat.
- Start real-time conversations with users or the AI assistant.
- Enjoy smooth animations and an intuitive chat experience.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any queries or collaboration, feel free to reach out via GitHub or email.

🚀

