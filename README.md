# GitHub Finder

A simple React website to find GitHub accounts by username using the GitHub API.

## Learning Objectives
This project was developed following the **"Modern React From The Beginning"** course by Brad Traversy. The primary goal was to move from fundamental concepts to building a functional, real-world application.

# Features:
- Search user by login
- Dropdown filtering
- Recent searches (saved to localstorage)
- TypeScript & TanStack Query

## Tech Stack
- **Frontend:** React.js (Vite)
- **Language:** TypeScript
- **Data Fetching:** TanStack Query (React Query)
- **Styling:** CSS
- **API:** GitHub REST API

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shadman2503/GitHub-Finder

2. **Install dependencies:**
   ```bash
   npm install

3. Create a .env file in the root directory and add the following:
  ```bash
  VITE_GITHUB_API_URL=https://api.github.com
  ```
  # Optional: Add a token to increase rate limits
  ```bash
  VITE_GITHUB_TOKEN=your_personal_access_token_here
  ```
4. **Start the development server:**
   ```bash
   npm run dev

## Credits

- **Brad Traversy** – Course Instructor  
- Course: *Modern React From The Beginning*
- Original Repository: https://github.com/bradtraversy/github-finder-tanstack-query
