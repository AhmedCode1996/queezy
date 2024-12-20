# Quiz Master - Interactive Learning Platform

## Overview

Quiz Master is a dynamic Next.js application that provides an interactive quiz platform with multiple categories, difficulty levels, and real-time scoring. Built with modern web technologies and The Trivia API integration.

## Features

- Multiple quiz categories (History, Science, Sports, etc.)
- Difficulty levels (Easy, Medium, Hard)
- Real-time scoring system
- Progress tracking
- Mobile-responsive design
- Leaderboard functionality
- User authentication
- Performance analytics

## Tech Stack

- **Frontend**: Next.js 15, React, TailwindCSS
- **Backend**: Next.js API Routes
- **Database**: MongoDB/PostgreSQL
- **Authentication**: NextAuth.js
- **API**: The Trivia API
- **Styling**: Tailwind CSS
- **State Management**: React Context/React Query

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm/yarn
- MongoDB/PostgreSQL instance

### Installation

```bash
# Clone the repository
git clone https://github.com/AhmedCode1996/queezy.git

# Navigate to project directory
cd queezy

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Run development server
npm run dev
```

### Environment Variables

```plaintext
DATABASE_URL=your_database_url
NEXTAUTH_SECRET=your_auth_secret
TRIVIA_API_KEY=your_api_key
```

## Project Structure

```
quiz-master/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── [...routes]
├── components/
│   ├── ui/
│   └── quiz/
├── lib/
├── public/
└── types/
```

## API Routes

- `GET /api/questions`: Fetch quiz questions
- `POST /api/submit`: Submit quiz answers
- `GET /api/leaderboard`: Get leaderboard data
- `POST /api/auth/*`: Authentication endpoints

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## License

MIT License - see LICENSE.md

## Contact

- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

## Acknowledgments

- The Trivia API for providing question database
- Next.js team for the amazing framework
- All contributors and supporters
