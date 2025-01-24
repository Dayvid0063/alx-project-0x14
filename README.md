# CineSeek - Movie Discovery Platform

CineSeek is a modern web application built with Next.js, TypeScript, and Tailwind CSS that allows users to discover and explore movies.

## Features

- Responsive movie browsing interface
- Movie filtering by year and genre
- Advanced search capabilities
- Real-time movie data from MovieDatabase API
- Modern, mobile-friendly design

## Tech Stack

- Next.js 13+
- TypeScript
- Tailwind CSS
- FontAwesome Icons
- MovieDatabase API

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/dayvid0063/alx-movie-app.git
cd alx-movie-app
```

2. Install dependencies:
```bash
npm install
```

3. Create `.env.local` file and add your API key:
```
MOVIE_API_KEY=your_api_key_here
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
alx-movie-app/
├── components/
│   ├── commons/      # Reusable components
│   └── layouts/      # Layout components
├── interfaces/       # TypeScript interfaces
├── pages/           # Next.js pages
│   ├── api/         # API routes
│   └── movies/      # Movie-related pages
└── styles/          # Global styles
```

## API Documentation

### MovieDatabase API Overview
The MovieDatabase API provides comprehensive access to movie information, including titles, release dates, and genres.

### Authentication
- API Key required in headers
- Rate limits apply based on plan
- Secure API key storage in environment variables

### Endpoints
- `/titles/search`: Search movies
- `/titles/{id}`: Get movie details
- `/titles/series/{id}/episodes`: Get series episodes.

### Error Handling
- 400: Bad Request
- 401: Unauthorized
- 404: Not Found
- 429: Rate Limit Exceeded
