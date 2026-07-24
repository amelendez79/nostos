# Nostos

A five-minute game that gives you the background to fully enjoy Christopher Nolan's
*The Odyssey*: the characters, the myths, the ideas the film assumes you already have.
No plot of the film, only the three thousand years underneath it.

You play as Odysseus through the seven decisions the story turns on. Every choice
explains itself and ends with what to watch for on screen. It closes with a field
guide, the full cast list, and what to expect in the cinema.

A fun experiment by [Unpredator LLC](https://unpredator.com). Stay Wild. Stay Human.

## Running it

`index.html` is a single self-contained file. No build step, no dependencies, no
network calls. Open it directly, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploying

GitHub Pages serves this folder as-is. In the repository settings, under Pages,
set the source to the branch and folder holding `index.html`.
