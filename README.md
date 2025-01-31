# @wonse/tsconfig

Shareable TypeScript configurations for various environments.

## Installation

```bash
# npm
npm install --save-dev @wonse/tsconfig

# yarn
yarn add -D @wonse/tsconfig

# pnpm
pnpm add -D @wonse/tsconfig
```

## Usage

### Base Configuration

The base configuration provides sensible defaults for TypeScript projects. Extend it in your `tsconfig.json`:

```json
{
  "extends": "@wonse/tsconfig/tsconfig-base.json"
}
```

### React Configuration

For React projects, use the React-specific configuration:

```json
{
  "extends": "@wonse/tsconfig/tsconfig-react.json"
}
```

### Node.js Configuration

For Node.js projects, use the Node.js-specific configuration:

```json
{
  "extends": "@wonse/tsconfig/tsconfig-node.json"
}
```

## Features

- **Base Configuration**: Strict type checking and modern JavaScript features
- **React Configuration**: React and JSX support with modern module resolution
- **Node.js Configuration**: Node.js-specific settings with ESM support

## License

MIT © [Wonse Shin](https://github.com/shinwonse) 