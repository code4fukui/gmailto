# gmailto

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, single-page web app for generating pre-filled Gmail compose links.

This tool creates a direct URL to Gmail's compose interface, not a standard `mailto:` link.

## Demo

[https://code4fukui.github.io/gmailto/](https://code4fukui.github.io/gmailto/)

## Screenshot

The user interface is clean and straightforward, featuring input fields for To, CC, BCC, Subject, and a text area for the Body. The generated link is updated in real-time below the input form.

## Features

- **Dynamic Link Generation:** Creates a direct link to the Gmail compose window that updates in real-time as you type.
- **Full Email Composition:** Supports `To`, `CC`, `BCC`, `Subject`, and `Body` fields.
- **Zero Dependencies:** A standalone, single HTML file that runs entirely in your browser.
- **Simple & Fast:** A minimalist interface for quickly creating email links.

## Usage

1.  Open the [demo page](https://code4fukui.github.io/gmailto/).
2.  Fill in the desired email fields (To, CC, BCC, Subject, Body).
3.  Click the "gmailto link" at the bottom of the page.
4.  A new tab will open with the Gmail compose window pre-filled with your details.

## License

Licensed under the [MIT License](LICENSE).