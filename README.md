# Send_Email using Nodemailer

## How to start

### Installation:

1. Clone the Repository
   ```g
   git clone https://github.com/garaadamiin/send_email.git
   ```
2. Install NPM packages
   ```g
   npm i express ejs nodemailer body-parser cors dotenv
   ```
3. Install nodemon packages
   ```g
   npm install -g nodemon
   ```
4. Start Server
   ```g
   nodemon server.js
   ```

## Development utilities:

- [nodemon](https://www.npmjs.com/package/nodemon)
  - nodemon is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.
- [dotenv](https://www.npmjs.com/package/dotenv)

  - Dotenv is a zero-dependency module that loads environment variables from a `.env` file into `process.env`
    -create .env file then
    EMAIL_HOST=smtp-mail.outlook.com
    EMAIL_PORT=587
    EMAIL_USER=
    EMAIL_PASS=
