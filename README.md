# Trainer Card Builder

A Next.js app for building Pokemon trainer cards with a complete Pokedex of 1,025+ Pokemon including all forms and variations.

## Quick Start

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```

3. **Open your browser:**
   Navigate to [http://localhost:3000](http://localhost:3000)

## Features

- **Complete Pokedex**: All 1,025+ Pokemon with forms and variations
- **Team Builder**: Create teams of up to 6 Pokemon
- **Species Selection**: Dropdown with formatted Pokemon names
- **Nickname Support**: Custom nicknames for each team member
- **Shiny Toggle**: Mark Pokemon as shiny variants
- **TypeScript**: Full type safety throughout the app
- **Tailwind CSS**: Modern, responsive styling

## Project Structure

```
src/
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   ├── page.tsx          # Landing page
│   └── builder/
│       └── page.tsx      # Team builder page
├── components/
│   └── TeamBuilder.tsx   # Main team building component
├── data/
│   └── pokemon.ts        # Complete Pokemon database
└── types/
    └── team.ts           # TypeScript type definitions
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Technologies

- Next.js 14 (App Router)
- React 18
- TypeScript
- Tailwind CSS
- ESLint