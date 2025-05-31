# Wanderlust: An Airbnb-Inspired Full-Stack Web Application 🌍🏠

Wanderlust is a meticulously crafted full-stack web application that emulates the core functionalities of popular rental platforms like Airbnb. This project serves as a comprehensive demonstration of my skills in building robust, user-friendly web experiences from the ground up, showcasing proficiency in both front-end and back-end development.

---

## ✨ Features

Wanderlust provides a complete set of features for managing rental listings and user interactions:

* **Comprehensive Listing Management:**
    * **View Listings:** Browse through a diverse collection of rental properties.
    * **Create New Listings:** Users can easily add their own properties with detailed information.
    * **Edit Listings:** Owners have the ability to modify their property details.
    * **Delete Listings:** Owners can remove their properties from the platform.
* **User Authentication & Authorization:**
    * **Sign Up:** New users can register for an account.
    * **Login:** Registered users can securely access their profiles.
    * **Logout:** Users can safely end their session.
* **Interactive Reviews:** Users can leave and view reviews for different listings, enhancing community engagement.
* **Responsive Design:** Ensures a seamless user experience across various devices (desktops, tablets, and mobile phones).

---

## 💻 Technologies Used

Wanderlust is built using a modern full-stack technology stack:

### Frontend

* **HTML5:** Structuring the core web content.
* **CSS3:** Styling and layout, including responsive design principles for optimal viewing across devices.
* **JavaScript:** Enhancing interactivity and dynamic content.

### Backend

* **Node.js:** JavaScript runtime environment for efficient, scalable server-side logic.
* **Express.js:** A fast, unopinionated, minimalist web framework for Node.js, used for building robust APIs.
* **Express Sessions:** Middleware for handling secure user sessions.
* **MVC (Model-View-Controller):** Architectural pattern used for organizing code, promoting separation of concerns and maintainability.

### Database

* **MongoDB:** A flexible and scalable NoSQL database for efficient data storage.
* **Mongoose:** An ODM (Object Data Modeling) library for MongoDB and Node.js, simplifying data interactions and schema definition.

### Package Management

* **NPM (Node Package Manager):** Used for managing project dependencies and running scripts.

---

## 🧠 Learning & Development

Developing Wanderlust was an invaluable learning experience that significantly deepened my understanding of:

* **Full-stack development workflows:** Connecting frontend and backend components seamlessly.
* **Database management:** Designing schemas, performing CRUD (Create, Read, Update, Delete) operations, and ensuring data integrity with MongoDB and Mongoose.
* **API design and implementation:** Building RESTful APIs with Node.js and Express.js.
* **Authentication and authorization:** Implementing secure user login and session management.
* **MVC architecture:** Organizing complex applications into manageable and scalable components.
* **Error handling and middleware:** Building robust and resilient web applications.

---

## 🚀 How to Run Locally

Follow these steps to get Wanderlust up and running on your local machine for development and testing:

1.  **Clone the repository:**
    ```bash
    git clone [Your GitHub Repo Link]
    cd wanderlust
    ```
    *Replace `[Your GitHub Repo Link]` with the actual HTTPS or SSH link to your GitHub repository.*

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up environment variables:**
    Create a `.env` file in the root directory of the project and add your MongoDB URI:
    ```
    DB_URL=your_mongodb_connection_string
    ```
    *Replace `your_mongodb_connection_string` with your actual MongoDB connection URI (e.g., from MongoDB Atlas or a local instance).*

4.  **Start the server:**
    ```bash
    npm start
    ```

5.  **Visit the application:**
    Open your web browser and go to `http://localhost:3000` (or the port specified in your `.env` file or `app.js`).

---

## 🔐 Sample Credentials

You can sign up with your own credentials or use the following sample credentials to explore the application's features:

* **Email:** `sample@example.com`
* **Password:** `password123`

---

Feel free to explore the code, provide feedback, or suggest improvements!
