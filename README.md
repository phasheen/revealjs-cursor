# Cursor & Model Context Protocol Presentation

This presentation provides an overview of Cursor, the AI-powered code editor, and the Model Context Protocol (MCP), which standardizes how applications provide context to LLMs.

## Presentation Content

- Introduction to Cursor, an AI-powered code editor built on VSCode
- Cursor's key features including Agent mode, Chat, Tab completion, and Ctrl+K editing
- Overview of the Model Context Protocol architecture
- Detailed explanation of MCP implementation and configuration
- Practical applications of Cursor and MCP in real-world development
- Discussion and practice exercise ideas

## How to Use This Presentation

1. Edit the content in `index.html` to customize your presentation
2. Modify presenter information in `custom/custom-scripts.js`:
   ```javascript
   const presenterName = "Your Name";
   const presenterDepartment = "Your Department";
   const presenterUniversity = "Your University";
   const presenterEmail = "your.email@example.com";
   const sessionName = "Your Presentation Title";
   ```

3. Start the development server:
   ```
   npm start
   ```

4. View your presentation at http://localhost:8000

## Key Features Covered

- **Agent Mode**: End-to-end task completion with programmer control
- **Chat with Codebase**: AI chat that understands your code context
- **Tab Completion**: Multi-line code predictions and smart rewrites
- **Ctrl+K Editing**: AI-assisted code editing and generation
- **MCP Architecture**: Standardized protocol for AI model context
- **MCP Configuration**: Setting up and using MCP with Cursor
- **Practical Applications**: Code refactoring, feature implementation, bug fixing

## Resources

The presentation includes links to important resources:
- [Cursor Features Documentation](https://www.cursor.com/features)
- [Cursor MCP Documentation](https://docs.cursor.com/context/model-context-protocol)
- [Model Context Protocol Documentation](https://modelcontextprotocol.io/introduction)

## Customization

- Modify the styling in `custom/custom-styles.css`
- Change behavior or add features in `custom/custom-scripts.js`
- Update the theme in `index.html`:
  ```html
  <link rel="stylesheet" href="dist/theme/white.css">
  ```
- Adjust the theme color in `custom/custom-styles.css`:
  ```css
  :root {
    --theme-color: #2a76dd; /* Change this to any color you want */
  }
  ```

## Credits

This presentation was created using the [SNUPHEL Reveal.js Template](https://github.com/phasheen/revealjs-snuphel).

Built with [Reveal.js](https://revealjs.com) - The HTML Presentation Framework

Content based on official documentation from [Cursor](https://www.cursor.com) and the [Model Context Protocol](https://modelcontextprotocol.io). 