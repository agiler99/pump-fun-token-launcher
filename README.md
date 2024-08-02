
# Pump.fun Token Launcher

This repository provides tools and scripts for programmatically launching `pump.fun` tokens. The project is set up using TypeScript and includes essential modules to facilitate token creation and management.
Some information to perform the launch transaction successfully has been redacted, contact me at t.me/guru6673 if you're interested.

For a fee you can use this bundler to launch a token with your own buys.
It contains the following features:
  - Bundle launch with up to 16 buy transactions
  - Enter mint privatekey to ensure mint ends in pump
  - Buying and Selling
  - Sell single wallet by percentage
  - Sell all wallets completely through Jito Bundle

Services are for hire, contact me at https://t.me/guru6673
## Features

- Programmatically launch `pump.fun` tokens.
- Utilities for managing token configurations.
- Easy integration into existing projects.

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or later)
- [npm](https://www.npmjs.com/)
- [TypeScript](https://www.typescriptlang.org/)

## Installation

To install the package, clone the repository and install the dependencies:

```bash
git clone https://github.com/guru6673/pump-fun-token-launcher.git
cd pump-fun-token-launcher
npm install
```

## Usage

To compile and run the scripts:

1. Configure your environment variables as instructed.
2. Compile the TypeScript files:

```bash
npx tsc
```

3. Run the compiled JavaScript file:

```bash
node example.js
```

## Project Structure

- `src/`: Contains the source code for the package.
    - `constants.ts`: Contains constant values used throughout the project.
    - `launch.ts`: Main module for launching tokens.
    - `utils.ts`: Utility functions used in the project.
- `package.json`: Project metadata and dependencies.
- `tsconfig.json`: TypeScript configuration file.
