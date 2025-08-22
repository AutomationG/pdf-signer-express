# PDF Signer — Client

A lightweight web app for uploading and digitally signing PDF documents.

## Deployment on Vercel
https://pdf-signer-react.vercel.app/

## Features
- Upload in-browser pdf
- Export signed PDFs for download or prview

## Tech stack
- React (UI)
- TypeScript (type safety)
- Vite (build + dev server)
- Tailwind CSS (styling)
- axios(HTTP requests to backend API)
- Node
- express(Node webserver)

## Prerequisites
- Node.js (22.12+)
- npm or yarn

## Quick start client
1. Open terminal and go to the client folder:
  - cd pdf-signer/client
2. Install dependencies:
  - npm install
  - or yarn
3. Add .env file in /client. Add VITE_API_BASE_URL=http://localhost:4000
4. Run in development:
  - npm run dev 
  - or yarn dev
  - open app in browser
5. Build for production:
  - npm run build
  - npm run Preview

## Quick start sever
1. Open terminal and go to the server folder:
  - cd pdf-signer/sever
2. Install dependencies:
  - npm install
  - or yarn
3. Add .env file in /server. Add CORS_ORIGIN=http://localhost:5173 PORT=4000
4. Run in development:
  - npm run start 
  - or yarn dev

## To Open in web browser
1. Run client
2. Run Server
3. Open http:localhost:5173 on browser

## To Open in mobile browser
1. Run client
2. Run Server with npm run devmobile
3. Uncomment in vite.config.ts
  // server: {
  //   host: true,
  //   port: 5173,
  //   proxy: {
  //     '/api': { target: 'http://localhost:4000', changeOrigin: true }
  //   }
  // }
4. Find IPv4 of your system: ipconfig on windows/ifconfig on MacOS
5. Open http:/<IP>:5173 on mobile browser

# Enhancements
1. Add Unit testing
2. Upgrade the current visible stamp-based PDF signing to use cryptographic digital signatures
3. Yarn 4 as Package Manager
