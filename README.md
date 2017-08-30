# Hypothesis EPUB Demo Content Library

A curated set of EPUBs for use in demonstrating Hypothesis integration with EPUB
readers, such as Readium.js.

## Usage with ReadiumJS

Use the `epubs` query param to point an instance of the Readium cloud reader at
the `library.json` file from this repository.

For example, assuming that the Readium cloud reader's `index.html` file is
accessible at `http://localhost:8080/index.html` and that the URL of
`library.json` is `http://localhost:8080/hypothesis-epub-content/library.json`:

```
http://localhost:8080/index.html?epubs=http://localhost:8080/hypothesis-epub-content/library.json
```

If the Readium cloud reader is hosted on a different domain than this demo
content, the demo content must allow cross-origin access.