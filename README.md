# Certificate Library

A responsive, browser-based certificate collection and PDF reader for the files in this repository.

## Features

- Responsive layout for phones, tablets, laptops, and desktop screens.
- Automatically discovers PDF files in the repository, including nested folders.
- Search certificates by filename and sort the list alphabetically in either direction.
- Preview PDF documents in the browser using PDF.js.
- Navigate between pages, enter a page number, zoom in and out, fit a page to the viewer width, and rotate pages.
- Open the original PDF in a separate tab or download it.
- Loading, empty, and error states, plus a manual library refresh.
- Keyboard shortcuts: Left/Right Arrow for page navigation, + to zoom in, and - to zoom out.
- Accessible control labels, visible keyboard focus, and reduced-motion support.
- No emojis in the interface.

## Usage

Open the published site:

https://HumayunShariarHimu.github.io/certificate/

Or serve the repository locally with any static HTTP server. For example:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

The application uses the GitHub Contents API to discover PDF files and loads PDF.js and Font Awesome from CDNs. An internet connection is required. The public GitHub API has unauthenticated rate limits, so wait and refresh if the application reports that the API limit has been reached.

## Repository

https://github.com/HumayunShariarHimu/certificate
