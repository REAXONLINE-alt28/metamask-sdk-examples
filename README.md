wallet app reax online# MetaMask SDK Examples Monorepo

This monorepo contains various example applications demonstrating the integration of MetaMask SDK across different frameworks and platforms. Built with Turborepo for efficient development and build processes.

## 🚀 Getting Started

Clone and install dependencies:

```sh
git clone <repository-url>
cd metamask-sdk-examples && pnpm install
```

## 📦 Repository Structure

```
metamask-sdk-examples/
├── examples/           # Example applications
│   ├── react/         # React.js integration
│   ├── next/          # Next.js integration
│   ├── vue/           # Vue.js integration
│   └── vanilla/       # Vanilla JavaScript integration
├── packages/          # Shared configurations and utilities
│   ├── eslint-config/ # Shared ESLint configurations
│   └── tsconfig/     # Shared TypeScript configurations
```

## 🎯 Available Examples

Each example in the `examples/` directory demonstrates MetaMask SDK integration in different frameworks and scenarios:

- **React Example**: Modern React application showcasing hooks and components
- **Next.js Example**: Server-side rendering and static site generation
- **Vue Example**: Vue.js integration example
- **Vanilla JS**: Pure JavaScript implementation without frameworks

## 🛠 Development

### Running Individual Examples

To run a specific example:

```sh
cd examples/<example-name>
pnpm dev
```

### Adding New Examples

1. Create a new directory in `examples/`
2. Copy the example template (if available)
3. Implement the MetaMask SDK integration
4. Update this README with the new example details

## 🔧 Technical Stack

- **Build System**: Turborepo
- **Package Manager**: pnpm
- **Language**: TypeScript
- **Linting**: ESLint
- **Formatting**: Prettier

## 📚 Documentation

Each example includes its own README with:
- Specific setup instructions
- Implementation details
- Best practices
- Common issues and solutions

## 🤝 Contributing

We welcome contributions! To add a new example:

1. Fork the repository
2. Create a new branch
3. Add your example
4. Submit a pull request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🔗 Useful Links

- [MetaMask SDK Documentation](https://docs.metamask.io/sdk/)
- [Turborepo Documentation](https://turbo.build/repo/docs)
- [Report Issues](https://github.com/MetaMask/metamask-sdk-examples/issues)
