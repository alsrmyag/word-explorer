# Word Explorer (단어 탐험대)

Elena's vocabulary game. Play: https://alsrmyag.github.io/word-explorer

- `index.html` — the built game (one file).
- `src/template.html` — game code with `/*WORDS*/` and `/*LESSONS*/` placeholders.
- `src/words.txt` — `word|pos|emoji|easy def|sentence with ___|syn/syn|ant/ant|level|Korean|picture distractors|s2 type:answer:distractors|fill-in distractors` (all questions are fixed)
- `src/gloss.txt` — `word|definition` for answer words that are not in the word list
- `src/lessons.txt` — `@L id|Title`, `W: words`, `S: sentence`, `Q: question|right|wrong|wrong`

Progress is saved only in the tablet browser (localStorage), not in this repository.
