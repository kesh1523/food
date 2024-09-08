## Installation

   1. Clone the repository:
      ```
      git clone https://github.com/yourusername/your-repo-name.git
      ```

   2. Navigate to the project directory:
      ```
      cd your-repo-name
      ```

   3. Install dependencies:
      ```
      npm install
      ```

   4. Start the development server:
      ```
      npm start
      ```

# NodeJs-Final-Project

## Regarding Database Access!!

The MongoDB URI is stored in `config.js`, which is not included in version control. To set up your own MongoDB database, create a `config.js` file in the root directory of the project with the following format:

```javascript
module.exports = {
  dbURI: 'your_mongodb_uri_here'
};
```

Replace `your_mongodb_uri_here` with your own MongoDB URI. Make sure to keep this file private and secure.

After following that, do these steps : -

1.) Install node-modules folder by running npm install\
2.) Run nodemon app to start the app on localhost:3000
