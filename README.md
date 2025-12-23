<br />
<p align="center">
  <a href="https://github.com/rocktimsaikia/anime-chan">
    <img src="./public/animechan-logo.png" alt="Logo" width="200" height="200">
  </a>
  <h3 align="center">Animechan</h3>
  <p align="center">
    <a href="https://github.com/Animechan-API/animechan/discussions/65">Anime request</a>
    |
    <a href="https://github.com/Animechan-API/animechan/issues">Bug report</a>
    |
    <a href="https://github.com/Animechan-API/animechan/issues">Feature request</a>
  </p>
</p>

## About

Animechan is an anime quotes and information API service that provides developers with access to a vast curated collection of anime content. Our API delivers episode counts, detailed show summaries, character information, and memorable quotes from thousands of anime series.

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

- Node.js (Latest LTS recommended)
- [pnpm](https://pnpm.io/) installed

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AnimechanOrg/animechan.git
cd animechan
```

2. Install dependencies:
```bash
pnpm install
```

3. Set up environment variables:
Copy `.env.example` to `.env` and fill in the required keys.
```bash
cp .env.example .env
```

### Usage

To run the development server:
```bash
pnpm dev
```

To build for production:
```bash
pnpm build
pnpm start
```

### Formatting

This project uses [Biome](https://biomejs.dev/) for formatting and linting.
```bash
pnpm format
```

> **Note**: This repository contains the frontend codebase for the Animechan project. The backend codebase is private.

## License

[MPL-2.0 license](./LICENSE) © 2025 [Rocktim Saikia](https://rocktim.dev)
