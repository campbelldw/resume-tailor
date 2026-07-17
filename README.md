# Resume Tailor

Paste your resume and a job posting, and get back a tailored, printable resume plus a keyword match report. Everything runs in your browser: no accounts, no uploads, no AI. Nothing you paste leaves your machine.

## Use it

1. Download `index.html` (Code > Download ZIP, or just save the raw file) and double-click it. Any modern browser works, and it runs fully offline.
2. Paste your resume as plain text on the left (copy it straight out of your document) and the full job posting on the right.
3. Click **Tailor my resume**. You get:
   - Your resume re-laid-out, with bullets reordered so the strongest matches for this posting come first
   - Highlights on every keyword you already match
   - A red list of words the posting repeats that your resume never says. **Only add what's true for you.** These are prompts for real experience you forgot to mention, not an invitation to invent any.
   - Wording alignments: places where you and the posting mean the same thing but spell it differently (k8s vs Kubernetes). Strict keyword filters care about exact wording.
4. Click any text on the sheet to edit it. The small dash button beside a bullet drops it from the printed copy.
5. **Print / save as PDF** gives you a clean copy with the highlights and analysis stripped out.

Tip: resumes parse best when section titles like `EXPERIENCE`, `SKILLS`, and `EDUCATION` sit on their own lines.

## How it works

Scoring is deterministic and transparent: the posting's repeated keywords (minus filler words) are checked against your text, with common synonyms and acronyms unified (CI/CD and continuous integration, k8s and Kubernetes, and so on). Bullets are ranked by how many of those keywords they hit. No AI is involved, so the same inputs always give the same result, and you can see exactly why anything was ranked where it was.

## License

MIT. Use it, share it, change it.
