# The Library of Babel

This is a simple, single-file implementation of Jorge Luis Borges' concept of the Library of Babel - an infinite library containing every possible combination of text.

## What it does

The library contains every book that has ever been written, every book that could be written, and infinite amounts of gibberish. You can navigate through hexagons, walls, shelves, volumes, and pages to explore this infinite space.

## Features

- Navigate to specific locations in the library
- Search for any text and find where it appears
- Random page generation
- Multiple search modes (exact match, random characters, English words, titles)
- URL sharing for specific pages

## Usage

Try it live at: https://thecommallama.github.io/libraryofbabel/

Or run locally: just open index.html in a web browser. No server required - it's all client-side JavaScript.

## Tech

This was vibe coded as a single HTML file with embedded CSS and JavaScript. It uses seeded random generation to create deterministic pages based on location coordinates.
