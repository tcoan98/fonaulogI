# Advanced 300-Word Phonology Bank

The Phonology Practice Lab now has **two separate curated 300-word banks**. In the **Phonological processes** section, the **Practice word bank** selector offers:

- **Original 300 — foundational**: preserves the original question set.
- **Advanced 300 — 2–3 syllables**: uses the following longer words.
- **All 600 — mixed difficulty**: samples from both banks without repeating a word within a 10-question round.

The bank selector works in **Identify the process**, **Apply a process**, and **Transcribe & apply** modes. Changing it starts a new round; the **Different word** button respects the selected bank.

## Data and validation

- **300 advanced entries** with **300 distinct spellings**, none shared with the original set.
- **217 two-syllable words** and **83 three-syllable words**, checked against first-pronunciation syllable counts in the CMU Pronouncing Dictionary.
- **16 process categories**, with **18 or 19 dedicated entries** each.
- Each curated example has a broad American English IPA target, an illustrative whole-word transformed production, and an explanatory sound-change description.
- The site's own process validator confirms that all 300 transformations match their indicated process; e.g., no curated answer starts with [ŋ], backing/assimilation constraints are checked, and deletions and replacements match their sound-change positions.
- **35 advanced words** with relevant unstressed final /i/ also accept /ɪ/ as an alternative transcription under the classroom convention. IPA stress marks remain omitted from learner-facing displays.
- The existing original 300 remain unchanged.

**Important:** These are **illustrative educational productions**, not claims that every child produces these forms or that every dialect shares a single transcription. Orthographic words and CMU pronunciations were manually organized by process, but a dictionary-based and automated check is not a substitute for a clinical or dialect-specific review.

## New words by process

| Process | Words | Word list |
| --- | ---: | --- |
| Stopping | 19 | very, father, several, southern, city, sister, seven, silver, finally, serious, silent, visitor, second, sympathy, fashion, famous, fifteen, feather, victory |
| Deaffrication | 19 | chapter, children, general, gentleman, justice, genius, journey, generous, charity, gentle, cheerful, joyful, junction, childhood, jumping, charcoal, jealousy, chocolate, champion |
| Fronting | 19 | country, garden, corner, candy, candle, camera, carrot, caper, cooker, gummy, golden, gooseberry, grocery, gallon, goblin, gathering, coconut, calendar, cucumber |
| Depalatalization | 18 | shortening, shaking, shining, shipping, shelter, shadows, shopkeepers, shivering, shallow, shortsighted, shudder, shovel, shuffling, shaving, shooting, shampoo, shopping, shoulder |
| Backing | 19 | disease, different, terrible, daughter, divided, danger, distance, division, desire, deeply, delight, domain, decision, decided, dollars, daily, dinosaur, telephone, tender |
| Gliding | 19 | liberty, regular, lemon, laundry, ribbon, reason, river, rainy, running, raccoon, rainbow, lollipop, luggage, lateral, ruler, roller, republic, recess, robin |
| Vocalization | 18 | elbow, pencil, purple, hospital, angle, tunnel, rattle, bubble, single, giggle, jungle, uncle, castle, sandal, practical, animal, beautiful, bicycle |
| Cluster Reduction | 19 | specific, primary, stomach, spaghetti, president, stapler, speaker, squirrel, sweater, snowman, princess, present, plastic, blanket, flower, gravity, tractor, dragon, criminal |
| Reduplication | 18 | panda, window, muffin, wagon, pillow, robot, pickle, hippo, puddle, honey, basket, napkin, bingo, cannon, kangaroo, monkey, zebra, donut |
| Weak Syllable Deletion | 18 | begin, become, believe, removal, below, attack, between, companion, avoid, police, defeat, convention, supply, surprise, remember, computer, consider, forget |
| Final Consonant Deletion | 19 | sunset, carpet, falcon, planet, rocket, triangle, magnet, snowball, skeleton, cactus, peanut, helmet, wallet, pumpkin, sandwich, melon, elephant, dolphin, cabin |
| Labial Assimilation | 19 | number, topic, tulip, temperature, topping, tippy, timber, tumble, tummy, teapot, dumbbell, double, december, dimple, copper, campus, cabbage, company, comedy |
| Alveolar Assimilation | 19 | pudding, position, paddle, puzzle, pocket, piston, pottery, battery, popular, balance, bacon, ballet, canyon, cattle, gallery, gadget, galaxy, barrel, budget |
| Velar Assimilation | 19 | technical, direction, document, talking, taking, ticking, ticker, tango, toggle, target, tugboat, tucking, tickle, typical, teaching, digging, dagger, donkey, doctor |
| Prevocalic Voicing | 19 | paper, possible, pigeon, pepper, piano, pizza, people, penguin, penny, petal, teacher, tissue, tendency, cousin, color, family, ferry, silly, sensation |
| Devoicing | 19 | united, lizard, wizard, liquid, forward, cupboard, backyard, onward, mustard, pyramid, bulldog, hotdog, ladybug, catalog, hedgehog, otherwise, creative, massive, buses |

## Sample IPA transformations

| Process | Adult word | Adult IPA | Illustrative production |
| --- | --- | --- | --- |
| Stopping | very | /vɛɹi/ | [bɛɹi] |
| Deaffrication | chapter | /tʃæptɚ/ | [ʃæptɚ] |
| Fronting | country | /kʌntɹi/ | [tʌntɹi] |
| Depalatalization | shortening | /ʃɔɹtənɪŋ/ | [sɔɹtənɪŋ] |
| Backing | disease | /dɪziz/ | [ɡɪziz] |
| Gliding | liberty | /lɪbɚti/ | [wɪbɚti] |
| Vocalization | elbow | /ɛlboʊ/ | [ɛʊboʊ] |
| Cluster Reduction | specific | /spəsɪfɪk/ | [pəsɪfɪk] |
| Reduplication | panda | /pændə/ | [pænpæn] |
| Weak Syllable Deletion | begin | /bɪɡɪn/ | [ɡɪn] |
| Final Consonant Deletion | sunset | /sʌnsɛt/ | [sʌnsɛ] |
| Labial Assimilation | number | /nʌmbɚ/ | [mʌmbɚ] |
| Alveolar Assimilation | pudding | /pʊdɪŋ/ | [tʊdɪŋ] |
| Velar Assimilation | technical | /tɛknɪkəl/ | [kɛknɪkəl] |
| Prevocalic Voicing | paper | /peɪpɚ/ | [beɪpɚ] |
| Devoicing | united | /junaɪtɪd/ | [junaɪtɪt] |

## Implementation notes

The data is embedded in `index.html` in the `advancedProcessQs` array, alongside the original `originalProcessQs`. This documentation lists the same entries for auditing; **editing this Markdown file does not update the quiz**.

References: [Carnegie Mellon University Pronouncing Dictionary](https://github.com/cmusphinx/cmudict) and [ASHA: Selected Phonological Patterns](https://www.asha.org/practice-portal/clinical-topics/articulation-and-phonology/selected-phonological-patterns/).
