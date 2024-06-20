
Project Link -> 

A clone of the Netflix web version app using , , , , , and ReactNextJSTailwind CSSPrismaMongoDBNextAuthVercel

🚀 Starting
These instructions will allow you to obtain a copy of the working project on your local machine for development and testing purposes.

🔧 Installation
A series of step-by-step examples that tell you what you should do to have a development environment running. You need to install all project dependencies

$ npm install
You need to have the environment settings

# .env.example
DATABASE_URL=

NEXTAUTH_JWT_SECRET=
NEXTAUTH_SECRET=

GITHUB_ID=
GITHUB_SECRET= 

GOOGLE_CLIENT_ID= 
GOOGLE_CLIENT_SECRET= 
You need to initialize the prism

$ npx prisma generate
The next step is to start the project

$ npm run dev
⚙️ Running the application
After installation, you must enter the https://localhost:3000/ link to view the application.

📃 Navigation Routes
Address	Description
/	Select Movies
/Auth	Log in
/profiles	Select a profile
🛠️ Built with
NodeJS - JavaScript Runtime
NextJS - Web Framework
Tailwind CSS - Framework for styling
Prism. - The easiest way to work with a database in Next.js
NextAuth. - Authentication for Next.js
MongoDb. - NoSQL database management system
Social media
Twitter
⌨️ with ❤️ by rahul 👨 💻
