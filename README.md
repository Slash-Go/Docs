# Documentation for SlashGo

### How to build/run

```
// Install dependencies for building/serving documentation
$ npm i -g redoc-cli serve


// Build documentation
$ redoc-cli build swagger.yaml -o index.html

// Serve documentation
$ serve -s .

// Documentation is now accessible on http://localhost:3000
```
