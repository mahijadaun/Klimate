<<<<<<< HEAD
# 🌤️ Klimate – Your Ultimate Weather Companion  

**Klimate** is a modern weather web app that provides real-time weather updates and a 5-day forecast for any location. Get detailed weather insights, including temperature, wind speed, humidity, and "feels like" data. The app features an interactive temperature graph, city search functionality, and a "Favorites" section for quick access. With a sleek dark mode and essential weather details like sunrise/sunset times, wind direction, and atmospheric pressure, Klimate ensures you stay informed, no matter where you are.  

## ✨ Features  

✅ **Real-time Weather Updates** – Get instant weather conditions for any city worldwide.  
✅ **Detailed Weather Data** – View temperature, wind speed, humidity, and "feels like" data.  
✅ **Location Search** – Find weather updates for any city globally.  
✅ **Favorites Section** – Save frequently searched cities for quick access.  
✅ **Dark Mode** – Enjoy a sleek, eye-friendly UI with dark mode support.  
✅ **Hourly Temperature Graph** – Visualize temperature trends throughout the day.  
✅ **5-Day Weather Forecast** – Plan ahead with an extended forecast.  
✅ **Additional Details** – Includes sunrise/sunset times, wind direction, and atmospheric pressure.  

## 🛠️ Tech Stack  

- **Next.js** – For server-side rendering and seamless routing.  
- **React.js** – For dynamic and interactive UI components.  
- **TanStack Query** – For efficient data fetching and caching.  
- **ShadCN UI** – For a beautifully styled interface.  
- **Recharts** – For interactive weather graphs.  
- **Tailwind CSS** – For modern and responsive styling.  
- **TypeScript** – For improved type safety and maintainability.  

## 🚀 Installation  

To run **Klimate** locally, follow these steps:  

### Prerequisites  
Ensure you have the following installed:  

- **Node.js** (v16+ recommended)  
- **npm** or **yarn**  

### Steps  

1. **Clone the Repository**  
   ```sh
   git clone https://github.com/yourusername/klimate.git
   cd klimate
2. **Install Dependencies**
   ```sh
   npm install
3. **Set Up Environment Variables**
   ```sh
   NEXT_PUBLIC_OPENWEATHER_API_KEY=your_api_key_here
4. **Run the Development Server**
   ```sh
   npm run dev  # or yarn dev
The app will be available at https://bright-gnome-ebb83b.netlify.app/.


## 👤 Author  

Developed by **Mahi Jadaun** 🚀  

Feel free to **contribute**, **suggest improvements**, or **report issues**! 😊  
=======
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config({
  extends: [
    // Remove ...tseslint.configs.recommended and replace with this
    ...tseslint.configs.recommendedTypeChecked,
    // Alternatively, use this for stricter rules
    ...tseslint.configs.strictTypeChecked,
    // Optionally, add this for stylistic rules
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config({
  plugins: {
    // Add the react-x and react-dom plugins
    'react-x': reactX,
    'react-dom': reactDom,
  },
  rules: {
    // other rules...
    // Enable its recommended typescript rules
    ...reactX.configs['recommended-typescript'].rules,
    ...reactDom.configs.recommended.rules,
  },
})
```
>>>>>>> c662712 (Initial commit)
