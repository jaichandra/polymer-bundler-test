# polymer-bundler-test

Steps to test:
* `bower install`
* `polymer-bundler --inline-scripts --strip-comments --root . --in-html assets/elements.html > assets/elements.bundle.html` to generate the bundle file.
* `python -m SimpleHTTPServer 8088`
* Test in browser: `http://localhost:8088`
* Check console log for error - `texture.jpeg` fails to load
