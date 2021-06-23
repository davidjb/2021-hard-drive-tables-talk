# Lightning Talk: Hard Drive Tables

A lightning talk delivered at DevNQ about hard drive "tables".

Slides PDF: <TBD>

## Setup

```bash
yarn
yarn start
```

This starts the presentation server at <http://localhost:8080> and
automatically opens a browser.

## Creating a PDF

```bash
yarn pdf
```

Look for the `.pdf` file in the current directory.  To optimise the file for the web:

```bash
brew install ghostscript
yarn optimise-pdf
```

## Stack

* `yarn`
* `reveal.js`
* `live-server` (for serving/reloading on changes)
* `decktape` (for creating PDFs from the slides)
* `GhostScript` (for optimising the PDF output)

## References

