# Retro SD Manager

A Chrome extension for managing SD cards for retro gaming devices.

## Features

- SD card management for retro gaming devices
- Device detection and configuration
- ROM and save file management
- Plugin system for extensibility
- Modern, responsive UI

## Development Setup

### Prerequisites

- Node.js (v16 or higher)
- npm (v7 or higher)
- Chrome browser

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/retro-sd-manager.git
   cd retro-sd-manager
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start development server:
   ```bash
   npm start
   ```

4. Load the extension in Chrome:
   - Open Chrome and navigate to `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked"
   - Select the `dist` directory

### Development Commands

- `npm start` - Start development server with hot reload
- `npm run build` - Build for production
- `npm test` - Run tests
- `npm run lint` - Run ESLint
- `npm run lint:fix` - Fix ESLint issues
- `npm run format` - Format code with Prettier
- `npm run type-check` - Run TypeScript type checking

### Project Structure

```
retro-sd-manager/
├── src/
│   ├── popup/         # Extension popup UI
│   ├── background/    # Background scripts
│   ├── content/       # Content scripts
│   ├── components/    # React components
│   ├── utils/         # Utility functions
│   └── types/         # TypeScript type definitions
├── public/            # Static assets
├── dist/             # Build output
└── tests/            # Test files
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 