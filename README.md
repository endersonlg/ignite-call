# Ignite Call - Full Stack Application with Next.js

The Ignite Call is an exciting full-stack project that utilizes Next.js for both frontend and backend development. This repository provides all the necessary resources to build and deploy a comprehensive application, complete with integration to Google Calendar, route authentication, validations, and much more.

## Description

In this project, we dive into full-stack development using Next.js, covering key features such as user authentication, seamless integration with Google Calendar, and robust data validations to ensure high-level data quality and security.

## Features

- Full-stack development powered by Next.js.
- Frontend route authentication.
- Seamless integration with Google Calendar.
- Comprehensive data validations for optimal data integrity.

## Getting Started

Follow these steps to get started with the project:

1. Clone this repository to your local machine using the command: `git clone https://github.com/endersonlg/ignite-call.git`
2. Navigate to the project directory: `cd ignite-call`
3. Install project dependencies: `npm install` or `yarn install`
4. Rename the `.env.example` file to `.env`.
5. Fill in the variables in the `.env` file as per the instructions below to configure integration with Prisma, Google authentication, and NextAuth:
   ```plaintext
   #PRISMA
   DATABASE_URL=

   #Google oAuth
   GOOGLE_CLIENT_ID=
   GOOGLE_CLIENT_SECRET=

   #NextAuth
   NEXTAUTH_SECRET=
   ```
6. To start the application, run the following command in the terminal, using npm run dev or yarn dev.

## Contribution
Contributions via pull requests are highly encouraged. If you encounter any issues or have ideas for improvements, please open an issue to facilitate discussion and collaboration.
