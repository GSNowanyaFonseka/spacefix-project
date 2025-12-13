# SpaceFix Project

A modern, responsive web application built with React and Vite, styled with Tailwind CSS and integrated with Firebase backend services.

## Live Demo

The application is deployed and accessible at: [https://spacefix-project.vercel.app/](https://spacefix-project.vercel.app/)

## Technology Stack

- **Frontend Framework:** React 18.3.1
- **Build Tool:** Vite 6.0.5
- **Styling:** Tailwind CSS 4.0.3
- **Routing:** React Router DOM 7.1.5
- **Backend Services:** Firebase 11.2.0
- **Icons:** Lucide React & React Icons
- **Code Quality:** ESLint

## Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager
- Firebase account and project configuration

## Installation

1. Clone the repository:
```bash
git clone https://github.com/sandewdinowanya/spacefix-project.git
cd spacefix-project
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables: 

Create a `.env` file in the root directory with your Firebase configuration:
```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

## Development

### Available Scripts

**Start Development Server**
```bash
npm run dev
```
Launches the development server with hot module replacement enabled.

**Build for Production**
```bash
npm run build
```
Generates an optimized production build in the `dist` directory.

**Preview Production Build**
```bash
npm run preview
```
Serves the production build locally for testing before deployment.

**Code Linting**
```bash
npm run lint
```
Runs ESLint to analyze code quality and identify potential issues.

## Project Structure

```
spacefix-project/
├── public/          # Static assets and files
├── src/             # Application source code
│   ├── components/  # React components
│   ├── pages/       # Application pages
│   └── ... 
├── index.html       # HTML entry point
├── vite. config.js   # Vite configuration
├── eslint.config.js # ESLint configuration
├── package.json     # Dependencies and scripts
└── . gitignore       # Git ignore rules
```

## Key Features

- High-performance development environment powered by Vite
- Modern, utility-first styling with Tailwind CSS
- Firebase integration for authentication and data management
- Responsive design for cross-device compatibility
- Client-side routing with React Router
- Comprehensive icon library support

## Deployment

This project is configured for deployment on Vercel. The production build is automatically generated from the main branch. 

## Contributing

Contributions are welcome.  Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Author

**sandewdinowanya**
- GitHub: [@sandewdinowanya](https://github.com/sandewdinowanya)
- Repository: [https://github.com/sandewdinowanya/spacefix-project](https://github.com/sandewdinowanya/spacefix-project)

## Contact

For questions, issues, or suggestions, please open an issue in the GitHub repository. 
```
