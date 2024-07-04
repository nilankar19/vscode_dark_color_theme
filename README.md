# simple-theme-color


## Publishing Your Theme (win CMD recommended)

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
