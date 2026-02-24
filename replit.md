# Luo Film

A React-based streaming platform frontend built with Vite, TypeScript, and Firebase.

## Project Structure

- `src/` - All frontend source code
  - `pages/` - Page components (Index, Watch, Movies, Series, TVChannel, LiveSport, Agent, AgentWatch, AudiencePage, SharedContent, AdminDashboard, SectionPage, HowToUse, NotFound)
  - `components/` - Reusable UI components
  - `contexts/` - React context providers (AuthContext)
  - `hooks/` - Custom React hooks
  - `lib/` - Firebase config and services
  - `data/` - Static data files
- `public/` - Static assets

## Tech Stack

- **Frontend**: React 18, TypeScript, Vite 5
- **Routing**: React Router DOM v6
- **Auth & Database**: Firebase (Auth + Firestore) — config hardcoded in `src/lib/firebase.ts`
- **UI**: Tailwind CSS, shadcn/ui (Radix UI), lucide-react
- **State/Data**: TanStack React Query v5
- **Video**: ArtPlayer, HLS.js, Shaka Player
- **PWA**: vite-plugin-pwa
- **Forms**: react-hook-form + zod

## Running the App

The workflow "Start application" runs `npm run dev` on port 5000.

## Firebase Project

Project ID: `luo-film`
Auth domain: `luo-film.firebaseapp.com`

## Notes

- This is a frontend-only app — no Express backend
- Firebase credentials are hardcoded in `src/lib/firebase.ts`
- Port changed from 8080 to 5000 for Replit webview compatibility
