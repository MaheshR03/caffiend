# ☕ Caffiend

**Caffiend** is a modern, responsive coffee tracking application that helps users monitor their daily caffeine intake with intuitive data visualization and seamless user experience.

## 🌟 Features

- **Real-time Coffee Tracking**: Log your coffee consumption with timestamp precision
- **Interactive Dashboard**: Visual statistics and consumption patterns
- **User Authentication**: Secure login and personalized data management
- **Responsive Design**: Optimized for desktop and mobile devices
- **Firebase Integration**: Cloud-based data storage and synchronization
- **Modern UI**: Clean, intuitive interface built with FantaCSS

## 🚀 Live Demo

Experience the application live: [https://caffiend-coffeetracker.vercel.app/](https://caffiend-coffeetracker.vercel.app/)

## 🛠️ Technology Stack

- **Frontend**: React 18.3.1, Vite
- **Styling**: FantaCSS, CSS3
- **Backend**: Firebase (Authentication, Firestore Database)
- **Deployment**: Vercel
- **Build Tools**: Vite, ESLint

## 📷 Screenshots

### Dashboard Overview
<img width="1887" height="902" alt="Caffiend Dashboard - Coffee tracking interface with statistics and consumption history" src="https://github.com/user-attachments/assets/80f504f5-07c8-41e5-adc0-66bef55fefc6" />

### Coffee Logging Interface
<img width="1886" height="879" alt="Coffee logging form with time tracking and consumption details" src="https://github.com/user-attachments/assets/66356dcf-9b58-49b5-a289-5e07f8f7feb1" />

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager
- Firebase account for backend services

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MaheshR03/caffiend.git
   cd caffiend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Authentication and Firestore Database
   - Copy your Firebase configuration to `firebase.js`

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 📁 Project Structure

```
caffiend/
├── public/                 # Static assets
├── src/
│   ├── components/        # React components
│   │   ├── Authentication.jsx
│   │   ├── CoffeeForm.jsx
│   │   ├── Hero.jsx
│   │   ├── History.jsx
│   │   ├── Layout.jsx
│   │   ├── Modal.jsx
│   │   └── Stats.jsx
│   ├── context/          # React context providers
│   │   └── AuthContext.jsx
│   ├── utils/            # Utility functions
│   ├── App.jsx           # Main application component
│   └── main.jsx          # Application entry point
├── firebase.js           # Firebase configuration
└── package.json          # Project dependencies
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - UI library
- [Firebase](https://firebase.google.com/) - Backend services
- [Vite](https://vitejs.dev/) - Build tool
- [FantaCSS](https://fanta.vercel.app/) - CSS framework
