# PostMortemPro

PostMortemPro is a Next.js web app that helps generate structured incident post-mortem reports from brief incident details. It is designed for hospitality-style incident analysis and produces sections such as executive summary, timeline, root cause analysis, what worked, what failed, and a prevention plan.

## Features

- Incident detail form for quick report input
- AI-generated post-mortem report
- 5-Why root cause analysis format
- Prevention plan ordered by priority
- Clean editorial-style report layout
- Built with Next.js, React, TypeScript, Tailwind CSS, and Gemini API

## Project Structure

```text
PostMortemPro/
  app/
    api/generate/route.ts
    globals.css
    layout.tsx
    page.tsx
  package.json
  tailwind.config.js
  tsconfig.json
```

## Requirements

- Node.js 24 or later
- npm
- Gemini API key

## Setup

Clone the repository:

```bash
git clone https://github.com/Adarsh-afk661/PostMortemPro.git
cd PostMortemPro/PostMortemPro
```

Install dependencies:

```bash
npm install
```

Create a `.env.local` file in the app folder and add your Gemini API key:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

Run the development server:

```bash
npm run dev
```

Open the app in your browser:

```text
http://localhost:3000
```

## Available Scripts

```bash
npm run dev
```

Starts the development server.

```bash
npm run build
```

Builds the app for production.

```bash
npm run start
```

Starts the production server after building.

## Environment Variables

| Variable | Description |
| --- | --- |
| `GEMINI_API_KEY` | API key used to call the Gemini generate content API |

## Tech Stack

- Next.js
- React
- TypeScript
- Tailwind CSS
- Lucide React
- Gemini API

## License

This project is for learning and development purposes.
