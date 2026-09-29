# OmniNavBench redirect

Independent static redirect to the [OmniNavBench website](https://huggingface.co/spaces/Sun-Season/omni-nav-bench).

Publish the `main` branch root with GitHub Pages. No backend, credentials, user data, or evaluation code is required.

`index.html` uses a fixed destination, with JavaScript and HTML refresh plus a visible fallback link. Incoming query strings and paths are not forwarded. This is a browser-side redirect, not an HTTP 301 response.

The legacy domain can be connected after the Pages deployment is verified. Until then, leave its DNS and existing HTTP tunnel unchanged.
