# Code[Mark] Support

Need help, found a bug, or have an idea? Open an issue at
**<https://github.com/miguelriotinto/codemark-app/issues/new>**. Include your device, its iOS / iPadOS / macOS version,
and the steps that lead to the problem; attaching the Markdown file (or a small
sample that shows the problem) helps most.

## Common questions

**How do I open a file?**
Tap it in Code[Mark]'s browser (Recents, Shared, Browse), or in the Files app choose
*Share › Code[Mark]* / *Open With*. On Mac, double-click a `.md` file or use
*File › Open*. Files open where they are — nothing is imported or copied.

**Will Code[Mark] reformat my file?**
No. Only the text you change is rewritten. Line endings, indentation, list markers,
front matter, comments and reference definitions stay exactly as they were. Opening
a file, switching to Source and back, or exporting a PDF never changes it at all.

**Where do pasted images go?**
Into the Markdown file itself, so it stays a single file you can move or send. Very
large images (over 10 MB) can't be embedded. Some other Markdown viewers, including
GitHub, don't display images stored this way.

**Images next to my document don't show on iPhone or iPad.**
iOS lets an app read only the file you opened. Tap **Allow Access to Folder…** on the
missing image and choose the document's folder once; Code[Mark] remembers it.

**Another app changed the file while I was editing.**
If you had no unsaved edits, Code[Mark] shows the new version. If you did, a bar
offers *Keep Other Version*, *Keep My Version* or *Save Mine As…*; until you choose,
nothing is written and both versions are kept.

**How do I see the Markdown source?**
Tap the `</>` button (or press ⌥⌘U). Tap it again to return to the same place.

**How do I export a PDF?**
On iPhone and iPad, tap the share button › *Export as PDF*. On Mac, *File › Export
as PDF…*.

**Which Markdown features are supported?**
CommonMark and GitHub Flavored Markdown (tables, task lists, strikethrough,
autolinks, footnotes, alerts), Mermaid diagrams and math (`$…$`, `$$…$$`). Anything
else is kept as written and shown as source.

## Privacy

Code[Mark] collects no data. See [PRIVACY.md](PRIVACY.md).
