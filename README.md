# TypeScript Node.js Template

A modern TypeScript Node.js project template with essential development tools pre-configured.

## 🚀 Features

- **TypeScript** - Type-safe JavaScript with modern features
- **ESLint + Prettier** - Code linting and formatting
- **Vitest** - Fast testing framework
- **Husky + lint-staged** - Git hooks for code quality
- **PNPM** - Fast, efficient package manager

## 📦 What's Included


### Configuration Files
- `tsconfig.json` - TypeScript configuration
- `eslint.config.mts` - ESLint configuration with TypeScript support
- `package.json` - Project scripts and dependencies
- `.gitignore` - Git ignore patterns

## 🛠 Usage

### Using as Template

1. **Create new repository from template:**
   ```bash
   # On GitHub, click "Use this template" button
   # Or clone and remove git history:
   git clone https://github.com/LiXuanqi/typescript-node-template.git my-project
   cd my-project
   ```

2. **Install dependencies:**
   ```bash
   pnpm install
   ```

3. **Update project details:**
   - Edit `package.json` name, description, author
   - Update this README.md

### Development

```bash
# Install dependencies
pnpm install

# Start development server with hot reload
pnpm dev

# Build for production
pnpm build

# Run built application
pnpm start

# Run tests
pnpm test

# Run tests once
pnpm test:run

# Lint code
pnpm lint

# Fix linting issues
pnpm lint:fix

# Format code
pnpm format

# Check formatting
pnpm format:check

# Type check
pnpm typecheck

# Clean build directory
pnpm clean
```

## 📁 Project Structure

```
├── src/
│   └── index.ts          # Main application entry
├── tests/
│   └── *.test.ts         # Test files
├── dist/                 # Build output (generated)
├── package.json          # Dependencies and scripts
├── tsconfig.json         # TypeScript configuration
├── eslint.config.mts     # ESLint configuration
└── .gitignore           # Git ignore patterns
```

## 🔧 Customization

### Adding Dependencies
```bash
# Runtime dependencies
pnpm add package-name

# Development dependencies
pnpm add -D package-name
```

### Git Hooks
Pre-commit hooks are configured to run linting and formatting automatically. Customize in `package.json` under `lint-staged`.

## 📝 Scripts

| Script | Description |
|--------|-------------|
| `dev` | Start development server with hot reload |
| `build` | Build for production |
| `start` | Run built application |
| `test` | Run tests in watch mode |
| `test:run` | Run tests once |
| `lint` | Lint code |
| `lint:fix` | Fix linting issues |
| `format` | Format code |
| `typecheck` | Type check without emitting |
| `clean` | Clean build directory |


## 📄 License

MIT
