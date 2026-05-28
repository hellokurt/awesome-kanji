# Awesome Japanese Kanji Resources

A curated list of open-source libraries, datasets, learning tools, etymology resources, stroke-order tools, and Anki decks for studying Japanese kanji.

> **Scope:** Japanese kanji resources, developer libraries, open datasets, stroke-order tooling, handwriting tools, etymology references, study apps, and Anki decks/add-ons.

## Contents

- [Legend](#legend)
- [Open Data, APIs, Dictionaries, and Developer Libraries](#open-data-apis-dictionaries-and-developer-libraries)
- [Stroke Order, Handwriting, Decomposition, Radicals, and Frequency](#stroke-order-handwriting-decomposition-radicals-and-frequency)
- [Open-Source Apps, Study Tools, and Kanji Practice Sites](#open-source-apps-study-tools-and-kanji-practice-sites)
- [Kanji Etymology, Radicals, and Character History](#kanji-etymology-radicals-and-character-history)
- [Anki Decks, Add-ons, and Deck Generators](#anki-decks-add-ons-and-deck-generators)
- [Meta Lists and Broader Japanese-Learning Collections](#meta-lists-and-broader-japanese-learning-collections)
- [Contributing](#contributing)
- [License](#license)

## Legend

- **Free** means the resource is publicly accessible or open-source.
- **Freemium** means there is a free tier plus paid features or content.
- **Paid** means the resource is primarily commercial.
- **License not specified** means no clear public license was found; verify before redistributing.
- Licenses listed here refer to the cited resource where stated. They do **not** automatically apply to this curated list.

---

## Open Data, APIs, Dictionaries, and Developer Libraries

| Resource | Description | Access | License / Terms |
|---|---|---:|---|
| [KanjiVG](https://kanjivg.tagaini.net/) | Canonical SVG stroke-order and stroke-group dataset for Japanese kanji, useful for animation, recognition, worksheets, and component analysis. | Free | CC BY-SA 3.0 |
| [KANJIDIC2](https://www.edrdg.org/wiki/index.php/KANJIDIC_Project) | EDRDG XML dictionary with readings, meanings, radicals, stroke counts, grades, frequency, and metadata for thousands of kanji. | Free | CC BY-SA 4.0 |
| [Kanji alive data/media](https://github.com/kanjialive/kanji-data-media) | Open data package behind Kanji alive: radicals, kanji metadata, audio, and SVG animations for pedagogically selected kanji. | Free | CC BY 4.0 |
| [Kanji alive web app / API source](https://github.com/kanjialive/kanji-web-app) | Web app and public API for searching kanji by meaning, readings, stroke count, radicals, grade, and study lists. | Free | Apache-2.0 code; Creative Commons data/media |
| [Kanji alive MCP server](https://github.com/kanjialive/kanjialive-mcp-server) | MCP server exposing Kanji alive kanji/radical data to AI tools and agents. | Free API tier | MIT code; CC BY 4.0 data/media |
| [Kanjium](https://github.com/mifunetoshiro/kanjium) | Aggregated kanji resource combining readings, meanings, variants, decompositions, phonetic data, examples, and cross-links. | Free | CC BY-SA 4.0 |
| [kanjiapi.dev](https://kanjiapi.dev/) | JSON API and dataset for kanji and Japanese word data, including thousands of kanji endpoints. | Free | MIT code; source data follows upstream EDRDG/KANJIDIC terms |
| [kanjiapi.dev source](https://github.com/onlyskin/kanjiapi.dev) | Source repository for kanjiapi.dev and related data generation. | Free | MIT code; data follows upstream licenses |
| [sepTN/kanji-data](https://github.com/sepTN/kanji-data) | Offline Node.js kanji database package built from kanjiapi.dev and EDRDG sources. | Free | MIT |
| [jmdict-simplified](https://github.com/scriptin/jmdict-simplified) | Simplified, structured JSON releases of JMdict, JMnedict, KANJIDIC, and related dictionaries for app developers. | Free | Project CC BY-SA 4.0; npm packages MIT; derived data follows upstream terms |
| [jmdict-yomitan](https://github.com/yomidevs/jmdict-yomitan) | Automatically generated Yomitan dictionaries for JMdict, KANJIDIC, JMnedict, and other Japanese dictionary sources. | Free | MIT code; dictionary data follows upstream licenses |
| [Yomitan](https://github.com/yomidevs/yomitan) | Open-source browser extension for Japanese popup lookup, kanji stroke-order display, and Anki card creation. | Free | GPL-3.0 |
| [MarvNC/yomitan-dictionaries](https://github.com/MarvNC/yomitan-dictionaries) | Large community collection of Yomitan dictionaries, including kanji info, frequency, variants, and name dictionaries. | Free | Varies by dictionary; verify each source |
| [Jamdict](https://github.com/neocl/jamdict) | Python 3 library for JMdict, KANJIDIC2, JMnedict, KRADFILE/RADKFILE, and Japanese dictionary lookup workflows. | Free | MIT |
| [kanji.js](https://kanji.js.org/) | JavaScript library for kanji search and lookup, with browser and Node.js support. | Free | MIT |
| [Kuroshiro](https://github.com/hexenq/kuroshiro) | JavaScript Japanese text converter for hiragana, katakana, romaji, furigana, and okurigana-style transformations. | Free | MIT |
| [Wacton.Desu](https://github.com/waacton/Desu) | .NET Japanese and kanji dictionary library built on JMdict, JMnedict, KANJIDIC, RADKFILE/KRADFILE, and KanjiVG. | Free | CC BY-SA 4.0 |
| [Japanese/Kanji Dictionary C# library](https://software.seekye.com/jkdic) | C# library exposing subsets of JMdict and KANJIDIC2 for Japanese and kanji dictionary applications. | Free | Zlib-style license |
| [Kanji Database Project](https://kanji-database.sourceforge.net/index.html?lang=en) | CJK Unified Ideographs data project with kanji-oriented database files distributed through GitHub. | Free | GPL and MIT |
| [Kanji Database](https://www.kanjidatabase.com/) | Web-accessible database for Joyo kanji with search and downloadable CSV data. | Free | License not specified |

---

## Stroke Order, Handwriting, Decomposition, Radicals, and Frequency

| Resource | Description | Access | License / Terms |
|---|---|---:|---|
| [animCJK](https://github.com/parsimonhi/animCJK) | Stroke-by-stroke animated SVG assets for Chinese, Japanese, and Korean characters, including many Japanese characters. | Free | Arphic Public License for graphics/SVG; LGPL for other files |
| [kanjivg-js](https://github.com/tempo-eng/kanjivg-js) | TypeScript/React library for searching, displaying, and animating KanjiVG stroke data. | Free | KanjiVG-derived data CC BY-SA 4.0; verify code license |
| [kanji-recognizer](https://github.com/mxggle/kanji-recognizer) | Lightweight dependency-free JavaScript library for stroke-order recognition and validation using KanjiVG. | Free | MIT |
| [kanji-colorize](https://github.com/cayennes/kanji-colorize/) | Script and Anki-oriented tooling for colored stroke-order diagrams generated from KanjiVG. | Free | AGPLv3+ code; SVG output based on KanjiVG CC BY-SA 3.0 |
| [kanji2gif](https://github.com/shuuryou/kanji2gif) | Tool for generating animated GIFs for kanji, hiragana, katakana, and symbols, often used in Anki workflows. | Free | AGPL-3.0 |
| [Kanji.gif](https://github.com/jcsirot/kanji.gif/) | Collection of animated GIFs for Japanese kanji and kana, generated from KanjiVG/Kanimaji-style sources. | Free | Images CC BY-SA 3.0; scripts GPL-3.0 |
| [AegisKan](https://dmirtao.github.io/AegisKan/) | JavaScript renderer/animator for kanji stroke animations using KanjiVG. | Free | License not specified |
| [KanjiVG Explorer](https://fasiha.github.io/kanjivg-explorer/) | Visual explorer for KanjiVG hierarchy and Joyo kanji structure, including Heisig-order views. | Free | License not specified |
| [TopoKanji](https://github.com/scriptin/topokanji) | Kanji learning-order generator based on components, frequency, school grade, JLPT, WaniKani, and Anki-ready outputs. | Free | Mixed: Apache-2.0, CC BY 4.0, EPL-1.0, LGPL-3.0, or MIT depending on file/source |
| [kanji-frequency](https://github.com/scriptin/kanji-frequency) | Kanji frequency datasets built from multiple corpora and exported for analysis or learning-order design. | Free | CC BY 4.0 |
| [kanjistat](https://dschuhmacher.github.io/kanjistat/) | R package and datasets for kanji morphology, decomposition, similarity, and statistical analysis. | Free | Derived data includes CC BY-SA 4.0 sources; verify package license |
| [CJKVI IDS](https://github.com/cjkvi/cjkvi-ids) | Ideographic Description Sequence data for CJK Unified Ideographs, useful for component/decomposition research. | Free | Mixed: CHISE-derived terms and GPLv2 data |
| [CHISE IDS](https://gitlab.chise.org/CHISE/ids) | CHaracter Information Service Environment data and utilities for IDS/decomposition-style character research. | Free | Common mirrors indicate GPL-2.0; verify upstream terms |
| [cjk-decomp](https://github.com/amake/cjk-decomp) | Decomposition database for Chinese/Japanese characters; older but still useful for component experiments. | Free | Multiple license options including Apache-2.0, LGPL-3.0, CC BY-SA 3.0, MIT, ODC-By 1.0, and EPL |
| [cjkradlib](https://github.com/patarapolw/cjkradlib) | Python library generating compositions, supercompositions, and variants for Hanzi/Kanji from CJKVI IDS data. | Free | MIT |
| [KentVu/kanji-decomposition](https://github.com/KentVu/kanji-decomposition) | Small kanji decomposition tool/database based on RADKFILE. | Free | GPL-3.0 |
| [cjkvi-ids-unicode](https://github.com/Transfusion/cjkvi-ids-unicode) | Unicode-only conversion of CJKVI IDS data for easier processing in modern pipelines. | Free | Products GPL-2.0-or-later; code dual MIT/GPL-2.0-or-later |
| [kanji.sh](https://github.com/rionlabs/kanji.sh) | Printable kanji worksheet generator by JLPT, grade, WaniKani level, frequency, and custom lists. | Free | MIT |
| [ichimiginikarasu](https://github.com/makemeunsee/ichimiginikarasu) | Tool for generating printable kanji flashcards automatically. | Free | License file present; verify exact license |

---

## Open-Source Apps, Study Tools, and Kanji Practice Sites

| Resource | Description | Access | License / Terms |
|---|---|---:|---|
| [KanjiDraw.com](https://kanjidraw.com/) | Browser-based kanji drawing and puzzle site for practicing strokes, readings, kana, and kanji levels. | Free to access | License not specified |
| [obfusk/kanjidraw](https://github.com/obfusk/kanjidraw) | Python library and GUI for handwritten kanji recognition using stroke data derived from KanjiVG. | Free | AGPL-3.0 code; stroke database based on KanjiVG CC BY-SA data |
| [TraceKanji](https://github.com/sicfran774/TraceKanji) | Kanji study tool with handwriting recognition, SRS-style custom decks, KanjiVG strokes, and KanjiAPI data. | Free | GPL-3.0 |
| [Kanji Dojo](https://kanji-dojo.com/) | Open-source multiplatform kanji learning app with SRS, handwriting practice, offline use, and thousands of characters. | Freemium | GPL-3.0; free core content, optional paid extras |
| [Kanji Koohii](https://github.com/fabd/kanji-koohii) | Web app for remembering kanji with user stories and Heisig/RTK-style study workflows. | Free | AGPL-3.0 code; some RTK-related assets/keywords have separate restrictions |
| [Hanabira](https://github.com/tristcoil/hanabira.org) | Open-source Japanese learning platform with SRS, parsing, dictionaries, and kanji-related learning features. | Free | MIT code; in-house content under Creative Commons |
| [Kanji alive](https://kanjialive.com/) | Pedagogical kanji study web app with radicals, stroke animations, readings, meanings, examples, and textbook lists. | Free | Apache-2.0 code; CC BY 4.0 data/media |
| [KanjiDamage](https://www.kanjidamage.com/) | Humorous kanji learning site covering around 1,700 kanji with radicals, usefulness ranking, mnemonics, and Anki support. | Free | License not specified |
| [Kanji Mastery](https://kanji-mastery.com/) | Free web-based JLPT kanji practice tool with meanings, readings, stroke order, and example sentences. | Free | License not specified |
| [PracticeKanji](https://www.practicekanji.com/) | Customizable kanji learning app with thousands of kanji and vocabulary items. | Free to use | License not specified |
| [Kanji Garden](https://www.tofugu.com/japanese-learning-resources-database/kanji-garden/) | Mnemonic-based SRS kanji learning web app covering thousands of kanji. | Free to access | License not specified |
| [Kanshudo](https://www.kanshudo.com/) | Large Japanese learning site with kanji lessons, flashcards, games, and kanji study tools. | Free core / freemium | Proprietary; no open license specified |
| [WaniKani](https://www.wanikani.com/) | Popular radicals-kanji-vocabulary SRS app using mnemonics and spaced repetition. | Freemium / paid subscription | Proprietary; no open license for content |
| [Manji](https://github.com/Livinglist/Manji) | Mobile Japanese dictionary/study app with handwriting recognition, image kanji extraction, cards, and quizzes. | Free | MIT |
| [jiten](https://github.com/obfusk/jiten) | Android/CLI/web Japanese dictionary with kanji dictionary, handwritten recognition, and stroke-order support. | Free | AGPL-3.0 |
| [Furigana Maker](https://github.com/aiktb/furiganamaker) | Browser extension adding furigana to Japanese text with JLPT-aware filtering. | Free | MIT |
| [Fun With Kanji](https://f-droid.org/packages/krillefear.funwithkanji/) | Open-source Android app for studying radicals and the Joyo kanji with dictionary/search features. | Free | MPL-2.0 |
| [DaKanji](https://github.com/CaptainDario/DaKanji) | Japanese study app with offline dictionary, drawing recognition, furigana, and kanji-related features. | Free | License not clearly surfaced; verify repository |
| [KanaDojo](https://github.com/lingdojo/kana-dojo) | Web-based open-source platform for hiragana, katakana, kanji, vocabulary, and grammar practice. | Free | License not clearly surfaced; verify repository |

---

## Kanji Etymology, Radicals, and Character History

| Resource | Description | Access | License / Terms |
|---|---|---:|---|
| [Genetic Kanji](https://www.genetickanji.com/) | Etymology-centered kanji course that teaches characters step-by-step from earlier forms and component history. | Free / freemium elements | License not specified |
| [Brad Warden's Kanji Etymology](https://www.bradwarden.com/kanji/etymology/) | Free kanji origin reference ordered by grade, stroke count, frequency, and JLPT-style categories. | Free | License not specified |
| [RakuGo Kanji Etymology Graph](https://rakugo.app/kanji) | Interactive graph visualization of kanji etymology and relationships between characters/components. | Free | License not specified |
| [Kanji Portraits](https://kanjiportraits.wordpress.com/) | Blog/project explaining origins, radicals, and historical structure of Joyo kanji. | Free blog + paid book/eBook | License not specified for blog content |
| [Wiktionary: Japanese kanji category](https://en.wiktionary.org/wiki/Category:Japanese_kanji) | Massive collaboratively edited kanji reference with character pages, meanings, readings, and etymology sections where available. | Free | CC BY-SA 4.0 |
| [Wikibooks: Japanese/Kanji](https://en.wikibooks.org/wiki/Japanese/Kanji) | Free introductory kanji learning guide hosted by Wikibooks. | Free | Wikimedia content licensing, generally CC BY-SA 4.0 |
| [Tofugu: Learn Kanji with Radicals and Mnemonics](https://www.tofugu.com/japanese/kanji-radicals-mnemonic-method/) | Practical free guide to learning kanji through radicals, stories, and mnemonics. | Free | License not specified |
| [Wasabi: 51 Key Radicals](https://wasabi-jpn.com/magazine/japanese-lessons/just-51-key-radicals-how-to-memorize-kanji/) | Free guide to important kanji radicals, meanings, and examples. | Free | License not specified |
| [Hanabira Radical Guide](https://hanabira.org/radicals) | Complete kanji radicals guide with meanings and stroke counts. | Free | Project has MIT code and Creative Commons content terms; verify page-level terms |
| [Kanjijo etymology guide](https://kanjijo.com/blog/kanji-etymology-origins.html) | Free article explaining historical kanji formation, oracle-bone origins, and phonosemantic characters. | Free | License not specified |
| [Ichiyo kanji origins article](https://ichilearning.com/origins-of-kanji/) | Free article explaining how kanji characters were created and classified. | Free | License not specified |
| [KanjiDamage radicals](https://www.kanjidamage.com/) | Radical/component reference integrated with KanjiDamage's mnemonics and kanji ordering. | Free | License not specified |
| [Learn Kanji Through Real Etymology](https://learn.japanology.nl/kanji-learning.php) | Etymology-focused learning course with sample kanji and full JLPT coverage behind a paid/freemium model. | Freemium / paid | Proprietary; no open license specified |
| [Outlier Linguistics](https://www.outlier-linguistics.com/) | Professional character etymology dictionaries and learning tools for Japanese/Chinese character structure. | Paid | Proprietary |
| [The Complete Guide to Japanese Kanji](https://books.google.com/books/about/Complete_Guide_to_Japanese_Kanji.html?id=W_CMCwAAQBAJ) | Paid Henshall/Seeley reference explaining Joyo kanji with historical development notes. | Paid book | Proprietary book copyright |
| [Kodansha Kanji Learner's Course](https://kodansha.us/book/the-kodansha-kanji-learners-course/) | Paid course/reference covering 2,300 kanji with systematic learning order and mnemonics. | Paid book | Proprietary book copyright |
| [Remembering the Kanji](https://books.google.com/books/about/Remembering_the_Kanji_1.html?id=PYOUEAAAQBAJ) | Classic Heisig method for associating kanji writing with meanings through imaginative memory. | Paid book | Proprietary book copyright |

---

## Anki Decks, Add-ons, and Deck Generators

| Resource | Description | Access | License / Terms |
|---|---|---:|---|
| [vitalii-bekshnev/jlpt-anki-decks](https://github.com/vitalii-bekshnev/jlpt-anki-decks) | Auto-updated JLPT Anki decks, including complete kanji decks and large vocabulary exports. | Free | Derived data includes JMdict/EDRDG, KANJIDIC2 CC BY-SA 4.0, and Tatoeba CC BY 2.0 FR terms |
| [jamsinclair/open-anki-jlpt-decks](https://github.com/jamsinclair/open-anki-jlpt-decks) | Open-source, updatable JLPT vocabulary Anki decks maintained as CSV and releases. | Free | MIT |
| [Official KanjiDamage Anki deck](https://www.kanjidamage.com/) | Official Anki deck for KanjiDamage, including KanjiDamage kanji and stroke-order diagrams. | Free | License not specified |
| [KanjiDamage Plus+](https://ankiweb.net/shared/info/183869315) | Expanded/reworked KanjiDamage-style Anki deck with updated mnemonics and organization. | Free | License not specified |
| [KanjiDamage with Core6k Vocab](https://ankiweb.net/shared/info/224499651) | KanjiDamage-derived Anki deck combining kanji meanings, onyomi, and Core6k-style vocabulary. | Free | License not specified |
| [kd-kanji-and-vocab](https://github.com/spejamchr/kd-kanji-and-vocab) | KanjiDamage-order deck/project pairing kanji, onyomi, and vocabulary after each kanji. | Free | License not clearly surfaced; verify repository |
| [Japanese 300 Beginner Kanji](https://ankiweb.net/shared/info/1055165940) | Beginner kanji Anki deck with onyomi, kunyomi, meanings, and vocabulary-card support. | Free | License not specified |
| [All in One Kanji Deck](https://ankiweb.net/shared/info/1606853709) | Large Anki deck covering Joyo, JLPT N5-N1, Jinmeiyo, frequency lists, and Heisig-style ordering. | Free | License not specified |
| [RRTK Recognition Remembering the Kanji v2 with tags](https://ankiweb.net/shared/info/1865376115) | Recognition RTK-style Anki deck with added tagging. | Free | License not specified |
| [RRTK Recognition Remembering the Kanji](https://anki-decks.com/anki-decks/japanese/rrtk-recognition-remembering-the-ka/) | Public recognition-focused RTK-style Anki deck with thousands of cards. | Free | License not specified |
| [N5 Kanji Japanese Top 80+](https://ankiweb.net/shared/info/106960747) | N5 kanji deck with commonly used beginner kanji and image support. | Free | License not specified |
| [Official KanjiDamage deck - reordered](https://anki-decks.com/anki-decks/japanese/official-kanjidamage-deck-reordered/) | Reordered variant of the official KanjiDamage Anki deck. | Free | License not specified |
| [Advanced Kanji Grid](https://ankiweb.net/shared/info/1907244465) | Anki add-on that builds an interactive kanji grid from your decks and sorts by JLPT, Joyo, Kanken, frequency, and more. | Free | License not specified |
| [Colorized Kanji Stroke Importer](https://ankiweb.net/shared/info/119224044) | Anki add-on inserting static SVG stroke-order diagrams based on KanjiVG data. | Free | License not specified on AnkiWeb page; KanjiVG data has CC BY-SA terms |
| [Jisho Kanji Stroke Order Anki add-on](https://ankiweb.net/shared/info/1619328930) | Anki add-on for kanji stroke-order display, explicitly licensed to align with KanjiVG requirements. | Free | CC BY-SA 3.0 |
| [KanjiVocab](https://shigeyukey.github.io/shige-addons-wiki/KanjiVocab.html) | Anki add-on that adds known vocabulary examples to kanji-writing decks such as RTK-style decks. | Free | License not specified |
| [Migaku Kanji Addon](https://github.com/migaku-official/Migaku-Kanji-Addon) | Anki add-on for learning kanji in the context of vocabulary, with metadata, mnemonics, lookup, and production/recognition cards. | Free / open-source | GPL-3.0 |
| [anki-kunren](https://github.com/eshrh/anki-kunren) | Interactive kanji writing drill add-on for Anki with stroke-order practice powered by KanjiVG. | Free | GPL-3.0; KanjiVG data CC BY-SA 3.0 |
| [kanji2gif for Anki](https://github.com/shuuryou/kanji2gif) | Generator for animated kanji/kana GIFs that can be inserted into Anki decks. | Free | AGPL-3.0 |
| [kanji-colorize for Anki](https://github.com/cayennes/kanji-colorize/) | Generates colorized SVG stroke-order diagrams, commonly used for static stroke-order cards. | Free | AGPLv3+ code; SVG based on KanjiVG CC BY-SA 3.0 |
| [ichimiginikarasu flashcard generator](https://github.com/makemeunsee/ichimiginikarasu) | Printable kanji flashcard generator that can complement Anki-style study workflows. | Free | License file present; verify exact license |
| [Heisig RTK index / templates](https://github.com/cyphar/heisig-rtk-index) | RTK-oriented index and templates for recognition/production-style Anki workflows. | Free to access | License not specified |

---

## Meta Lists and Broader Japanese-Learning Collections

| Resource | Description | Access | License / Terms |
|---|---|---:|---|
| [Awesome Japanese](https://github.com/yudataguy/Awesome-Japanese) | Curated GitHub list of Japanese learning resources, including kanji-related tools, apps, decks, and dictionaries. | Free | License not clearly surfaced |
| [Awesome Japanese Learning Resources](https://github.com/ailanguagetutor/awesome-japanese-learning-resources) | Curated list of Japanese-learning materials and tooling; useful for discovering adjacent kanji resources. | Free | Apache-2.0 |
| [Learning Japanese resource list](https://github.com/dubeyanant/Learning-Japanese) | GitHub resource list referencing KanjiDamage, WaniKani, RTK, KLC, Anki decks, and other study materials. | Free | License not clearly surfaced |

---

## Contributing

Contributions are welcome.

Please add resources in this format:

```md
| [Resource Name](https://example.com/) | One-line factual description. | Free / Freemium / Paid | MIT / GPL-3.0 / CC BY-SA 4.0 / License not specified |
```

Guidelines:

- Prefer official links.
- Include license information when available.
- Keep descriptions short and factual.
- Mark paid, proprietary, and freemium resources clearly.
- Do not add pirated decks, copyrighted book scans, or unauthorized mirrors.
- For decks or dictionaries based on third-party data, include upstream license notes where possible.

## License

This curated list is released under [CC0 1.0 Universal](LICENSE).

Individual resources linked here are owned by their respective authors and may use different licenses or terms.
