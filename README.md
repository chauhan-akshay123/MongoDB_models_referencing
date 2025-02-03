# MongoDB Models Referencing

This project demonstrates how to establish **referenced relationships** between MongoDB models using **Mongoose** in a Node.js application.

## 📌 Features
- User and Post models with referencing (`author` in `Post` refers to `User`).
- MongoDB connection using Mongoose.
- CRUD operations for `User` and `Post` models.
- Populating referenced documents.

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository  
```
git clone https://github.com/chauhan-akshay123/MongoDB_models_referencing.git
cd MongoDB_models_referencing
```

### 2️⃣ Install Dependencies
``` npm install ```

### 3️⃣ Create a .env File
 - Inside the project root, create a .env file and add your MongoDB connection string
 - " MONGODB=mongodb+srv://<your-username>:<your-password>@cluster.mongodb.net/<database-name>?retryWrites=true&w=majority"

### 4️⃣ Run the Project
``` node index.js ```

--- 

### 📌 Usage 
### 1️⃣ Add a User
 - Calls a function to create and store a user in the database.
### 2️⃣ Add a Post
 - Creates a post with an author reference to an existing user.
### 3️⃣ Fetch All Posts with Author Info
 - Uses ```.populate("author")``` to retrieve posts along with user details.  
 
 

