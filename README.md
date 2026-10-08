# LTTC Practice Studio — Liquid Glass

Open `index.html` after extracting this ZIP. All scripts, question data and formula images are included; no installation, API key or paid service is needed.

## Practice

- 1,045 multiple-choice practice items mapped to all 892 original exercise IDs.
- Nine chapters; Test bank / Past paper filters; individual paper/bank filter.
- Mixed practice shuffles original exercise groups while keeping linked parts together.
- Calculation flow: choose formula → check and explanation → calculation choices → original formula, substitution/results and interpretation.
- Correct and incorrect answers both reveal explanations.
- A missed formula remains a mistake even when the calculation answer is correct. Use “Try this question again” to complete both steps correctly.
- Bookmarks, progress and mistakes persist in this browser. Export a backup before changing devices or clearing browser storage. Import accepts this version’s JSON backup.
- Source links open the corresponding page in the included exercise PDF.

## Publish on GitHub Pages

Upload the extracted contents into your repository root, including the `math` folder and `.nojekyll`. Configure Pages to publish the root of your chosen branch. Keep `index.html` at the root rather than inside an additional ZIP folder. The project is plain HTML/CSS/JavaScript and requires no build.

## Source and conversion notes

Source: LTTC_892_Exercises_EN.pdf and LTTC_892_Answers_EN.pdf, supplemented by the existing structured source records and direct checks of identified extraction defects in the supplied original compilation. Source years are retained rather than inferred. Some historical institutional descriptions use the source period’s definitions.

The original 892 identifiers are all represented. Multi-part and written exercises were adapted into linked choices, including individual ratio/common-size table cells. Choices authored for these adaptations are practice choices, not claimed as original exam options. True/False remains a two-choice question.

The five-paper compilation includes supplementary firm-performance practice; this is labeled in the paper filter and source metadata rather than presented as a verified dated exam.

Source limitations and alternative conventions remain in the explanations. Several originals have incomplete information, defective options or inconsistent financial statements. These are not silently assigned fabricated numerical answers. Corrected source extraction includes FIVE-F2-4, FIVE-F2-5 and FIVE-F3-11; the segmentation-theory statement S3-Q64 is False. Original labeled MCQ choices retain their order because some answers refer to other option letters.

Verification: JavaScript syntax, unique IDs, coverage of all 892 source IDs, valid answer indices, nonempty explanations, and availability of all rendered formula assets were checked. Full browser visual/interaction verification could not be completed in the execution environment. The included answers are study solutions, not an independently re-audited official answer key for all questions.

## Files

- index.html — interface
- style.css — responsive dark glass design
- app.js — practice, grading, filters and local progress
- data.js — questions, explanations, source references and formula metadata
- math/ — offline vector mathematical typesetting
- source.pdf — original exercise PDF
- COVERAGE.csv — original IDs mapped to generated practice IDs

No analytics, remote database, login or tracking is used. Progress is device/browser-local, not synchronized across devices.
