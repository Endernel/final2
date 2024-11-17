**Cities Portfolio Platform**

An advanced portfolio platform built using Node.js, Express, MongoDB,
and HTML/CSS.

The platform allows admin/editor to make some crud operation to the
Cities in pink interface.

**Features**

- Custom pink theme

- Full CRUD (Create, Read, Update, Delete) operations for blog posts

- MongoDB integration using Mongoose

- Authentication and Authorization system

- Role based system

- API usage

- Data visualization

**Prerequisites**

Before you begin, ensure you have met the following requirements:

\- Node.js <https://nodejs.org/en/> installed (version 12 or higher)

\- A code editor like \[VSCode\] <https://code.visualstudio.com/>

\- Register at Mongodb for database <https://cloud.mongodb.com/>

**Installation and Setup**

Step 1: Create a Folder

Create a folder where all your working files will be stored. For
example, you can name it portfolio

Step 2: Open the Folder in a Code Editor

Open the folder in your code editor, such as Visual Studio Code:

Step 3: Initialize the Project and Install Dependencies

1\. Initialize a new Node.js project by running: **npm init -y**

This will create a \`package.json\` file with the default settings.

2\. Install the necessary libraries for your project by running: **npm
install bcrypt body-parser cookie-parser dotenv express jsonwebtoken
mongoose path qrcode speakeasy**

We will be using the following Node libraries:

1.  bcrypt: For hashing passwords, ensuring secure storage of user
    passwords in the database.

2.  body-parser: Parses incoming HTTP request bodies (e.g., JSON or
    URL-encoded data).

3.  cookie-parser: Handles HTTP cookies, useful for session management.

4.  dotenv: Manages environment variables using a .env file.

5.  express: A framework for building server-side applications in
    Node.js, simplifies routing and HTTP request handling.

6.  jsonwebtoken: Used for creating and verifying JWT (JSON Web Tokens)
    for authentication purposes.

7.  mongoose: An ODM library for MongoDB, allowing schema-based
    interaction with the database.

8.  path: Provides utilities for working with file and directory paths,
    ensuring cross-platform compatibility.

9.  speakeasy: Implements two-factor authentication (2FA), including
    Time-based One-Time Password (TOTP).

Step 4: Set up MongoDB

1.  Create a free account at [MongoDB
    Atlas](https://cloud.mongodb.com/).

2.  Create a new cluster and database.

3.  Copy the MongoDB connection URI and store it in server.js file

Step 5: Do not forget to login  
Admin (username: Anel, password 123)

Editor (<lolla@gmail.com>, password 1234)

Your project is now set up and ready for further development!

**Running the Application**

Once the environment is set up, you can run the application by using:
**node server.js**

By default, the app will be running on <http://localhost:3000>

**Usage**

File Structure  
portfolio-platform/

├── server.js

├── .env

├── config/

│ ├── db.js

├── middlewares/

│ ├── authMiddleware.js

├── models/

│ ├── Item.js

│ ├── User.js

├── routes/

│ ├── admin.js

│ ├── auth.js

│ ├── itemRoutes.js

├── utils/

│ ├── generate2FACode.js

├── views/

│ ├── index.html

│ ├── item.html

│ ├── login.html

│ ├── main.html

│ ├── register.html

│ ├── css/

│ │ ├── style.css

│ ├── js/

│ ├── script.js

├── node_modules/

├── package.json

├── package-lock.json

└── README.md

## Custom Styling

The project uses a pink color palette-style theme for the user
interface. All the styles are defined in views folder and you can update
colors by modifying the CSS in the views/css/styles.css.

## License

This project is open source and available under the MIT License.

## Contact

For issues or contributions, please feel free to open a pull request or
contact me at anel@example.com.
