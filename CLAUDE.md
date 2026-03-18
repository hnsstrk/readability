# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A static webpage for experimenting with text colors based on readability scores (ARI — Automated Readability Index) against fixed background colors. Created to address the readability color misalignment issue in [Zettlr #5355](https://github.com/Zettlr/Zettlr/issues/5355).

## Tech Stack

- **Frontend:** Static HTML (single file, no dependencies)
- **License:** BEER-WARE

## Project Structure

```
readability/
├── index.html    # Complete experiment page
├── README.md     # Project documentation
└── LICENSE       # BEER-WARE License
```

## Development

Open `index.html` in any modern browser. No build step required.

## Key Concepts

- Colors range from green (easy to read) to red (difficult to read) based on ARI score
- Tested against 4 fixed backgrounds: Light (#F3F3E8), Dark (#14141E), White (#FFFFFF), Dark Blue (#002B36)

## Documentation

Projektdokumentation: Siehe Obsidian Vault [[Readability]]
