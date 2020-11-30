# Robot Framework syntax highlighting test

An example program with Robot Framework syntax highlighting using Monaco Editor and TextMate grammar file.

Includes two added grammars in the `grammars` folder: `robot.tmLanguage` from Tomi Turtiainen's [language server](https://github.com/tomi/vscode-rf-language-server/blob/master/client/syntaxes/robot.tmLanguage) and `robotframework.tmLanguage.json` from the official Robocorp [language server](https://github.com/robocorp/robotframework-lsp/blob/master/robotframework-ls/syntaxes/robotframework.tmLanguage.json). Using the latter by default since it seems to be more extensive.

The `robot.json` file in `configurations` folder is also taken from the Robocorp [language server](https://github.com/robocorp/robotframework-lsp/blob/master/robotframework-ls/language-configuration.json). I had to change it a little bit to get it to work.

Otherwise I just followed the instructions that are included in `app.ts`.

The original README is below 👇

# monaco-tm

This gets TextMate grammars working in standalone Monaco by leveraging
`vscode-oniguruma` and `vscode-textmate`. For more context, see:
https://github.com/microsoft/monaco-editor/issues/1915.

## Run demo

- `yarn install`
- `yarn demo`
- open http://localhost:8084/

Currently, only the Python grammar and VS Code Dark+ themes are included in the
demo.
