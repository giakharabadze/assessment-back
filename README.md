A simple authentication API built with NestJS, Prisma, and SQLite.

This project provides a minimal backend system with basic user registration and login endpoints using a local SQLite database and Prisma as the ORM.

Follow these steps to set up and run the project locally on your machine.


1. Clone the Repository
git clone https://github.com/giakharabadze/assessment-back.git

2. Install Dependencies
npm install

3.Create .env in the root directory  and add the following environment variable to it:
DATABASE_URL="file:./dev.db"

4. Generate Prisma Client
npx prisma generate

5. Start the Development Server
npm run start:dev
server will be running on port 3000


## 🛠 API Endpoints

### POST /auth/register
Registers a new user.

### POST /auth/login
Logs in a registered user.