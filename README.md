# Jinyuan Li — Personal Website

A one-page personal website for Jinyuan Li, a student at Shenzhen College of International Education, built for college applications. It presents Jinyuan's interests, awards, history research and science projects in five sections, each named with a Latin word.


## Sections

| Section | Latin meaning | Contents |
|---|---|---|
| **Ego** | myself | Name, school, introduction, highlights, and the documentary *The Hundred-Year Influence of Addiction* |
| **Passio** | passion (also suffering, or disease) | Badminton, music, French film, supporting peers, gaming, feasting, sleep, friends |
| **Laurea** | laurel, or triumph | Awards from Grade 9 to Grade 11, newest first |
| **Fabulae** | stories, or myths | History research: John Locke essay, Self-Strengthening Movement paper, French Revolution documentary, 1840 Opium War Debates, Charles Elliot exhibition, Islands of Contention |
| **Ars** | science, or a skill method | Badminton computer-vision project, antibacterial grip, catalysis lab work, YBCO superconductor, chemistry education app |

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole website: content, styling and a small script, all in one file |
| `Website Organisation.docx` | Source text the website was written from |
| `*.pdf` | Local copies of the four papers (the site links to the Google Drive versions) |

## Links used on the site

- John Locke essay: https://drive.google.com/file/d/1oVZAziDlrHvfMrK1qBjnktJClkeMygPh/view
- Self-Strengthening Movement paper: https://drive.google.com/file/d/11DPT1roMaj6LJ1SyZiN5bicZN0eFecwm/view
- 1840 Opium War Debates: https://drive.google.com/file/d/1Bq2FpkpoIY7g7QO7wVCSOVXVgO_BJYsp/view
- Islands of Contention: https://drive.google.com/file/d/1maOhhCAZAE6imSdKDwSYwX3rbwbS60AI/view
- French Revolution documentary: https://youtu.be/-d9eSyiYtLk
- Charles Elliot exhibition: https://charleselliot.framer.website/

## Viewing locally

Double-click `index.html` to open it in a browser. An internet connection is needed for the fonts (Google Fonts) and the Drive and YouTube links.

## Editing

All text lives in `index.html`. Search for the sentence you want to change and edit it directly.

- **Add an award:** copy an existing `<li>` line in the Laurea section. Use `class="medal gold"` for golds and first places, and `class="medal"` for everything else.
- **Add a research story:** copy an `<article class="story">` block in the Fabulae section.
- **Add a science project:** copy an `<article>` block in the Ars section.
- **Change colors or fonts:** edit the variables at the top of the `<style>` block (`--lapis`, `--gilt`, `--display`, `--body` and so on).

## Publishing on your own domain

The file can be hosted on any static host (GitHub Pages, Netlify, Vercel). Before hosting it outside claude.ai, add a standard HTML wrapper at the top of `index.html`:

```html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
```

Then put `</head><body>` after the closing `</style>` tag and `</body></html>` at the very end of the file.

## To do

- Add a link for *The Hundred-Year Influence of Addiction* documentary
- Add food photos to the Feasting card (optional)
- Decide whether to add a contact email to the footer
- Check The Concord Review's policy before sharing the 1840 Opium War paper publicly while it is under review
