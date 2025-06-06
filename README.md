# test-interview

//how to run todo-api :
  1. Install Node.js
Make sure you have Node.js installed (version 18 or higher is recommended based on your package.json). You can download it from nodejs.org.

2. Install Dependencies
Open your terminal/command prompt and navigate to the project directory, then run:

bash
npm install
# or
yarn install
# or
pnpm install
This will install all the dependencies listed in your package.json.

3. Start the Development Server
After dependencies are installed, start the development server with:

bash
npm run dev
# or
yarn dev
# or
pnpm dev
4. Access the Application
Once the server starts (you'll see a message like "ready - started server on 0.0.0.0:3000"), open your browser and visit:

text
http://localhost:3000
5. Test the API Endpoints (Optional)
You can test the API endpoints using the test-api.rest file:

Use VS Code with the REST Client extension

Or tools like Postman or Thunder Client

Example endpoints:

GET todos: GET http://localhost:3000/api/todos

POST a new todo: POST http://localhost:3000/api/todos with JSON body

6. Development Workflow
Edit files in the app directory (like app/page.tsx) to see live changes

The page will automatically reload when you save changes

2.
// how to run secondtest:
  1. Install Required Dependencies
First, make sure you have the necessary tools installed:

bash
npm install -D typescript ts-node
# or
yarn add -D typescript ts-node
2. Run the Script
You have two options to run the TypeScript file:

Option A: Using ts-node directly
bash
npx ts-node test.ts
Option B: Using Node with ESM loader (if you need ES modules)
bash
node --loader ts-node/esm test.ts
3. Expected Output
The script should:

Import the listNotes function from the specified path

Call it with { maxResults: 2 }

Log the returned notes to the console

3.//how to run ai-chat-app:
  npm run dev
