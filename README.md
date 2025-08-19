# WebGame-UI

## Overview

WebGame-UI is a monorepo for web-based game user interfaces. It currently contains a React application built with TypeScript, located in the `react-app` directory.

## Project Structure

- `react-app/` — Main React application (TypeScript)
- `.github/workflows/ci.yml` — GitHub Actions workflow for automated testing

## Getting Started

To start developing or running the React app:

```bash
cd react-app
npm install
npm start
```

This will launch the app in development mode at [http://localhost:3000](http://localhost:3000).

## Running Tests

To run the test suite locally:

```bash
cd react-app
npm test
```

## Continuous Integration

All pull requests to the `main` branch will automatically trigger the GitHub Actions workflow to install dependencies and run the test suite. See `.github/workflows/ci.yml` for details.

## License

MIT