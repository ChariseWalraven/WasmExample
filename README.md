## Wasm Example

I coded this while following this [WebAssembly tutorial](https://tutorialzine.com/2017/06/getting-started-with-web-assembly) online.

To see the result in the browser, clone the repo, `cd` into `WebAssembly` and then run `python -m SimpleHTTPServer 9000` to start up a server on [localhost:9000](http://localhost:9000).

After starting the server, the roll_dice function should be availabel to you in the browser console under the name of `_roll_dice`.

### NOTE:

In order for this to work, you must be using a browser that supports WebAssembly. See [CanIUse](https://caniuse.com/#search=webassembly) for more information.