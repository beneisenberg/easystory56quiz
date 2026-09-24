# לָבָן בִּקֵּשׁ אֶת־אֱלֹהָיו

Two interactive Biblical Hebrew comprehension games on Genesis 31, Jacob's flight from Laban and Rachel hiding the teraphim: a twelve-question quiz and a drag-and-drop cloze passage. Entirely in Hebrew with full niqqud, built for communicative / comprehensible-input classrooms.

Companion to [Lesson 144](https://youtu.be/gD-_d9FGSoM) (story 56 — לָבָן בִּקֵּשׁ אֶת־אֱלֹהָיו).

## What it does

The start screen offers both games — **שְׁאֵלוֹת** and **מִלִּים** — and each links to the other when finished.

### שְׁאֵלוֹת — the quiz

Each correct answer adds a camel to Jacob's caravan across the top of the screen — וַיִּשָּׂא אֶת־בָּנָיו וְאֶת־נָשָׁיו עַל־הַגְּמַלִּים — walking west from Paddan Aram. The score is the caravan.

After every answer — right or wrong — the corresponding line of the biblical text appears, with Masoretic cantillation intact. The reward for answering is more Hebrew input, not a score animation. Questions missed along the way are collected into a review list at the end, so students can take them back to the video.

### מִלִּים — the cloze passage

The story appears in full, with fifteen words missing. A bank of word tiles sits beside the text, or pinned to the bottom of the screen on a phone. Students drag each word into its place, or tap a word and then tap its place, which is the dependable method on touchscreens. Tapping a filled blank returns the word to the bank.

Seven of the tiles belong nowhere. Most are morphological traps rather than story traps: each one fits the grammar of a slot's position but differs from the real word only in a prefix or suffix — וַיֵּשֶׁב for וַתֵּשֶׁב, הַגְּמַלִּים for הַגָּמָל, אֵינֶנּוּ for אֵינָם, אֱלֹהֶיךָ for אֱלֹהַי, כֵּלֶיךָ for כֵּלַי. Students can't eliminate them on meaning alone; they have to read the endings. Two are story traps: שְׁלֹשֶׁת for שִׁבְעַת, and לֵאָה for רָחֵל.

Nothing is graded until the student presses **הַאֱמֶת?** — the interrogative הַ before a guttural, not the article — so the passage can't be solved by trial and error. Correct words are marked, wrong ones can be tapped back into the bank and tried again. When every word is in its place, the whole caravan lights up.

Only words that carry no taamim in the lesson text are blanked, so no tile ever has an accent stranded on it.

There is no English anywhere in the interface.

## Typography

Hebrew is set in **SBL Hebrew** (Tiro Typeworks, v1.56a), embedded in the file so every student sees the same rendering regardless of what is installed on their machine. The `@font-face` rule lists `local("SBL Hebrew")` first, so anyone who already has it installed loads their own copy and skips the \~315 KB download.

Type is set in the regular weight throughout. SBL Hebrew ships no bold, and synthetic bold smears badly over niqqud and taamim, so hierarchy runs on size and color instead. Leading is opened up well beyond a Latin-typeface default to keep cantillation above and below the baseline from colliding between lines.

## License

The game — text, questions, code, design — is released into the **public domain (CC0)** by Ben Eisenberg / Lingua Deo Gloria, for the free use of the global church. Copy it, translate it, adapt it, teach with it, sell it, no attribution required.

**The embedded font is not covered by that dedication.** SBL Hebrew is © John Hudson, Tiro Typeworks, 2003 \& 2007; SBL Hebrew is a trademark of the Society of Biblical Literature. It is redistributed here unmodified, with its embedding bit unaltered, under clauses 3 and 5 of the [SBL Font End User License Agreement](https://www.sbl-site.org/wp-content/uploads/2024/05/SBL_Font_End_User_License_Agreement.pdf), which permit free redistribution of the unmodified software and embedding in non-commercial electronic documents including web pages. The full license text travels inside `index.html`.

That license covers non-commercial use only. If you intend to use this commercially, contact the Society of Biblical Literature for a font license, or swap the `@font-face` rule for an open-licensed Hebrew face with cantillation support — Taamey Frank CLM, Taamey David, Keter YG, Ezra SIL and Cardo are all good candidates.

