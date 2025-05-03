# Brown Dining Hall - Composting Website

This is a website that was created for the displaying of composting data from the Brown Dining Hall at the University of Minneosta - Crookston campus.

## Prerequisites

- Node.js (v18 or higher)
- Python 3.x (for backend)
- npm (v10.2.4 or higher)

## Installation

### Frontend Setup

1. Clone the repository:
```bash
git clone https://github.com/browncomposting/BrownComposting.git
cd BrownComposting
```

2. Install dependencies:
```bash
npm install
```

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

### Start the Backend Server

1. Make sure you're in the backend directory
2. Run the backend server:
```bash
python3 inbox.py
```

### Start the Frontend Development Server

1. Open a new terminal
2. Navigate to the project root directory
3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## Important Scripts for the Terminal

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run start` - Start the production server

## Project Structure

- `/src` - Frontend source code
- `/backend` - Backend Python code
- `/public` - Static assets
- `/components` - React components
- `/pages` - Next.js pages

## Frameworks and Languages Used

- Frontend:
  - Next.js
  - React
  - TypeScript
  - Highcharts

- Backend:
  - Python
  - Flask
  - SQLite
