
<h1 align="center">GameHub</h1>

<div align="center">
  <img src="https://github.com/Shubham34928/rawggamehub/raw/main/public/vite.svg" height="50" width="50" />
</div> <br />
Welcome to the GameHub, a web application built using React, Chakra UI, React Query, Zustand, and the RAWG API. This platform allows users to explore and discover a wide range of video games, access detailed information about them, and stay up-to-date with the latest releases.

## Features

- **Explore a Vast Game Library**: The platform provides access to a vast collection of video games, including popular titles and hidden gems.

- **Search and Filter**: Easily search for specific games using the search bar, and apply filters to find games based on genres, platforms, release dates, and more.

- **Game Details**: Get detailed information about each game, including its description, release date, platforms, genres, ratings, and screenshots.

- **Responsive Design**: The platform is built with a mobile-first approach, ensuring an optimal user experience across various devices and screen sizes.

## Installation

To set up the GameHub locally, follow these steps:

1. Clone this repository to your local machine.

```bash
git clone https://github.com/Shubham34928/rawggamehub
cd game-hub
```

2. Install the dependencies using npm or yarn.

```bash
npm install
```

3. Obtain an API key from the RAWG API website (https://rawg.io/apidocs) and add it to the environment variables.

```bash
cp .env.example .env
```


4. Start the development server.

```bash
npm start
```

The application will be accessible at `http://localhost:3000`.



## License

The Game Discovery Platform is open-source and licensed under the [MIT License](LICENSE.md).

---

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

