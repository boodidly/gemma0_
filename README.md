# Modern Terminal UI

A beautiful, customizable terminal wrapper with script management and theme support.

![Terminal UI Preview](https://images.unsplash.com/photo-1629654297299-c8506221ca97?auto=format&fit=crop&q=80&w=1000)

## Features

- 🎨 Customizable accent colors
- 📜 Script management system
- 🖥️ Multiple terminal profile support
- 🎯 Quick-access script buttons
- 🔄 Import/export terminal configurations
- 🌈 Beautiful, modern UI design

## Prerequisites

- Node.js 18.x or higher
- npm 9.x or higher

## Installation

1. Clone the repository:
```bash
git clone https://github.com/boodidly/gemma0_.git
```

2. Navigate to the project directory:
```bash
cd gemma0_
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm run dev
```

## Usage

### Managing Scripts

1. Click the "+" button in the sidebar to add a new script
2. Enter the script name and command
3. Click "Add Script" to save

### Customizing Colors

1. Click the palette icon in the sidebar
2. Select from the available color options
3. The UI will update immediately with your chosen accent color

### Terminal Profiles

1. Click the settings icon next to "Terminal Profile"
2. Select from pre-configured profiles or import your own
3. To import a custom profile:
   - Click the upload icon
   - Choose a JSON configuration file
   - Review the preview
   - Click "Import Profile"

### Example Profile JSON

```json
{
  "name": "Custom Terminal",
  "shell": "/bin/bash",
  "backgroundColor": "#1A1B26",
  "foregroundColor": "#A9B1D6",
  "fontSize": 14,
  "fontFamily": "JetBrains Mono",
  "opacity": 0.95
}
```

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- Vite
- Lucide Icons

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
