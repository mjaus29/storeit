# StoreIt - Modern Cloud Storage Solution with Next.js

<div align="center">
  <img src="https://www.markaustria.com/storeit.png" alt="StoreIt Demo" />

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>

## 🌐 Live Site

🚀 Here is a working live site: [storeit.markaustria.com](https://storeit.markaustria.com/)

🗒️ Check out the case study here: [markaustria.com/storeit](https://www.markaustria.com/storeit)

## 📝 Description

Welcome to StoreIt! A full-featured cloud storage application inspired by Google Drive and Dropbox using Next.js.

This project was created to demonstrate full-stack development capabilities by building a professional-grade cloud storage solution rather than creating yet another social media clone.

StoreIt addresses the universal need for secure, accessible file storage and management with modern technologies.

The application features secure passwordless authentication, comprehensive file management capabilities, real-time storage tracking, and a responsive UI that works across all devices.

**Technologies Used**: Next.js, TypeScript, Tailwind CSS, Shadcn UI, React Hook Form, Zod, Appwrite

## 📖 Table of Contents

- [Features](#-features)
- [Installation](#%EF%B8%8F-setup-project)
- [How to Contribute](#%EF%B8%8F-how-to-contribute)
- [Bug / Feature Request](#-bug--feature-request)
- [Future Enhancements](#-future-enhancements)
- [Acknowledgements](#-acknowledgements)

## ✨ Features

- **Passwordless OTP Authentication**: Secure authentication system using one-time passwords sent via email
- **Comprehensive File Management**: Upload, preview, rename, download, delete, and share files
- **Support for Various File Types**: Handle documents, images, videos, and audio files with appropriate previews
- **Real-time Storage Dashboard**: Interactive dashboard displaying storage usage statistics and file categorization
- **Global Search Functionality**: Efficient search across all file types with debouncing
- **Responsive Design**: Optimized UI that works seamlessly across all devices

## 🛠️ Setup Project

To get this project up and running in your development environment, follow these step-by-step instructions.

### 🍴 Prerequisites

We need to install or make sure that these tools are pre-installed on your machine:

- [Git](https://git-scm.com/downloads)
- [NodeJS](https://nodejs.org/en/download/)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)

### 🚀 Install Project

1. Clone the Repository

   ```bash
   git clone https://github.com/mjaus29/storeit.git
   ```

2. Navigate into the project directory

   ```bash
   cd storeit
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Set up environment variables

   - Create a .env.local file in the root directory.
   - Add the following environment variables:

   ```
   NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
   NEXT_PUBLIC_APPWRITE_PROJECT="your-project-id"
   NEXT_PUBLIC_APPWRITE_DATABASE="your-database-id"
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION="your-users-collection-id"
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION="your-files-collection-id"
   NEXT_PUBLIC_APPWRITE_BUCKET="your-bucket-id"
   NEXT_APPWRITE_KEY="your-appwrite-api-key"
   ```

5. Start the application

   ```bash
   npm run dev
   ```

6. Open your web browser and navigate to <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> to see the project running.

7. Test the application

   Run the test suite to ensure everything is working as expected.

   ```bash
   npm test
   ```

### 🔒 ENV file

This project requires the following environment variables for configuration:

```
NEXT_PUBLIC_APPWRITE_ENDPOINT - Appwrite API endpoint
NEXT_PUBLIC_APPWRITE_PROJECT - Appwrite project ID
NEXT_PUBLIC_APPWRITE_DATABASE - Appwrite database ID
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION - Appwrite users collection ID
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION - Appwrite files collection ID
NEXT_PUBLIC_APPWRITE_BUCKET - Appwrite storage bucket ID
NEXT_APPWRITE_KEY - Appwrite API key
```

## ⚒️ How to Contribute

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

- Fork the repo
- Create a new branch (`git checkout -b improve-feature`)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (`git commit -am 'Improve feature'`)
- Push to the branch (`git push origin improve-feature`)
- Create a Pull Request

### 📩 Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/mjaus29/storeit/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/mjaus29/storeit/issues/new). Please include sample queries and their corresponding results.

### ✅ Future Enhancements

- [ ] Implement admin privileges for shared files to control who can modify sharing settings
- [ ] Add file versioning to track changes and allow reverting to previous versions
- [ ] Integrate with third-party services like Google Drive or Dropbox for file import
- [ ] Implement custom avatar selection or generation based on user initials

### 📚 Acknowledgements

Special thanks to JSM for the inspiration and guidance on this project.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>
