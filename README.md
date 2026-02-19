# LIFE UNFILTERED - Movie Landing Page

A premium, responsive movie landing page built with **Vite** and **Vanilla JavaScript**. This project features a modern design with a dark aesthetic, interactive elements, and a multi-page layout including a login screen.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on all devices (Desktop, Tablet, Mobile).
- **Modern UI/UX**: utilizing a dark-themed, neon-noir aesthetic with smooth transitions and hover effects.
- **Multi-page Navigation**: Includes a Home page (with sections for Trending, Top Picks, Synopsis, Cast, Gallery, Reviews) and a Login/Signup page.
- **Login/Signup Flow**: Mock authentication flow using `localStorage`.
- **Verified Deployment**: Configured for deployment on Vercel with clean URLs.

## 🛠️ Tech Stack

- **Frontend Framework**: [Vite](https://vitejs.dev/) (Vanilla JS template)
- **Languages**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS (Variables, Flexbox, Grid)
- **Icons**: FontAwesome

## ⚙️ Setup & Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/basavanagowda31/movie-landing-page.git
    cd movie-landing-page
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Run the development server**
    ```bash
    npm run dev
    ```
    The app will run at `http://localhost:5173/`.

4.  **Build for production**
    ```bash
    npm run build
    ```
    The output will be in the `dist/` directory.

## 🚀 Deployment

### Vercel

This project includes a `vercel.json` configuration for easy deployment.

1.  Push your changes to GitHub.
2.  Import the repository into Vercel.
3.  Vercel will automatically detect Vite.
4.  Deploy!

## 📂 Project Structure

```
movie-landing-page/
├── public/              # Static assets (images, icons)
├── src/
│   ├── main.js          # Main JavaScript logic
│   └── style.css        # Global styles
├── index.html           # Home page
├── login.html           # Login/Signup page
├── package.json         # Project dependencies and scripts
├── vite.config.js       # Vite configuration
└── vercel.json          # Vercel deployment config
```

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
