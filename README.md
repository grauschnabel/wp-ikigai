# WP Ikigai Finder

A WordPress plugin that provides an AI-powered Ikigai finder to guide users through their personal Ikigai discovery process.

Version: 0.1.4

## Description

WP Ikigai Finder is an innovative WordPress plugin that uses artificial intelligence (OpenAI GPT) to help users discover their personal Ikigai. Ikigai is a Japanese concept that describes the "reason for being" or "joy of life" - the sweet spot where passion, mission, profession, and vocation intersect.

### Key Features

- Interactive AI guide through the Ikigai discovery process
- Four-phase structure for systematic exploration of personal Ikigai
- Customizable system prompts and AI parameters
- Responsive and user-friendly interface
- Multiple GPT models to choose from
- Available in English and German

## Installation

1. Download the plugin ZIP file
2. Go to your WordPress dashboard "Plugins > Add New"
3. Click "Upload Plugin"
4. Select the downloaded ZIP file
5. Click "Install Now"
6. Activate the plugin

## Configuration

1. Navigate to "Settings > WP Ikigai"
2. Enter your OpenAI API key
3. Select your preferred GPT model
4. Adjust other parameters if needed
5. Save settings

## Usage

1. Add the "WP Ikigai Finder" block to any page or post
2. Publish the page
3. The chat interface will appear automatically

### Best Practices for Users

For optimal results, users should:
- Provide detailed answers to the guide's questions
- Take time for reflection
- Communicate honestly and openly
- Include specific examples and details in their responses

## Development

### Prerequisites

- Node.js and npm
- WordPress 6.0 or higher
- PHP 7.4 or higher

### Developer Setup

```bash
# Clone repository
git clone https://github.com/grauschnabel/wp-ikigai.git

# Install dependencies
npm install

# Start development build
npm run start

# Create production build
npm run build
```

## Contributing

Contributions are welcome! Please read our contribution guidelines before creating a pull request.

## License

GPL v2 or later

## Author

Martin Kaffanke  
Email: martin@kaffanke.info  
GitHub: [@grauschnabel](https://github.com/grauschnabel)

## Changelog

### 0.1.4
- Complete German translation
- Improved block rendering and asset loading
- Enhanced error handling and security
- Fixed coding standards compliance
- Optimized chat interface

### 0.1.3
- Enhanced UI with WordPress system colors
- Optimized phase display
- Automatic chat initiation
- Improved system prompt handling
- Added new GPT models
- Added multilingual support (EN/DE)

### 0.1.2
- Improved error handling
- Implemented system prompt as HEREDOC

### 0.1.1
- Initial public release
- Basic Ikigai finder functionality 