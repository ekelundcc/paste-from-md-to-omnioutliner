## OmniOutliner Markdown Import Plugin

A simple OmniOutliner plugin that imports Markdown from your clipboard and converts it into a hierarchical outline structure.

## Features

- Converts Markdown headers to outline hierarchy (`#` = level 1, `##` = level 2, etc.)
- Automatically removes numbering prefixes (1, 1.1, 1.1.1, etc.) from headers
- Converts text between headers into notes
- Validates clipboard content before running
- Supports up to 6 levels of nesting

## Installation

1. In OmniOutliner, go to **Automation > Console**
2. Click the **+** button to create a new action
3. Copy and paste the code from `paste-from-md.omnijs` into the editor
4. Save the action
5. The plugin will now appear in your Automation menu

## Usage

1. Copy Markdown text to your clipboard
2. Open an outline in OmniOutliner
3. Run the "Paste from Markdown" action from the Automation menu
4. The Markdown structure will be converted to outline items

## Limitations

- Does not preserve Markdown links in notes (converts to plain text)
- Always creates new items at the root level
- Simple parser - does not handle all Markdown features (lists, code blocks, etc.)
- Cannot merge with existing outline structures intelligently

## Companion Plugin

Works perfectly with OmniOutliner to Markdown Exporter for round-trip conversion.

## Development

This plugin uses the [Omni Automation](https://omni-automation.com/tutorial/og-macos/index.html) JavaScript API for OmniOutliner.

## License

MIT License - see LICENSE file for details

## Requirements

- OmniOutliner 5 or later (macOS)

## Author

Fredrik Ekelund
