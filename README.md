# Life Manager

Life Manager is a web application designed to help users organize and manage various aspects of their daily lives. Whether it's tracking tasks, setting goals, or managing schedules, Life Manager provides a centralized platform for users to streamline and enhance their daily routines.

## Features

- **Task Management:** Create, update, and prioritize tasks to stay organized and on top of your responsibilities.
- **Goal Setting:** Set and track your short-term and long-term goals to stay focused on personal and professional growth.
- **Schedule Management:** Plan and manage your daily schedule to optimize productivity and allocate time effectively.

## Technologies Used

- **Frontend:** Built with React, a popular JavaScript library for building user interfaces.
- **Backend:** Developed using Nest.js, a progressive Node.js framework for building efficient, scalable server-side applications.
- **Database:** Utilizes Postgres as the relational database to store and retrieve data.
- **Authentication:** Implements JSON Web Tokens (JWT) for secure user sessions.

## Getting Started

To get started with Life Manager, follow these steps:

### Prerequisites

- Node.js and npm installed on your machine.
- PostgreSQL installed and a database created for Life Manager.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/lucianostegun/life-manager.git
cd life-manager
```

2. Install dependencies:

```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
```

3. Configure the database:

   - Create a `.env` file in the `backend` directory and set your PostgreSQL connection details:

   ```
   DB_HOST=your_db_host
   DB_PORT=your_db_port
   DB_USERNAME=your_db_username
   DB_PASSWORD=your_db_password
   DB_NAME=your_db_name
   ```

4. Run the application:

   - Frontend:

   ```bash
   cd frontend
   npm start
   ```

   - Backend:

   ```bash
   cd backend
   npm start
   ```

5. Access the application:

   Open your web browser and visit `http://localhost:3000` to use Life Manager.

## Contributing

Contributions are welcome! Please check the [CONTRIBUTING.md](CONTRIBUTING.md) file for more details on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Special thanks to the React and Nest.js communities for their excellent frameworks and tools.
