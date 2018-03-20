# Preact Webpack4 Minimal Starter [![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](LICENSE)

Minimal [Webpack 4](https://webpack.js.org/) / [preact](https://preactjs.com/) starter project.

This project contains the initial setup for a plain Javascript project
(including babel/eslint). It does not contain any configuration for tests
or assets handling.

## Installation

**1. Clone this repo:**

```bash
git clone --depth 1 https://github.com/code2k/preact-webpack4-minimal.git my-app
cd my-app
```

**2. Initialize your project:**

```bash
rm -rf .git && git init && yarn init
```

**3. Install dependencies:**

```bash
yarn install
```

## Usage

**Start a live-reload development server:**

```bash
yarn start
```

**Generate a production build:**

```bash
yarn build
```

**Cleanup:**

```bash
yarn clean
```
