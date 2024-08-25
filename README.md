Here's a proper README for your Fullstack MERN Blogging Website project:

---

# MERN Blogging Website

This is a modern, feature-rich blogging website built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The website includes a variety of functionalities tailored for an optimal blogging experience.

## Features

- **Modern Blog Editor**: Utilize Editor JS for an advanced and intuitive blog editing experience.
- **Google Authentication**: Secure and convenient user authentication via Google.
- **Dynamic Blog Pages**: Blogs are rendered on dynamic URLs, making each post easily accessible.
- **Search Functionality**: Users can search for blogs and other users through a dedicated search page.
- **User Profiles**: Each user has a dedicated profile page displaying their social links and written blogs.
- **Dashboard**: A personalized dashboard for managing published and draft blogs.
- **Blog Post Analytics**: Analytics for each blog post, with options to edit or delete them.
- **Interactive Features**: Users can like blogs and comment on posts, with a nested comment system allowing replies.
- **Notification System**: All interactions generate notifications for the respective users. Recent notifications are highlighted separately from old ones.
- **Profile Editing**: Users can update their social links, bio, and username. The option to change the login password is available in the settings.
- **Mobile Responsive Design**: The website is fully responsive with a modern design and fade-in animations for smooth transitions between pages.

## Demo

Check out the [Demo](#) of the website.

![Thumbnail](#)

## Installation

### Prerequisites

- Node.js
- MongoDB

### Steps

1. **Fork the Repository**: Start by forking this repository to your GitHub account.
2. **Clone the Repository**: Clone the forked repository to your local machine.
    ```bash
    git clone https://github.com/your-username/mern-blogging-website.git
    ```
3. **Install Dependencies**: Navigate to the project directory and install the required dependencies.
    ```bash
    cd mern-blogging-website
    npm install
    cd client
    npm install
    ```
4. **Environment Variables**: Create a `.env` file in the root directory and add the necessary environment variables.
    ```plaintext
    MONGO_URI=your-mongodb-uri
    GOOGLE_CLIENT_ID=your-google-client-id
    GOOGLE_CLIENT_SECRET=your-google-client-secret
    JWT_SECRET=your-jwt-secret
    PORT=5000
    ```
5. **Run the Application**: Start the development server.
    ```bash
    cd ..
    npm run dev
    ```
   The app should now be running on `http://localhost:5000`.

## Usage

- **Blog Creation**: Sign in using Google, create a new blog post using the modern blog editor, and publish or save it as a draft.
- **Profile Management**: Update your profile information, including social links and bio, from your profile page.
- **Interacting with Blogs**: Like, comment, and reply to other users' blog posts.
- **Manage Blogs**: Use the dashboard to edit, delete, or view analytics for your blog posts.

## Technologies Used

- **Frontend**: React.js, Editor JS, CSS, Bootstrap
- **Backend**: Node.js, Express.js, JWT, MongoDB, Mongoose
- **Authentication**: Google OAuth 2.0
- **Database**: MongoDB
- **Others**: Axios, React Router, Redux

## Contributing

If you wish to contribute to this project, feel free to fork the repository and create a pull request with your changes. Contributions are always welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## author

- [Rohit Kumar](www.rohitsaraf.in)
