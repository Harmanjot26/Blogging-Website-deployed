# 📝 Blogging Website

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)

> A modern, responsive blogging platform built with cutting-edge web technologies

## ✨ Features

🎨 **Modern Design** - Clean, minimalist interface with responsive layout  
📱 **Mobile First** - Optimized for all devices and screen sizes  
⚡ **Fast Performance** - Lightning-fast loading times and smooth interactions  
🔍 **SEO Optimized** - Built-in SEO best practices for better search rankings  
📊 **Analytics Ready** - Easy integration with Google Analytics and other tools  
🔒 **Secure** - Built with security best practices in mind  
💬 **Comments System** - Engage with your readers through built-in comments  
🏷️ **Tag System** - Organize your content with intuitive tagging  
📝 **Rich Editor** - Powerful markdown editor with live preview  
🌙 **Dark Mode** - Eye-friendly dark theme support  

## 🚀 Quick Start

### Prerequisites

Make sure you have the following installed:
- Node.js (v16 or higher)
- npm or yarn
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Blogging-Website-deployed.git
   cd Blogging-Website-deployed
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   ```
   http://localhost:3000
   ```

## 🏗️ Project Structure

```
📦 Blogging-Website-deployed
├── 📁 api/                 # Backend API routes
├── 📁 client/              # Frontend React application
├── 📁 uploads/             # Media uploads directory
├── 📄 package.json         # Project dependencies
├── 📄 package-lock.json    # Lock file
├── 📄 yarn.lock           # Yarn lock file
├── 📄 .gitignore          # Git ignore rules
└── 📄 README.md           # You are here!
```

## 🛠️ Built With

- **Frontend**: React.js, HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB / PostgreSQL
- **Authentication**: JWT
- **Styling**: Tailwind CSS / Styled Components
- **Deployment**: Vercel / Netlify / Heroku

## 📱 Screenshots

### Desktop View
![Desktop Screenshot](https://via.placeholder.com/800x400/4f46e5/ffffff?text=Desktop+View)

### Mobile View
![Mobile Screenshot](https://via.placeholder.com/400x600/06b6d4/ffffff?text=Mobile+View)

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
# Database
DATABASE_URL=your_database_url
MONGODB_URI=your_mongodb_connection_string

# Authentication
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRE=30d

# Email Service
EMAIL_SERVICE=gmail
EMAIL_USERNAME=your_email@gmail.com
EMAIL_PASSWORD=your_app_password

# Cloudinary (for image uploads)
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

## 📚 API Documentation

### Authentication Endpoints
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout

### Blog Endpoints
- `GET /api/posts` - Get all posts
- `GET /api/posts/:id` - Get single post
- `POST /api/posts` - Create new post
- `PUT /api/posts/:id` - Update post
- `DELETE /api/posts/:id` - Delete post

## 🚀 Deployment

### Deploy to Vercel

1. Install Vercel CLI
   ```bash
   npm i -g vercel
   ```

2. Deploy
   ```bash
   vercel --prod
   ```

### Deploy to Netlify

1. Build the project
   ```bash
   npm run build
   ```

2. Deploy the `build` folder to Netlify

## 🤝 Contributing

Contributions are what make the open source community amazing! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Harmanjot26**
- GitHub: [@Harmanjot26](https://github.com/Harmanjot26)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- Thanks to all contributors who helped make this project better
- Inspiration from modern blogging platforms
- Open source community for amazing tools and libraries

## 📞 Support

If you have any questions or need help with setup, feel free to:
- Open an issue on GitHub
- Contact me on LinkedIn
- Send an email

---

<div align="center">
  <p>Made with ❤️ by Harmanjot26</p>
  <p>⭐ Star this repo if you like it!</p>
</div>
