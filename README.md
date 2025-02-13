# Watsonx Chrome Extension

## Overview
The Watsonx Chrome Extension integrates Watsonx.ai capabilities directly into your browser, allowing users to interact with AI-driven chat and text processing tools on any website. This extension enhances productivity by providing features such as summarization, translation, grammar checking, and AI-driven responses.

## Features
- AI-powered chat with Watsonx.ai via a sidebar.
- Secure authentication using IBM Watsonx API keys.
- Context-aware quick menu for summarization, translation, and text adjustments.
- Customizable settings for personalized AI interactions.
- Support for both light and dark mode.
- Webpage-aware responses and content-based interactions.
- Ability to capture screenshots and query Watsonx Vision.

## Installation
### Manual Installation
To install the extension manually, follow these steps:
1. Clone the repository or download the source code.
2. Run `yarn build` to generate the `dist` folder (ensure Node.js and Yarn are installed).
3. Open Google Chrome and navigate to `chrome://extensions/`.
4. Enable "Developer mode" in the top right corner.
5. Click "Load unpacked" and select the `dist` folder.

## Usage
- Open the chat sidebar by pressing `Ctrl + Shift + X`.
- Select text on a webpage to access the quick menu options.

### Quick Menu Options
#### Review Selection
- Summarize
- Simplify language
- Translate
- Extract key takeaways

#### Edit Selection
- Correct spelling and grammar
- Adjust tone
- Shorten or extend text

#### Reply Suggestions
- Generate a positive response
- Generate a negative response
- Request more information

These options can be customized through the settings page by defining custom prompts.

## Security & Privacy
The extension stores user API keys locally and does not transmit them to any external service beyond direct API requests to Watsonx.ai. No user data is collected or stored beyond the immediate session.

## Contribution
Contributions are welcome to improve the extension. Please follow standard development and pull request guidelines when submitting changes.



