# PIP Mode Video Player

A video player built with React and TypeScript that features Picture-in-Picture (PIP) mode with custom media controls. This project leverages media-chrome to handle player interactions and transitions between inline and floating video modes, making it user-friendly and interactive.

## Technologies

- **Vite**
- **React**
- **TypeScript**
- **Tailwind CSS**
- **Framer Motion**

## Features

- Automatically switches between inline and Picture-in-Picture mode based on scroll position.
- Play, pause, mute, fullscreen, and time tracking powered by `media-chrome`.
- Integrated animations using Framer Motion and Tailwind CSS.
- When out of view, the video floats at the bottom right corner.
- The player intelligently toggles between inline and floating modes based on user interaction.

## Running the Project

To run the project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/KruthinPatel/pip-mode.git
    cd picture-in-picture-player
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Start the development server**:

    ```bash
    npm run dev
    ```

4. **Open the app**:

    Visit `http://localhost:5173` to see the app in action.



## Project Structure

```bash
├── public/             # Public assets (e.g., videos)
├── src/
│   ├── components/     # React components
│   │   ├── VideoPlayer.tsx
│   │   ├── VideoDescription.tsx
│   │   ├── DynamicContent.tsx
│   ├── App.tsx         # Main application component
│   ├── index.css       # Tailwind CSS file
│   ├── main.tsx        # Entry point
├── package.json        # Project configuration and dependencies
└── tsconfig.json       # TypeScript configuration
```


