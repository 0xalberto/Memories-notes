# Memories Notes App <img src="./frontend/public/logo192.png" width="30" height="30">

A fullstack web application built with the MERN stack that allows users to sign up, log in, create, update, delete, and download notes in text format. This app features modern UI/UX with various libraries and frameworks. <br /> <br />
[Click here](https://memories-note-app.vercel.app/) to preview

## App Screenshots
![Screenshot (5)](https://github-production-user-asset-6210df.s3.amazonaws.com/91872021/344429791-1d306c61-908d-4a84-8d0a-390a36b8c7bd.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250313%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250313T095309Z&X-Amz-Expires=300&X-Amz-Signature=b41743ccda99ac537d6a37f8ccbfa2f7a59d343ded1245a188f9ccabb3ff8b4b&X-Amz-SignedHeaders=host)

![Screenshot (6)](https://github.com/0xalberto/Memories-notes/assets/91872021/9481f0f6-c1ee-48b1-8934-83cac7204783](https://private-user-images.githubusercontent.com/91872021/344429795-9481f0f6-c1ee-48b1-8934-83cac7204783.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDE4NTk1NjcsIm5iZiI6MTc0MTg1OTI2NywicGF0aCI6Ii85MTg3MjAyMS8zNDQ0Mjk3OTUtOTQ4MWYwZjYtYzFlZS00OGIxLTg5MzQtODNjYWM3MjA0NzgzLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAzMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMzEzVDA5NDc0N1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWEwNTIzNzgwYjM4YmQ5MTllZWQ5MmE0YjgyOWVkMDQ4ZWRjYWYxOGM4NjNjMzFkMGMxZmYwZWU1ZTM3ZTEyNzgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.foJJgtkJ7ZVU1DlJvpzhau0tm-rcyNNEr6Xm-LJtgYg))
![light](https://private-user-images.githubusercontent.com/91872021/344429804-d4854f58-76f2-421b-a209-e4cfaf5397cd.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDE4NTk1NjcsIm5iZiI6MTc0MTg1OTI2NywicGF0aCI6Ii85MTg3MjAyMS8zNDQ0Mjk4MDQtZDQ4NTRmNTgtNzZmMi00MjFiLWEyMDktZTRjZmFmNTM5N2NkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAzMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMzEzVDA5NDc0N1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY2ZmU2NmU5ODUyYzM5M2VhYmE1NTYwYjhmZWQzMjhkNWMyYjdlMDc2NjM3ZDI3OThlZGY3ZmQ2YTZkZGJlNzcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.tU6lhEZOD1-fbQkwbeivDKwlPInqSPyVZzC1yIxf1SM)
![dark](https://private-user-images.githubusercontent.com/91872021/344429805-feb30706-0ac0-4373-ac6b-ad550db7ab73.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDE4NTk1NjcsIm5iZiI6MTc0MTg1OTI2NywicGF0aCI6Ii85MTg3MjAyMS8zNDQ0Mjk4MDUtZmViMzA3MDYtMGFjMC00MzczLWFjNmItYWQ1NTBkYjdhYjczLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAzMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMzEzVDA5NDc0N1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY0N2M0YTczNDM1NGJhNWJjMDMxZDlkMWU5ODE2NWFmNTlkYmE2MDcwNzc4ZDJmNzI2OGU3YTEwZDIxZDMyMGYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.P5CYTvDKSO_1CffTTO23ZCk2PKBGsgndBl6tm9N4_QY)



## Features

- User Authentication with JWT
- Create, Update, Delete Notes
- Download Notes in Text Format
- Modern UI/UX
- Secure and Efficient

## Tech Stack

### Frontend
- **React.js**: For building dynamic user interfaces
- **Tailwind CSS**: For modern, responsive design
- **Ant Design (AntD)**: For polished UI components
- **GSAP & ScrollTrigger**: For animations and scroll interactions
- **Locomotive.js**: For smooth scrolling effects
- **React Router**: For routing and navigation

### Backend
- **Node.js**: For server-side JavaScript
- **Express.js**: For building RESTful APIs
- **MongoDB**: For database management

### Security
- **JWT (JSON Web Tokens)**: For secure user authentication

## Getting Started

### Prerequisites

Make sure you have the following installed on your local development machine:

- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/0xalberto/Memories-notes.git
    cd Memories-a-note-app
    ```

2. **Install dependencies:**

    ```bash
    # Install server dependencies
    cd server
    npm install

    # Install client dependencies
    cd frontend
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the `server` directory and add the following:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

### Running the App

1. **Start the backend server:**

    ```bash
    cd server
    npm run dev
    ```

2. **Start the frontend development server:**

    ```bash
    cd frontend
    npm start
    ```

The application should now be running on [http://localhost:3001](http://localhost:3001).

## Usage

1. **Sign up** for an account.
2. **Log in** with your credentials.
3. **Create, update, and delete notes** as needed.
4. **Download notes** in text format.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [React.js](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Ant Design](https://ant.design/)
- [GSAP](https://greensock.com/gsap/)
- [Locomotive.js](https://locomotivemtl.github.io/locomotive-scroll/)
- [React Router](https://reactrouter.com/)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)

---

Happy coding! 🚀
