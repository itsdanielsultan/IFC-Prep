# IFC Prep

A free, independent study companion for **Investment Funds in Canada (IFC)**, offered by the Canadian Securities Institute. Created by Daniel Sultan, following [InvestmentRegulation.ca](https://investmentregulation.ca/).

Study at **[IFCPrep.ca](https://ifcprep.ca/)**. The public source is available at [itsdanielsultan/IFC-Prep](https://github.com/itsdanielsultan/IFC-Prep).

Open `index.html` in a modern browser. The app, content, styles, icons and local-font choices are self-contained: no package installation, build step, account or external runtime dependency is required. Downloaded HTML works offline; linked source pages require internet access.

The black-and-white stacked study-card favicon is embedded as a tiny SVG for sharp browser tabs, including in the downloaded HTML. `favicon.ico` supplies 16, 32 and 48 pixel fallbacks; `apple-touch-icon.png` supplies a 180 pixel home-screen icon. `favicon.svg` is the editable vector source. Serve these files beside the HTML for the hosted fallbacks.

The site includes:

- **54 original lessons in 18 chapters**, examples, chapter recaps, printable revision notes and **108 foundational lesson checks**. Lessons teach before checking understanding; completion requires correct answers to both checks. Core teaching and the example appear first; extended topic notes are available in a native Read more disclosure and remain included in printable notes.
- A **Study Companion reader** with 18 chapters of original notes, formulas, common mistakes and 54 revealable self-checks. Read one chapter at a time or print a chapter/the whole companion, including answers. The reader does not change lesson completion or scored practice.
- A separate **324-question assessment bank**, including **100 calculations**, used for practice, speed rounds and mock papers. Questions have original scenarios, explanations and public primary-source links.
- **162 flashcards** with adaptive scheduling, due/unseen/scheduled counts, chapter cram, revealed-card swipe ratings, keyboard/buttons, undo and a confirmed schedule-only reset.
- **18 chapter workshops** with **54 worked examples** and **108 written-answer exercises**, model answers, reasoning and common mistakes. Draft responses and self-check ratings save locally and are included in progress backups. Ratings are not automatic marks or lesson completion. Printable notes include the workshop solutions.
- **100-question full papers and 50-question half papers**, with optional 180/90-minute clocks, question/answer shuffle preferences, optional auto-next, flags, navigation, saved progress and sequential answer review. Full papers follow the published IFC topic counts; half papers use proportional rounding. Different attempts can reuse bank questions.
- Topic and mistake practice, speed rounds, lesson/question bookmarks, a combined saved-items browser, topic accuracy, a searchable **71-term glossary** and JSON progress export/import.

Progress stays in browser local storage. Export a backup before clearing browser data or moving to another browser/site address. If storage is unavailable, the app shows a notice and works in memory. A timed mock’s clock continues while the page is closed; an untimed paper has no countdown. Progress statistics include repeated attempts and retain the latest 4,000 answer attempts.

A recurring Back control returns to the appropriate parent page and keeps active study sessions available to resume. Practice queues, shuffled answer order, flashcard face/queue/Undo and unfinished lesson checks now survive refresh and closing the page; progress backups include those small session snapshots. Older version 1 backups remain readable. Flashcards turn as two persistent faces, keep swipe ratings and Undo, and respect reduced motion. The visual design uses Daniel CIRE’s original stylesheet and components: black navigation, ruled rows, chapter colours, circular study-mode markers, square flashcards and a phone navigation sheet. The original local Helvetica font stack and measured spacing are retained.

On phones, a revealed flashcard follows the finger's full curved path and keeps the same card through release. Swipes, buttons and keyboard use CIRE's throw and fade; short drags and cancellations do not grade. Reduced motion keeps direct dragging without rotation or an automatic throw. Scroll long answers from the space around the card, or scroll while the card is unrevealed. Selecting the current page closes the phone menu. The page and browser theme colours match the current InvestmentRegulation.ca light and dark themes.

Chapter recaps link directly to their workshops and scored questions. A Review row appears when there are due cards, missed assessment questions or written exercises marked Needs review; these items share one queue within Training. Scheduled card review uses only cards that are due; new cards remain in the learning tool. Revisiting an exercise starts with its solution hidden. The six first-chapter checks use more plausible alternatives and optional explanations for each choice; their IDs and answer indices remain compatible. The separate 324-question assessment bank is unchanged.

The interface supports light/dark themes, whole-interface scaling, additional reading-size adjustments, keyboard navigation, reduced motion and a skip link. On phones, a context/progress header and fixed study controls keep actions within reach, with safe-area spacing and scroll locking while navigation is open. Answer shortcuts 1–4 or A–D follow the displayed choice order. Flashcards support reveal, then 1 for Again or 2 for Got it, with button alternatives.

The content follows CSI’s public curriculum and topic grouping. Teaching was checked against all 18 chapters of the supplied IFC textbook and all 180 section-quiz stems and answer-choice lists. The EPUB filename contains 2024, while its package metadata records a 2025 revision; follow current enrolled-course updates for examinable details. The lessons include 87 named teaching subsections, with selected current-rule differences identified. It supports study and does not replace the purchased course, promise exhaustive coverage, certify readiness or establish eligibility for registration or employment. Questions are independently authored practice, not official or recalled exam questions. **IFC Prep is not affiliated with or endorsed by CSI.** See [CSI’s exam requirements](https://www.csi.ca/en/learning/courses/ifc/exam-credits) and [study tools](https://www.csi.ca/en/learning/courses/ifc/study-tools).

The workshops were cross-checked with the supplied study companion and official EPUB. Despite a filename containing 2024, the EPUB package records a 2025 revision; its introduction describes early-2024 preparation. Historical tax figures are not presented as current limits, and calculations state their assumptions.

Content review: **October 4, 2026**. The six revised opening checks and the public Study Companion reader were additionally reviewed on **October 10, 2026**. Public primary sources support the teaching and are linked from lessons, questions and the About page. Regulations, tax rules and exam requirements can change; consult the current official sources and enrolled-course updates. No purchased course files, proprietary question bank, private course URLs or personal records are included in this release.

There is no advertising, analytics, external-font service or tracking code. Study data is not transmitted by the app. Browser or hosting-provider access logs may exist when the hosted page is opened. Public source links open third-party sites with their own practices.

The release is a static site published through GitHub Pages at `ifcprep.ca`, with HTTPS enforced. Serve `index.html`, the favicon files, `LICENSE` and this README with a static host; no server processing is needed. The expanded HTML is 1,046,762 bytes before compression (about 311 KB with gzip when enabled by the host).

App code and original study content are **MIT licensed**, copyright 2026 Daniel Sultan. Third-party source materials remain under their owners’ terms. Feather icons retain their MIT copyright notice in `LICENSE`.
