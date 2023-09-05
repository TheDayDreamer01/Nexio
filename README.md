# Nexio 👨🏻‍💻

Nexio is a modern and efficient Contact Management System designed to simplify your contact management tasks. This README provides an overview of Nexio, its tech stack, instructions for installation using ReactJS, Vite, and ASP.NET, details on how to use Docker Compose for deployment, licensing information, and more.

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Installation](#installation)
    - [Backend Installation](#backend-aspnet)
    - [Frontend Installation](#frontend-reactjs-with-vite)
    - [Docker Compose Installation](#docker-compose)
4. [Usage](#usage)
5. [License](#license)

## Overview

Nexio is an MVC architecture application that seamlessly manages your contacts and interactions. Its key features include:

- **Contact Management:** Easily create, view, update, and delete contacts.
- **Suggestion System:** Get intuitive suggestions to enhance your interactions.
- **User-Friendly Interface:** A clean and user-friendly interface for efficient contact management.
- **Tech-Driven:** Built using modern technologies like ASP.NET, ReactJS, and Docker.

## Tech Stack

Nexio leverages a modern and robust tech stack to deliver an efficient contact management experience:

- **Backend:** ASP.NET MVC
- **Frontend:** ReactJS with Vite
- **UI Design:** Tailwind CSS
- **Version Control:** Git
- **Containerization:** Docker

## Installation

To get Nexio up and running on your local machine, follow these installation steps:

### Backend (ASP.NET)

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/TheDayDreamer01/ContactManagement-ASP.NET.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd backend
   ```

3. **Install Dependencies:**

   ```bash
   dotnet restore
   ```

4. **Run the ASP.NET Application:**

   ```bash
   dotnet run
   ```

5. The Nexio backend should now be running at `http://localhost:8000`.

### Frontend (ReactJS with Vite)

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/TheDayDreamer01/ContactManagement-ReactJS.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd frontend
   ```

3. **Install Dependencies:**

   ```bash
   npm install
   ```

4. **Start the Development Server:**

   ```bash
   npm run dev
   ```

5. The Nexio frontend should now be running at `http://localhost:3000`.

## Docker Compose

Nexio can be deployed using Docker Compose, which makes it easy to manage multi-container Docker applications.

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/TheDayDreamer01/Nexio.git
   ```

2. **Navigate to the Docker Compose Directory:**

   ```bash
   cd nexio
   ```

3. **Start Nexio Using Docker Compose:**

   ```bash
   docker-compose up -d
   ```

4. Nexio should now be accessible at `http://localhost:3000`.

## Usage

Nexio is designed to be user-friendly and intuitive. Simply log in, and you can start managing your contacts, accessing suggestions, and organizing your interactions efficiently.

## License

Nexio is open-source software licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as needed.
