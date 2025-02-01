# @wonse/tsconfig

A collection of shareable TypeScript configurations optimized for various environments (React, Node.js, Next.js).

## Features

- ✨ **Strict Type Checking**: Enhanced type safety with strict mode and additional checks
- 🚀 **Modern JavaScript Support**: Latest ECMAScript features enabled
- 🎯 **Environment-Specific Optimization**: Tailored settings for each framework/environment
- 📦 **Enhanced Module Resolution**: Improved handling of imports/exports
- 🛡️ **Type Safety**: Additional type checking options for more secure code

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

The base configuration provides fundamental rules applicable to any TypeScript project.

```json
{
  "extends": "@wonse/tsconfig/tsconfig-base.json"
}
```

Key Features:

- Strict mode enabled
- Unused code/variable checks
- Source map generation
- Consistent casing enforcement
- Decorator support

### React Configuration

Optimized configuration for React projects with modern features.

```json
{
  "extends": "@wonse/tsconfig/tsconfig-react.json"
}
```

React-Specific Features:

- Full JSX support
- React 18+ compatibility
- DOM type definitions
- Optimized module resolution

### Node.js Configuration

Specialized configuration for Node.js backend projects.

```json
{
  "extends": "@wonse/tsconfig/tsconfig-node.json"
}
```

Node.js-Specific Features:

- Node.js type definitions
- CommonJS/ESM module support
- Node.js-specific module resolution

### Next.js Configuration

Optimized configuration for Next.js projects.

```json
{
  "extends": "@wonse/tsconfig/tsconfig-next.json"
}
```

Next.js-Specific Features:

- Next.js type support
- Server/Client component optimization
- Build performance settings

## Detailed Configuration

### Base Configuration Options

```json
{
  "strict": true, // Enable all strict type-checking options
  "noUnusedLocals": true, // Report errors on unused local variables
  "noUnusedParameters": true, // Report errors on unused parameters
  "noImplicitReturns": true, // Report error when not all code paths return a value
  "noFallthroughCasesInSwitch": true, // Report errors for fallthrough cases in switch
  "esModuleInterop": true, // Enable interoperability between CommonJS and ES Modules
  "skipLibCheck": true // Skip type checking of declaration files
}
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT © [Wonse Shin](https://github.com/shinwonse)
