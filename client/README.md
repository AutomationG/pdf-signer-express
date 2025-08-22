# PDF Signer — Client

A lightweight web client for uploading, previewing and digitally signing PDF documents before downloading or sending them to a backend signing service.

## Features
- Upload and preview PDFs in-browser
- Add freehand or image-based signatures
- Position, resize and remove signature elements
- Export signed PDFs for download or upload to a server

## Tech stack
- React (UI)
- TypeScript (type safety)
- Vite (build + dev server)
- Tailwind CSS (styling)
- pdf-lib (client-side PDF manipulation)
- axios or fetch (HTTP requests to backend API)

## Prerequisites
- Node.js (22.12+)
- npm or yarn

## Quick start
1. Open terminal and go to the client folder:
  - cd /d:/Gargi/Projects/Assignments/pdf-signer/client
2. Install dependencies:
  - npm install
  - or yarn
3. Create environment file (if required):
  - Copy `.env.example` to `.env.local` and set API URL, e.g. `VITE_API_URL=http://localhost:5000`
4. Run in development:
  - npm run dev
  - or yarn dev
5. Build for production:
  - npm run build
6. Preview production build (optional):
  - npm run preview

## Environment
- VITE_API_URL — base URL of the backend API used for server-side signing or storage.

## Testing
- If tests exist:
  - npm run test

