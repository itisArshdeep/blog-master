# BlogMaster

**BlogMaster** is a modern, feature-rich blogging platform built using React and Vite for the frontend, with Appwrite as the backend service. It enables users to create, manage, and share their blog posts seamlessly.

## Features

- 📝 **Write and Edit Blogs**: Intuitive editor to create and update blog content.
- 📚 **Blog Listing**: View all published blogs in an organized manner.
- 🔐 **User Authentication**: Secure login and registration using Appwrite.
- 🗂️ **Data Management**: Manage posts, comments, and user profiles with Appwrite's database.
- 🚀 **Fast and Modern UI**: Leveraging the speed of Vite and React.

---

## Tech Stack

### Frontend:
- **React**: For building a responsive and dynamic UI.
- **Vite**: Ultra-fast development environment and build tool.

### Backend:
- **Appwrite**: Backend-as-a-service (BaaS) for authentication, database, and storage.

---

## Getting Started

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v16 or later)
- **NPM** or **Yarn**
- **Appwrite Server** (set up and running)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/blogmaster.git
   cd blogmaster
2. Install dependencies:
   npm install
# or
yarn install
3. Set up environment variables: Create a .env file in the root directory and configure the following variables:
VITE_APPWRITE_URL=""
VITE_APPWRITE_PROJECT_ID=""
VITE_APPWRITE_DATABASE_ID=""
VITE_APPWRITE_COLLECTION_ID=""
VITE_APPWRITE_BUCKET_ID=""

4. Run the development server:
npm run dev
# or
yarn dev
