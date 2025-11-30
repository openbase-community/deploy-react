# Deploy React Action

This GitHub Action builds and deploys a React website to Amazon S3. It handles checking out both the app repository and a core React repository, building the application, and deploying it to S3.

## Features

- Checks out both the app repository and react-core repository
- Sets up Node.js environment
- Installs dependencies
- Builds the React application using Vite
- Deploys the built files to S3 with public-read access
