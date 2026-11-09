# Binary Upload Boom

A social networking site built with Node.js, Express, and MongoDB. Users sign up, upload pictures with a title and caption, browse a feed of everyone's posts, and like and comment on other users' posts.

![Binary Upload Boom demo](./public/imgs/demo.png)

## Try it Here
[Live Link](https://binary-upload-boom-yhyx.onrender.com)

## Features

- User signup and login with authentication
- Upload a picture with a title and caption
- Browse a feed of posts from all users
- Like other users' posts
- Comment on other users' posts

## Tech Stack

- HTML, CSS, JavaScript
- Node.js and Express
- MongoDB with Mongoose
- EJS templates
- Passport.js for authentication
- Cloudinary and Multer for image uploads

## Getting Started

### Prerequisites

- Node.js and npm
- A MongoDB database and connection URI
- A Cloudinary account for image storage

### Installation

1. Clone the repository and move into the project directory.
2. Install the dependencies:

   ```
   npm install
   ```
3. Create a `config/.env` file with the following values:

   ```
   PORT=2121
   DB_STRING=mongodb+srv://<username>:<password>@<cluster>/<database>?retryWrites=true&w=majority
   CLOUD_NAME=your-cloudinary-cloud-name
   API_KEY=your-cloudinary-api-key
   API_SECRET=your-cloudinary-api-secret
   ```

   Replace the placeholders with your own database and Cloudinary details.
4. Start the server:

   ```
   npm start
   ```
5. Open [http://localhost:2121](http://localhost:2121) in your browser.

## Usage

1. Sign up for an account or log in.
2. Upload a picture with a title and caption.
3. Scroll the feed to see posts from other users.
4. Like a post, or leave a comment on it.
