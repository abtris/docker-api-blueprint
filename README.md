# Docker API documentation in API Blueprint

## Installation & Usage
There are two ways to use aglio: as an executable or as a library for Node.js.

### Executable
Install aglio via NPM. You need Node.js installed and you may need to use `sudo` to install globally:

```bash
npm install -g aglio
```

Then, start generating HTML.

```bash
## Default theme
aglio -i input.apib -o output.html

## Built-in color scheme
aglio --theme-variables slate -i input.apib -o output.html
