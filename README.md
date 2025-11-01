# Anki Multiple Choice Notes
### Anki note template for multiple choice questions

---

Have multiple choice flashcards with up to 9 options, extremely simplistic, only checkbox and text.

*To be used with Anki*

---

### Installation

1. In your Anki client, open the "manage note types" menu and add a new note type.
2. Open "edit cards" or similar options and paste the code in `anki-mc-front.html` as the front page, and `anki-mc-back.html` as the back page.
3. Open "fields" or similar options and add:
  1. One field named `Question`
  2. 9 fields named `Option 1` through `Option 9`
  3. One field named `Answer Index`

The name of the fields are case sensitive and will be referenced in the code.

### Usage

1. Add a flashcard and switch the note type to the added type.
2. Fill in `Questions` and `Options 1-9`. If you don't need the extra options, leave them blank.
3. In `Answer Index`, type the trailing number of the correct options without any separation. For example, if `Option 1`, `Option 3`, and `Option 4` are correct, input `134`.
4. Study the card, when the card loads, the options are re-arranged randomly

---

### Note

Tested on the Anki app for Windows and AnkiDroid.

To persist choice between both sides of the card, [anki-persistence](https://github.com/SimonLammer/anki-persistence) is used.
