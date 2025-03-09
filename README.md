# TWIST2 - Metin2 Server

Welcome to TWIST2, a Metin2 server where players can register and log in using the latest web3 technologies.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Dependencies](#dependencies)
- [DevDependencies](#devdependencies)

## Installation

To get started with the project, follow these steps:

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/homepage1.git
   cd homepage1
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

## Usage

To start the development server, run:

```sh
npm start
```

If you encounter issues with OpenSSL, you can use the legacy OpenSSL provider:

```sh
npm run start:legacy
```

## Scripts

- `start`: Starts the development server.
- `build`: Builds the app for production.
- `test`: Runs the test suite.
- `eject`: Ejects the app from Create React App configuration.
- `start:legacy`: Starts the development server using the legacy OpenSSL provider.

## Dependencies

- `react`: ^17.0.2
- `react-dom`: ^17.0.2
- `react-scripts`: 4.0.3
- `web3`: ^1.3.6

## DevDependencies

- `autoprefixer`: ^10.2.6
- `postcss`: ^8.3.5
- `tailwindcss`: ^2.2.4
