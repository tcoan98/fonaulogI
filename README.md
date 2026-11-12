# fonaulogI — Phonology Practice Lab

A free, browser-based phonology practice website with a Wisconsin-inspired dark theme.

## What it includes

- **IPA consonant inventory:** Classify symbols by voicing, place, and manner, or select every sound matching one to three phonetic features.
- **Phonological processes:** Three quiz modes with **600 unique words** across 16 process types: Identify the process (multiple-choice or typed name), Apply a process (build a sound change), and Transcribe & apply (write the adult word in IPA and the full IPA production after the named process).
- **Selectable practice word bank:** Original 300 (foundational), Advanced 300 (217 two-syllable and 83 three-syllable words), or All 600 (mixed). Changing banks starts a new round; non-repeating question selection and the Different word control respect the selected bank. See [the advanced word list and validation notes](ADVANCED_WORD_BANK.md).
- Randomized IPA keyboards, randomized non-repeating words within each quiz, a **Different word** button, and a **Review Quiz** screen.

- **Audited IPA practice:** Removed word-initial [ŋ] example errors and filters invalid generated applications. In the transcription mode, accepts appropriate unstressed final /i/ or /ɪ/ variants. See [IPA rules and audit](IPA_RULES.md).
- **Mobile input:** IPA transcription boxes use an on-page IPA keypad by default on touch devices, with a **Phone keyboard** option. Typed phonological-process names always use the regular text keyboard; desktop users can type normally or use the IPA keys. The transcription keypad stays in a consistent order; graded choice keyboards remain randomized.
- **Clearer feedback and navigation:** Transcribe & apply reports adult IPA and the applied IPA separately (0, 1, or 2 parts correct). **Next question** scrolls the prompt into view on mobile. Primary and secondary stress marks are not displayed or required; the on-screen IPA keyboard omits them.
- 10-question quiz rounds.
- Works entirely in a web browser. **No build, runtime dependencies, login, or hosting backend required.**

## Publish with GitHub Pages

1. Go to this repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select branch **main** and directory **/(root)**.
4. Click **Save**.

The site will be available at:

**https://tcoan98.github.io/fonaulogI/**

Publishing can take a few minutes. Check the **Actions** tab or **Settings → Pages** for deployment status.

## Update the app

The entire website is in `index.html` at the repository root. Edit it or upload an updated replacement and commit to `main`; GitHub Pages will publish the new version.

## Notes

- Educational practice examples only. Word transcriptions may vary by dialect and are not developmental norms or clinical guidance.
- Wisconsin-inspired colors; **not affiliated with or endorsed by UW–Madison**.
- Do not store personal, student, or patient information in the public repository.
