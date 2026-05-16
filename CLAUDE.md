## gstack (REQUIRED — global install)

**Before doing ANY work, verify gstack is installed:**

```bash
test -d ~/.claude/skills/gstack/bin && echo "GSTACK_OK" || echo "GSTACK_MISSING"
```

If GSTACK_MISSING: STOP. Do not proceed. Tell the user:

> gstack is required for all AI-assisted work in this repo.
> Install it:
> ```bash
> git clone --depth 1 https://github.com/garrytan/gstack.git ~/.claude/skills/gstack
> cd ~/.claude/skills/gstack && ./setup --team
> ```
> Then restart your AI coding tool.

Do not skip skills, ignore gstack errors, or work around missing gstack.

Using gstack skills: After install, skills like /qa, /ship, /review, /investigate,
and /browse are available. Use /browse for all web browsing.
Use ~/.claude/skills/gstack/... for gstack file paths (the global path).

## Document generation — high-quality template style (REQUIRED)

All documents generated in this repo (memos, proposals, decks, reports)
must follow a high-quality executive-template style, modeled on the MELIC
May 15, 2026 executive memo and the Sequoia deal-memo format:

- **Title block**: centered title in dark blue (#1F3864, ~26pt bold), then
  a centered subtitle (~15pt, dark blue, semibold).
- **Metadata block**: left-aligned, ~10pt, with bold dark-blue labels
  (`To:`, `From:`, `Date:`, `Subject:`, etc.) followed by the value.
- **Section headers**: numbered, ~15pt, dark blue, bold, with a thin
  light-grey bottom border. Subsections at ~12pt, dark blue, bold.
- **Body**: Calibri (or system equivalent) ~11pt, line-height ~1.45,
  black on white.
- **Tables**: dark-blue header row (#1F3864) with white bold text;
  alternating row backgrounds (#F4F7FB on every other row); thin
  light-grey row separators; top-aligned cells.
- **Callouts / sidebars**: light-blue background (#EAF1F8) with a 4pt
  dark-blue left border, used sparingly for key framing or summary lines.
- **Footer**: small italic grey line, centered, with author + draft
  version + date.

When generating docs for upload to Google Drive, build a `.docx` (via
python-docx) rather than relying on plain-text or markdown conversion —
Drive auto-converts `.docx` to a properly styled Google Doc, preserving
the template. Keep a `.md` source-of-truth in the repo for diffing and a
`.docx` (and optionally `.html`) for distribution.

Never deliver a polished-content document as a raw markdown render to an
executive audience — always produce the styled `.docx` first.
