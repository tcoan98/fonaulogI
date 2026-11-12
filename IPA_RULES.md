# IPA and Phonological-Process Audit

**Scope:** 300 distinct curated adult words, 16 processes (18–19 examples each), plus the application's automatically generated *Apply a process* choices.

**Goal:** Provide consistent **broad, illustrative American English** transcription practice, not predict every child's production or prescribe developmental norms. English phonotactics describes adult patterns; a child's atypical production is not physically impossible merely because it violates an adult restriction.

## Applied checks

1. **Word-initial velar nasal** — do not use initial [ŋ] as a default English practice answer. Remove eight curated examples that incorrectly generated it; exclude such results from automatic applications.
2. **Backing** — use context-independent alveolar /t/→[k] and /d/→[ɡ] substitutions; do not auto-generate initial /n/→[ŋ]. Where a velar consonant elsewhere in a word conditions a change, classify it as assimilation rather than unrestricted backing.
3. **Assimilation** — require another sound with the relevant place of articulation in the *adult target* to motivate the change. Keep labial, alveolar and velar assimilation distinct.
4. **Unstressed final happy vowel** — accept **/i/** and **/ɪ/** for the final unstressed vowel in the **17 specifically reviewed polysyllabic words** in the site (e.g., *baby, cherry, jelly, happy, cookie*). This equivalence does **not** extend to stressed vowels, monosyllabic *key*, or unrelated /i/–/ɪ/ contrasts. Where reduplication eliminates the final vowel, the transformed response must still be correct for that process.
5. **Letters versus sounds** — practice uses phonemes, not spelling; silent letters are excluded (e.g. *knock* starts /n/). The 300 reference transcriptions were checked against an offline CMU pronunciation lexicon for broad plausibility.
6. **Position-sensitive processes** — check that cluster reduction changes an initial consonant cluster, final consonant deletion affects the final consonant, gliding targets a liquid in a permitted position, and vocalization targets a coda liquid.
7. **Syllable structure without stress-symbol practice** — validate reduplication as an actual repeated production; weak syllable deletion must remove an initial unstressed syllable. The underlying reference data may retain stress markers so the process validator can distinguish unstressed syllables, but learner-facing IPA questions, expected answers, and the custom keyboard omit both primary (ˈ) and secondary (ˌ) stress marks. Markers are not graded in typed transcriptions.
8. **Voicing counterparts** — preserve place/manner using reviewed voiced–voiceless pairs. Restrict prevocalic voicing to an eligible initial consonant before a vowel, and final devoicing to a word-final counterpart.
9. **Notation-only normalization** — allow capitalization-independent process names (with approved synonyms), /g/ vs /ɡ/, /r/ vs /ɹ/, optional transcription brackets, and tied versus untied affricate notations. Distinct IPA vowels and consonants are not universally interchangeable.
10. **Question validation** — check the expected whole-word result, the change's position, conditioning sounds and the no-initial-[ŋ] rule. Automatically generated alternatives that fail are excluded rather than displayed as correct.

## Curated word replacements

All eight replacements maintain 300 distinct words and preserve the per-process balance.

| Process | Removed example | New example |
| --- | --- | --- |
| Backing | nail /neɪl/ → [ŋeɪl] | dot /dɑt/ → [ɡɑt] |
| Backing | nine /naɪn/ → [ŋaɪn] | dust /dʌst/ → [ɡʌst] |
| Backing | new /nu/ → [ŋu] | dish /dɪʃ/ → [ɡɪʃ] |
| Backing | night /naɪt/ → [ŋaɪt] | dive /daɪv/ → [ɡaɪv] |
| Velar assimilation | neck /nɛk/ → [ŋɛk] | duck /dʌk/ → [ɡʌk] |
| Velar assimilation | nuke /nuk/ → [ŋuk] | tiger /taɪɡɚ/ → [kaɪɡɚ] |
| Velar assimilation | knock /nɑk/ → [ŋɑk] | ticket /tɪkɪt/ → [kɪkɪt] |
| Velar assimilation | nag /næɡ/ → [ŋæɡ] | digger /dɪɡɚ/ → [ɡɪɡɚ] |

## Validation completed

- **300** curated entries, **300** distinct orthographic words.
- **16** process categories with **18 or 19** dedicated words apiece.
- **300/300** curated items pass the process-placement and expected-production checks.
- **623** additional generated Apply-mode choices pass the same guards; unsafe ones are excluded.
- No included target or transformed production begins with [ŋ].
- All 300 words were found in the CMU pronouncing dictionary. A broad phoneme-sequence comparison identified two items (*giraffe* and *around*) needing awareness of unstressed rhotic-vowel variation; these are retained as plausible transcriptions rather than forcing a single dialect.
- Browser grading of all **300** curated pairs passed, including correct /ɪ/ alternatives in relevant contexts and rejection elsewhere.
- Ten-question rounds and review screens passed in **Identify**, **Apply**, and **Transcribe & apply** modes, including mobile viewport checks.

These validations check the site's internal consistency and a broad dictionary comparison; they do not replace a full clinician-led transcription review of every dialectal or developmental possibility.

## References

- [ASHA: Selected Phonological Patterns](https://www.asha.org/practice-portal/clinical-topics/articulation-and-phonology/selected-phonological-patterns/)
- [ASHA: Speech Sound Disorders—Articulation and Phonology](https://www.asha.org/practice-portal/clinical-topics/articulation-and-phonology/)
- [Cambridge Dictionary: *baby* IPA](https://dictionary.cambridge.org/us/pronunciation/english/baby)
