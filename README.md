# CS260 Notes Site

Static notes website for Computer Architecture lectures.

## Files

- `index.html` - landing page with links to each lecture
- `lecture_apr14_single_cycle_datapath.html`
- `lecture_apr16_control_path_immgen_jal.html`
- `lecture_apr21_critical_path_and_multicycle_rtl.html`

Each lecture now includes a shared **Course Pages** nav near the top so you can jump between all pages quickly.

## Add a New Lecture

1. Duplicate one existing lecture file and rename it (`lecture_aprXX_topic.html`).
2. Update title/content in that new file.
3. In the new lecture, update the `Course Pages` nav block:
   - Add the new page link.
   - Mark that page with `class="active"`.
4. Add a new card link in `index.html`.

## Host on GitHub Pages

1. Create a new GitHub repo and upload these files.
2. In GitHub: **Settings -> Pages**.
3. Under **Build and deployment**, set:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` (or your default branch), `/ (root)`
4. Save, then open the published URL GitHub shows.

Because lecture images are inlined as data URIs, the pages are self-contained and do not depend on external image hosts.
