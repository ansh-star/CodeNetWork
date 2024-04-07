# CodeNetWork

CodeNetWork is a full-stack social network application for developers. It is built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) and provides a platform for developers to create profiles, share posts, and connect with other developers.

## CodeNetwork Project Walkthrough

If you'd like to see a video walkthrough of the CodeNetWork project, you can check out the following YouTube video:

https://youtu.be/SvX35K5s-DA

This walkthrough should give you a comprehensive understanding of the CodeNetWork project and how it works. Feel free to refer to the video as you explore the codebase and try out the application yourself.

## Features

### User Authentication
- Developers can register, log in, and manage their profiles.

### Developer Profiles
- Registered users can create and update their developer profiles, including information about their skills, experience, education, and social media links.
- If the user has a Gravatar account associated with the email address used for their CodeNetWork account, their Gravatar profile picture will be displayed on their developer profile.

### Posts and Comments
- Users can create posts, which other users can comment on.
- The application supports features like liking, commenting, and deleting posts.

### Developer Network
- Users can find and connect with other developers, view their profiles, and interact with them through posts and comments.

### GitHub Repository Integration
- When users log in and provide their GitHub username, the application fetches and displays their top 5 most recent GitHub repositories.
- For each repository, the following information is displayed:
  - Repository name
  - Repository description
  - Number of stars
  - Number of forks
  - Link to the repository on GitHub

This integration with the GitHub API allows developers to showcase their GitHub projects and activity directly on the CodeNetWork application, enhancing the overall user experience and promoting collaboration within the developer community.

## Tech Stack

**Frontend**:
- React.js
- Redux

**Backend**:
- Node.js
- Express.js

**Database**:
- MongoDB

**Authentication**:
- JSON Web Tokens (JWT)

## Key Packages Used

**Frontend**:
- React Router
- Axios
- React Redux
- Redux Thunk

**Backend**:
- Express
- Mongoose
- Bcrypt
- JSON Web Token
- Validator
- Config
- Gravatar
- Normalize-url


## Getting Started

To get started with the CodeNetWork project, please follow these steps:

### Clone the repository:
   ```
   https://github.com/ansh-star/CodeNetWork.git
   ```
### Add a default.json file in config folder with the following

   ```json
   {
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubCLientId": "<yoursecrectaccesstoken>",
  "githubSecret":"<youtgithubsecrettoken>"
   }
   ```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run both Express & React from root

```bash
npm run dev
```
### Open the application in your browser at `http://localhost:3000`.

## Contributing

CodeNetWork is an open-source project, and contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue on the [GitHub repository](https://github.com/ansh-star/CodeNetWork).

![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/0154bc4d-250c-459d-864e-8bda82722d97)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/01bf5547-58be-4404-9ebe-57faf34acb8e)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/aeb5da05-85a2-4cf5-bea2-e613036c3ae5)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/e9a86ab8-2a1c-4d2b-acf7-53dbf1536f27)

![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/2ef9caef-16e1-43cd-a157-3241b4353bfb)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/b44f2ed7-268d-4b79-b02d-d3ae7403e832)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/d9b2fdd3-ec1f-49b8-bae4-637637f07dfa)

![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/2bab3202-a8b2-46ba-9a5d-52bca3035270)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/dae6d098-c0bd-48ec-b109-b7b3fa00e159)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/52dee0bd-5ff6-4655-b5f2-d9bba03891d8)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/d1225b47-9c80-40b5-a834-11bdf4bc161c)
![image](https://github.com/ansh-star/CodeNetWork/assets/96314656/89cb172a-1cc9-45af-ab2f-3032794c24b7)
