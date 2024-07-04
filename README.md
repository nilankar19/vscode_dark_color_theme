# simple-theme-color README

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## Publishing Your Theme

1. Install VSCE:

   ```
   npm install -g @vscode/vsce
   ```

2. Navigate to your theme folder:
   ```
   cd your-theme-folder
   ```

3. Login to VSCE:
   ```
   vsce login <your-publisher-id>
   ```
   Enter your Azure token when prompted.

4. Ensure your `package.json` has the correct publisher name (same as your login ID).

5. Package your theme:
   ```
   vsce package
   ```
   This generates a `myExtension.vsix` file.

6. Publish your theme:
   ```
   vsce publish
   ```

Enjoy your new theme!

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
