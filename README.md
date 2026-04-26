# Direct Download Search

> Direct Download Search: A simple browser based tool named has been created using Google Dork queries to search through open directory servers for publicly accessible files.
The user enters what they want to find (using a keyword), the type of file they want (video, music, book, software or image) and this will build and launch a specific targeted Google search with no back end, no log in and no scraping, only fast and intelligent file discovery. 

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![MIT License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)](LICENSE)

---

## Preview

![Direct Download Search Preview]
<img width="1052" height="526" alt="Direct Download Search" src="https://github.com/user-attachments/assets/9ea4c433-c93e-4826-b9ce-043a06b880be" />


---

## About

**Direct Download Search** is a simple, browser-based tool that uses Google Dork queries to search open directory servers for publicly accessible files. Enter a keyword and select a file type — video, music, book, software, or image — and the tool will automatically build and launch a targeted Google search. No backend, no login, no scraping. Just fast and intelligent file discovery.

---

## Features

- **File type filtering** — Choose from Video, Books, Music, Software, or Images
- **Google Dork engine** — Automatically builds advanced `intitle:index.of` search queries
- **Zero backend** — Fully client-side, pure HTML, CSS, and JavaScript
- **Dark mode support** — Adaptive light and dark theming
- **No login required** — No accounts, no API keys, nothing to install
- **Instant launch** — Opens the targeted Google search directly in a new tab

---

## How It Works

1. Enter a keyword (e.g. `The Blacklist S01E01` or `Dune`)
2. Select a file type from the dropdown (or leave it as **All Files**)
3. Click **Search**
4. The tool builds a Google Dork query and opens it in a new tab

**Example query generated:**

```
Dune +(mkv|mp4|avi|mov) -inurl:(jsp|php|html|aspx) intitle:index.of
```

---

## Supported File Types

| Category | Formats |
|----------|---------|
| Video / Movies | `mkv`, `mp4`, `avi`, `mov`, `mpg`, `wmv`, `divx`, `mpeg` |
| Books | `pdf`, `epub`, `mobi`, `docx`, `fb2`, `cbr`, `cbz`, and more |
| Music / Audio | `mp3`, `wav`, `flac`, `ogg`, `aac`, `wma`, `m4a` |
| Software / Games | `exe`, `iso`, `dmg`, `zip`, `rar`, `7z`, `apk` |
| Images | `jpg`, `png`, `gif`, `bmp`, `psd`, `tif` |

---

## Getting Started

No installation needed. Just open the HTML file in any modern browser.

```bash
# Clone the repository
git clone https://github.com/aymansaikat/direct-download-search.git

# Open in browser
cd direct-download-search
open index.html
```

Or simply [**view the live demo →**](https://aymansaikat.blogspot.com)

---

## Built With

- [Bootstrap 5](https://getbootstrap.com/) — UI framework
- [Bootstrap Icons](https://icons.getbootstrap.com/) — Icon set
- Vanilla JavaScript — No frameworks, no dependencies

---

## Disclaimer

This tool only constructs and launches Google search queries. It does not host, store, distribute, or scrape any files or content. All results are sourced directly from Google's public search index. The user is solely responsible for how they use the search results. This tool is intended for educational and research purposes only.

---

## Author

**Ayman Saikat**
[Blog](https://aymansaikat.blogspot.com)

---

## License

This project is licensed under the [MIT License](LICENSE).
