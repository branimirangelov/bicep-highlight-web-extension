# Bicep Syntax Highlight

Bicep syntax highlighting support for VS Code for Web. 
Filling the gap until official Bicep extension [adds web support](https://github.com/Azure/bicep/issues/5032).

## Features

Simple syntax highlighting based on Bicep [TM grammar](https://github.com/Azure/bicep/tree/main/src/textmate)

## Run

To run and test the extension locally you can use:
```
npx @vscode/test-web --browserType=chromium --extensionDevelopmentPath=. .
```

## Release Notes

### 0.0.1
- Initial release for Bicep syntax highlight supporting VS Code for Web
