# Zentartika Local Development Setup

## Prerequisites

1. Install Node.js (v18 or later)
   - Visit https://nodejs.org
   - Download and install the LTS version

2. Install Git
   - Visit https://git-scm.com/download/mac
   - Download and install the latest version

## Setup Steps

1. Clone the repository:
```bash
git clone <your-repo-url>
cd zentartika
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. View the application:
   - Open your browser to the URL shown in the terminal (typically http://localhost:5173)
   - The page will automatically reload when you make changes

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## Development Tools

For the best development experience, we recommend:

- VS Code with these extensions:
  - ESLint
  - Prettier
  - Tailwind CSS IntelliSense
  - TypeScript Vue Plugin (Volar)

## Project Structure

```
zentartika/
├── src/                    # Source files
│   ├── components/         # React components
│   ├── App.tsx            # Main App component
│   └── main.tsx           # Entry point
├── public/                 # Static assets
├── index.html             # HTML template
└── package.json           # Project configuration
```