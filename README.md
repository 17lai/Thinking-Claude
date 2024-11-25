# Thinking Claude

Let Claude think comprehensively before responding!

> **A super quick reminder:**
> Thinking claude **is not aimed for benchmarks or huge leaps in math or something**, since those are pre-determined by the base model (new Claude-3.5 Sonnet).
> I only want to explore how further we could reach with Claude's "deep mindset". That said, when using it in your daily tasks, you will find Claude's inner monolog (thinking process) very very fun and interesting.

## Demo

https://github.com/user-attachments/assets/88ff0c75-c51b-42b9-a042-00d47053795a

## Overview

This project consists of two main components:

1. **Thinking Protocol**: A comprehensive set of instructions that guides Claude to think deeply and systematically before responding
2. **Browser Extension**: A tool that makes Claude's thinking process more readable and manageable in the browser interface

## Project Structure

```bash
thinking-claude/
├── extensions/
│   ├── chrome/          # Current version of Chrome extension
│   ├── chrome_v0/       # Legacy Chrome extension (deprecated)
│   ├── firefox/         # Firefox extension (in development)
│   └── changelog.md
├── model_instructions/
│   ├── changelog.md
│   ├── v5.1-extensive-20241125.md
│   ├── v5.1-20241125.md
│   ├── v5-lite-20241124.md
│   ├── v4-20241118.md
│   ├── v4-lite-20241118.md
│   └── v3.5-20241113.md
├── .github/             # GitHub configurations and workflows
├── .husky/             # Git hooks for development
├── LICENSE
└── README.md
```

The project is organized into two main components:

- `extensions/`: Browser extension implementations

  - `chrome/`: Current version with modern architecture and features
  - `chrome_v0/`: Legacy version (deprecated)
  - `firefox/`: Firefox version (in development)

- `model_instructions/`: Thinking protocols for different versions
  - Contains versioned instruction sets
  - Each version brings improvements to Claude's thinking process

## Thinking Protocol

The thinking protocol instructs Claude to follow a natural, thorough thought process before providing responses.

## Browser Extension

The browser extension makes Claude's thinking process easier to read and use! It automatically organizes Claude's thoughts into neat, collapsible sections.

### Features

- 🎯 Makes Claude's thinking process easy to read
- 🔄 Fold and unfold different parts of Claude's thoughts
- 📋 Copy any part with just one click
- ⚡ Works automatically with new messages
- 🎨 Clean, modern design that's easy on the eyes

### 🚀 Quick Install Guide

1. **Chrome Users (Recommended)**

   - Install directly from the [Chrome Web Store](https://chromewebstore.google.com/detail/thinking-claude/ncjafpbbndpggfhfgjngkcimeaciahpo)

2. **Manual Installation**
   - Download the latest version from our [Releases Page](https://github.com/richards199999/Thinking-Claude/releases)
   - Unzip the file
   - Open Chrome and go to `chrome://extensions/`
   - Turn on "Developer mode" (top right corner)
   - Click "Load unpacked" and select the unzipped folder

👉 Want more details? Check out our [Extension Guide](extensions/chrome/README.md) for:

- Step-by-step installation instructions
- Development setup
- Advanced features and usage
- Troubleshooting tips

### 🎉 Getting Started

Once installed, just:

1. Visit [Claude.ai](https://claude.ai)
2. Start chatting with Claude
3. That's it! The extension will automatically make Claude's thinking process more readable

## Usage

### Applying the Thinking Protocol

1. Copy the latest version in `model_instructions` folder
2. Start a new Project in Claude.ai
3. Paste the instructions to the Custom Instructions section
4. Claude will now follow the thinking protocol for all subsequent interactions

### Using the Extension

Once installed, the extension automatically:

- Detects Claude's thinking process blocks
- Adds collapse/expand functionality
- Provides a copy button for each block

## Why Use Thinking Claude?

- **Better Reasoning**: Get more thorough and well-thought-out responses
- **Transparency**: See how Claude arrives at its conclusions
- **Improved Organization**: Manage long conversations more effectively
- **Quality Control**: Benefit from built-in verification steps

## Contributing

Contributions are welcome! Feel free to:

- Submit bug reports
- Propose new features
- Create pull requests

## License

MIT License - feel free to use and modify as needed.

## Acknowledgments

Special thanks to Claude! We build this whole extension together!
