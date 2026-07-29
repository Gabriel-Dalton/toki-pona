# Toki Pona word swapper

A learning exercise from March 2025. One HTML file holding a text box, a button, and a 17 word English to Toki Pona dictionary in a plain object.

## How it works

`translateText()` lowercases the input, splits it on spaces, and swaps any word that has an entry. Anything unknown passes through untouched. That is the entire program.

It swaps words and does not translate. There is no grammar, no particles, no context. One entry is the two word phrase `thank you`, which the space split can never reach, so it never fires.

## Run it

Open `translator.html` in a browser. No server, no dependencies.
