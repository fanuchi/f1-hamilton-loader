# 🏎️ F1 Hamilton Loader

A React loading component inspired by Formula 1, featuring an animated GIF with a pulsing text effect.

## Preview

![F1 Hamilton Loader](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExbHY5Z3l1NmpqeDY1c3J2OWk3eXBmd3locDliNWZwMjJxa21jNHU0NSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/VFwnvJZ871lHlfYIBT/giphy.gif)

## Tech Stack

- React
- Vite
- SCSS
- Google Fonts (Orbitron)

## Installation

```bash
npm install
npm run dev
```

## Usage

```jsx
import F1HamiltonLoader from './F1HamiltonLoader';

// Basic usage
<F1HamiltonLoader />

// Custom text
<F1HamiltonLoader text="Loading..." />

// With conditional rendering
const [loading, setLoading] = useState(true);

{loading ? (
  <F1HamiltonLoader text="Loading..." />
) : (
  <YourContent />
)}
```

## Features

- Animated F1 sticker with transparent background
- Pulsing text animation
- Customizable loading text via props
- Orbitron font for F1 aesthetic
- Fully reusable React component

## Credits

F1 sticker GIF via [Giphy](https://giphy.com/stickers/VFwnvJZ871lHlfYIBT)

## Author

Made with ❤️ and a love for Formula 1 🏁
 by fanuchi
