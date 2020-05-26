# Anchor Digital

This is the source code for Anchor Digital's homepage currently hosted at <https://anchordigital.io>.

## Getting Started

This is meant to be a simple and static website so that load times are fast and optimized for search engines. Whenever server-side rendering features are required PHP should be implemented. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
NodeJS + NPM
```

### Installing & Development

```
npm install
npm run dev or npm run watch
```

## Deployment

The only necessary files for production in a live server are located inside the `public` directory. Any other file or directory is meant to be used for development only. The code must be compiled in production mode before proceeding to upload the files.

```
npm run prod
```