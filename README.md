# Space Viewer

A Next.js application for viewing space-related images and data from NASA APIs. This project provides an interactive interface to explore astronomical images, search for specific content, and view detailed information about space phenomena.

## Features

- **NASA Image Search**: Search and browse through NASA's extensive collection of space images
- **Interactive Gallery**: View images in a responsive grid layout
- **Image Modal**: Click on images to view them in full detail with metadata
- **Search Functionality**: Filter images by keywords and dates
- **Responsive Design**: Optimized for desktop and mobile devices

## Tech Stack

- **Framework**: Next.js 16
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: React components with custom styling
- **API**: NASA Images API

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Othman-Nazrhan/space-viewer.git
cd space-viewer
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
space-viewer/
├── app/
│   ├── layout.tsx          # Root layout component
│   ├── page.tsx            # Main page component
│   └── globals.css         # Global styles
├── components/
│   ├── ImageCard.tsx       # Individual image card component
│   ├── ImageModal.tsx      # Modal for viewing full-size images
│   └── SearchBar.tsx       # Search input component
├── lib/
│   └── fetchNASA.ts        # NASA API integration utilities
├── public/                 # Static assets
└── package.json            # Project dependencies and scripts
```

## API Usage

This application uses NASA's Images API to fetch space-related images. The API integration is handled in `lib/fetchNASA.ts`, which provides functions for searching and retrieving image data.

## Development

- **Linting**: Run `npm run lint` to check code quality
- **Building**: Run `npm run build` to create a production build
- **Starting**: Run `npm run start` to start the production server

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- NASA for providing the Images API
- Next.js team for the excellent framework
- Vercel for hosting and deployment platform
