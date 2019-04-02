# WebAssembly Testing

A test playground for WebAssembly.

## Compile

After changes to `hello.c`, compile it to HTML with the following:

`$ emcc hello.c -s WASM=1 -o hello.html`

This will create a new `hello.html` file. Now, fire up the `emrun` web server provided with the Emscripten SDK to serve your files:

## Run

`$ emrun --no_browser --port 8080 .`