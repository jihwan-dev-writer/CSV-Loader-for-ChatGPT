# CSV Loader for ChatGPT

CSV Loader for ChatGPT is a Chrome Extension that allows users to upload CSV files into the OpenAI's ChatGPT interface. Upon uploading a CSV file, the extension sends the first 200 lines of data to ChatGPT prompt.

## Installation and Usage

1. Clone or download this repository.
2. Open your Chrome browser and navigate to `chrome://extensions`.
3. Enable "Developer mode" from the switch on the top right corner.
4. Click on the "Load unpacked" button and select the directory of this repository.
5. You can now click on the extension icon in your browser's toolbar and upload a CSV file.

## Note

- The extension will only recognize the first 200 lines of any uploaded CSV file.
- This extension operates on the `https://*.openai.com/*` domain.

## About the Developer

This extension is designed to provide an interface for uploading CSV files to OpenAI's ChatGPT. For any bugs, issues or feature requests, please use the GitHub issue tracker.

## License

MIT License. For more information, see the LICENSE file.
