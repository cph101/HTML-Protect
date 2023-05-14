# HTML-Protect
The new way to stop people tampering

HTML-Protect is a project which aims to stop people modifying or stealing the code of a website. It does the job very well, but also has some limitations.

## Usage
Insert the following line of code anywhere in your HTML document:
`<script src="https://raw.githubusercontent.com/cph101/HTML-Protect/main/htmlproject.min.js"></script>`

## Limitations
- Non-inlined files accessed with `<script src...` or `<link href...` as well as any http requests made by the website will show up in the Network tab of the web inspector
- DOM cannot be edited after page is fully loaded

## NodeJS Package

Coming soon, please star or watch this project to get updates in your github feed.
