<div align="center">
  <img src="./public/GamesLibri_logo.svg" alt="GamesLibri Logo" width="200" height="200">
  
  # 🎮 GamesLibri
  
  **Discover Amazing Free Games**
  
  [![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://gameslibri.vercel.app/)
  [![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
  [![Vite](https://img.shields.io/badge/Vite-6.0.5-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.17-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
  
</div>

## 📖 About

GamesLibri is a modern, responsive web application built with React that helps gaming enthusiasts discover and explore an extensive collection of free-to-play games. With an intuitive interface and powerful search capabilities, users can easily browse games by categories, search for specific titles, and find detailed information about each game.

## ✨ Features

- 🎯 **Comprehensive Game Discovery** - Browse thousands of free games from various genres
- 🔍 **Advanced Search & Filtering** - Find games by title, genre, or category
- 📱 **Responsive Design** - Seamless experience across desktop and mobile devices
- 🏷️ **Category Navigation** - Explore games organized by genres
- ⚡ **Fast Performance** - Built with Vite for lightning-fast load times
- 🎨 **Modern UI/UX** - Clean and intuitive interface with Tailwind CSS
- 🔗 **Direct Game Links** - Quick access to play games on their platforms

## 🖼️ Screenshots

<div align="center">
  <img src="./public/website demo.png" alt="GamesLibri Homepage" width="800">
  <p><em>Homepage showcasing featured games and categories</em></p>
</div>

## 🚀 Quick Start

### Prerequisites

- **Node.js** (v16 or higher) - [Download here](https://nodejs.org/)
- **npm** or **yarn** package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/GovindSingh3011/GamesLibri.git
   cd GamesLibri
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   
   Navigate to `http://localhost:5173` to view the application

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `dist` directory.

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|-----------|---------|---------|
| **React** | 18.3.1 | Frontend framework |
| **Vite** | 6.0.5 | Build tool and dev server |
| **React Router** | 7.1.1 | Client-side routing |
| **Tailwind CSS** | 3.4.17 | Utility-first CSS framework |
| **Axios** | 1.7.9 | HTTP client for API requests |
| **Styled Components** | 6.1.14 | CSS-in-JS styling |

## 📁 Project Structure

```
GamesLibri/
├── public/                 # Static assets
│   ├── GamesLibri_logo.svg
│   └── website demo.png
├── src/
│   ├── components/         # React components
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   ├── Home.jsx
│   │   ├── GameCard.jsx
│   │   ├── FetchGames.jsx
│   │   ├── Search.jsx
│   │   └── ...
│   ├── assets/            # Images and static files
│   ├── App.jsx            # Main App component
│   └── main.jsx           # Entry point
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
```

## 🔧 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint for code quality |

## 🌐 API Integration

GamesLibri integrates with the [Free-to-Play Games Database API](https://rapidapi.com/digiwalls/api/free-to-play-games-database) to fetch real-time game data, including:

- Game titles and descriptions
- Genre classifications
- Screenshots and thumbnails
- Platform availability
- Release dates

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Govind Singh**
- GitHub: [@GovindSingh3011](https://github.com/GovindSingh3011)

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Vite](https://vitejs.dev/) - Next generation frontend tooling
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- [Free-to-Play Games Database API](https://rapidapi.com/digiwalls/api/free-to-play-games-database) - For providing comprehensive game data
- [Vercel](https://vercel.com/) - For seamless deployment and hosting

---

<div align="center">
  <p>Made with ❤️ by <a href="https://govindsingh.vercel.app/">Govind Singh</a></p>
  
  ⭐ Star this repository if you found it helpful!
</div>

