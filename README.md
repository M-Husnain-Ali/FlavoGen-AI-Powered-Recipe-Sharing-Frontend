# FlavoGen Frontend – AI-Powered Recipe Sharing Platform

## Overview
This is the frontend repository for FlavoGen, an innovative recipe-sharing platform. Built with React.js, it provides a modern and intuitive user interface for recipe sharing and discovery. The frontend communicates with our [Django backend](https://github.com/M-Husnain-Ali/FlavoGen-AI-Powered-Recipe-Sharing-Backend) to deliver a full-featured recipe sharing experience.

## **Key Features**

### 🛡 **User Authentication**
- Secure **registration and login** system
- **Access control** ensures only registered users can interact with the platform

### 📖 **Recipe Management**
- **Create, share, and manage** your favorite recipes
- **Browse and explore** a diverse collection of user-submitted recipes
- **User-friendly recipe submission form** for seamless uploads

### 🔥 **User Engagement**
- **Rate and comment** on recipes to share feedback
- **Bookmark favorite recipes** for quick access
- **Submit feedback** via a dedicated form for continuous improvement

### 🧠 **Smart Search & AI Assistance**
- **Advanced search functionality** for easy recipe discovery
- **AI-powered chatbot** for instant recipe recommendations and cooking tips

### 🎛 **Admin Dashboard**
- Comprehensive **user and content management** for platform moderation

### 🎨 User Interface
- Modern, responsive design
- Intuitive navigation with React Router
- Interactive recipe cards and detailed views
- Real-time search functionality
- Mobile-friendly layout

### 👤 User Features
- User registration and login interface
- Profile management dashboard
- Recipe creation and management
- Bookmark system for favorite recipes
- Rating and commenting system

### 🤖 AI Integration
- Interactive chatbot interface
- Real-time recipe recommendations
- Cooking assistance features
- Smart search suggestions

### 📱 Components
- Responsive navigation bar
- Dynamic recipe cards
- Interactive forms for recipe submission
- User profile components
- Feedback submission system
- Privacy policy page

## Tech Stack
- React.js
- React Router for navigation
- Modern CSS with responsive design
- Axios for API communication
- Environment variable configuration

## Getting Started

### Prerequisites
- Node.js (v14 or above)
- npm
- Access to [FlavoGen Backend](https://github.com/M-Husnain-Ali/FlavoGen-AI-Powered-Recipe-Sharing-Backend)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Recipe_Sharing_Frontend.git
   cd Recipe_Sharing_Frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```
### Running the App
```bash
npm start
```
The app will run at [http://localhost:3000](http://localhost:3000)

## Project Structure
```
src/
  components/           # Reusable UI components
    ├── Navbar/        # Navigation components
    ├── Footer/        # Site footer
    ├── Profile/       # User profile components
    ├── UpperNav/      # Upper navigation bar
    └── LoginMenu/     # Login-related components
  
  screens/             # Main application screens
    ├── Login/         # Authentication screens
    ├── Signup/        # User registration
    ├── Home/          # Homepage
    ├── AddRecipe/     # Recipe creation
    ├── MainRecipe/    # Recipe details
    ├── Search/        # Search functionality
    ├── Bookmark/      # Bookmarked recipes
    ├── Chatbot/       # AI assistant interface
    └── FeedbackForm/  # User feedback

  services/
    └── APIservices.js # Backend API integration

  App.js              # Main application component
  index.js            # Application entry point

Sequence and Design Class Diagram/
  ├── *.jpg           # Sequence and class diagrams (image format)
  └── Xml file/*.xml  # Sequence and class diagrams (draw.io XML format)
```

## Sequence and Class Diagrams

The `Sequence and Design Class Diagram` folder contains detailed diagrams illustrating the application's architecture and workflows. Each diagram is available in both image (`.jpg`) and editable draw.io (`.xml`) formats:

- **Design Class Diagram**: Overview of the main classes and their relationships
- **Add Recipe**: Sequence for adding a new recipe
- **Add Review**: Sequence for submitting a review
- **Bookmark Recipe**: Sequence for bookmarking a recipe
- **Manage User Generated Content**: Moderation and management flow
- **Rate Recipe**: Sequence for rating a recipe
- **Recipe Recommendation**: AI-powered recommendation flow
- **Search Recipe**: Sequence for searching recipes
- **Share Recipe**: Sequence for sharing a recipe
- **User Management**: User registration, login, and profile management
- **View Recipe**: Sequence for viewing recipe details

You can open the `.xml` files in [draw.io](https://app.diagrams.net/) for editing or export.

## API Integration
The frontend communicates with the backend through `src/screens/APIservices.js`. Key integrations include:
- User authentication
- Recipe CRUD operations
- Search functionality
- AI chatbot communication
- User interactions (bookmarks, ratings, comments)

## Available Scripts
- `npm start`: Run development server
- `npm build`: Build for production
- `npm test`: Run tests
- `npm eject`: Eject from Create React App

## Backend Integration
This frontend is designed to work with the [FlavoGen Backend](https://github.com/M-Husnain-Ali/FlavoGen-AI-Powered-Recipe-Sharing-Backend). Ensure the backend is properly set up and running before starting the frontend application.

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
[MIT](LICENSE)

## Support
For frontend-specific issues, please open an issue in this repository. For backend-related questions, visit our [backend repository](https://github.com/M-Husnain-Ali/FlavoGen-AI-Powered-Recipe-Sharing-Backend).
