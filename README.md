# Ágora

## 📜 Description

Ágora is a FullStack application providing a comprehensive online learning platform. It offers a seamless experience for both learners and instructors, allowing for course creation, management, and access. This repository contains the code for both the frontend and backend of the Ágora platform.

**Note:** [Live Preview](https://agora-client-azure.vercel.app/) available for viewing.

## 🔨 Main Features

1. 📊 **Dashboard**

   - Provides a detailed overview of users, courses, and orders along with analytics for the last 28 days.

2. 🔐 **Login / Registration**

   - Secure and personalized experience using NextAuth for authentication.

3. 🎓 **Courses**

   - Allows creating, editing, deleting, and updating courses on the platform.

4. 🛍️ **Orders**

   - Manage course purchases and maintain an organized view of all orders.

5. 📜 **Notifications**

   - Real-time notifications for users using Socket.io, with features to get and update notification statuses.

6. 🙍‍♂️ **User Management**

   - Admin dashboard to manage user information, ban users, and view user analytics.

7. 📱 **Responsiveness**

   - Fully adaptable for viewing on any device.

## 👩‍💻 Technologies Used

### Frontend

- [Next.js](https://nextjs.org/) - React framework for server-side rendering.
- [Typescript](https://www.typescriptlang.org/) - Programming language adding static types to JavaScript.
- [RTK Query](https://redux-toolkit.js.org/rtk-query/overview) - Toolset for efficient data fetching.
- [Socket.io](https://socket.io/) - Library for real-time web applications.
- [Redux](https://redux.js.org/) - State management tool.
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework for styling.
- [Material UI](https://mui.com/) - React components for faster and easier web development.
- [Formik](https://formik.org/) - Library for building forms in React.
- [Yup](https://github.com/jquense/yup) - JavaScript schema builder for value parsing and validation.
- [Toast](https://react-hot-toast.com/) - Notifications library for React.
- [NextAuth](https://next-auth.js.org/) - Authentication for Next.js applications.
- [React Pro Sidebar](https://github.com/azouaoui-med/react-pro-sidebar) - React component for sidebar navigation.
- [VdoCipher](https://www.vdocipher.com/) - Secure video hosting and streaming.

### Backend

- [Node.js](https://nodejs.org/) - JavaScript runtime environment.
- [MongoDB](https://www.mongodb.com/) - NoSQL database.
- [Mongoose](https://mongoosejs.com/) - ODM for MongoDB.
- [Redis](https://redis.io/) - In-memory data structure store.
- [Cloudinary](https://cloudinary.com/) - Cloud media storage service.
- [Stripe](https://stripe.com/) - Online payment processing platform.

## 📁 Running Locally

### Backend

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/agora-backend.git
   cd agora-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file and add your environment variables:
   ```env
   PORT=8000
   ORIGIN=http://localhost:3000,https://agora-client-azure.vercel.app
   ```
4. Start the server:
   ```bash
   npm run dev
   ```

### Frontend

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/agora-frontend.git
   cd agora-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env.local` file and add your environment variables:
   ```env
   NEXT_PUBLIC_SERVER_URL=http://localhost:8000/api/v1/
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## 👩‍💻 Developer

<img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/134077780?v=4" width="100px;" alt="Developer's avatar"/>

<div align="left">
  <a href="https://www.linkedin.com/in/miguel-rafael-almeida/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  </a>
</div>
