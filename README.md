# Ouzbourne Tutor Portfolio

Personal portfolio website of Ouzbourne Tutor, Web Developer and 2nd Year Information Systems Student.

## About

This is a modern, responsive portfolio website built with React, TypeScript, and Tailwind CSS. The application integrates Google's Gemini API for AI-powered features.

## Tech Stack

- **Frontend Framework:** React 19
- **Build Tool:** Vite
- **Styling:** Tailwind CSS
- **Language:** TypeScript
- **AI Integration:** Google Gemini API
- **Animations:** Motion (Framer Motion)
- **Icons:** Lucide React
- **PDF Generation:** jsPDF

## Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ouzbournetutor73-cyber/ouzbourne-tutor-portfolio.git
   cd ouzbourne-tutor-portfolio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   - Copy `.env.example` to `.env.local`
   - Add your Gemini API key:
     ```bash
     GEMINI_API_KEY=your_api_key_here
     ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:3000`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run preview` - Preview the production build
- `npm run clean` - Clean build artifacts
- `npm run lint` - Run TypeScript type checking

## Project Structure

```
.
├── src/               # Source code
├── index.html         # HTML entry point
├── package.json       # Dependencies and scripts
├── tsconfig.json      # TypeScript configuration
├── vite.config.ts     # Vite configuration
└── README.md          # This file
```

## Features

- Responsive design
- AI-powered interactions with Gemini API
- Modern animations
- PDF export capability
- Type-safe TypeScript codebase

## Deployment

The app is optimized for deployment. After building:

```bash
npm run build
```

The `dist/` folder contains the production-ready files.

## License

MIT

## Author

Ouzbourne Tutor
