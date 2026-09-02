# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

This is the **official post-event archive** for Cloud Native Valencia (a quarterly CNCF community meetup in Valencia, Spain). It is a static content repository, not a software project — there is no build, lint, or test tooling. The two things that matter are:

- `README.md` — the talks table, which is the source of truth for event/session metadata
- `slides/` — flat directory of speaker slide PDFs, referenced by relative link from the table

## Working conventions

- **New talk submissions**: add a row to the Talks table in `README.md` following the existing column order (`#`, Event date, Title, Speaker(s), Type, Topics, Slides, Video, Code). `#` is a sequential row number, not a stable ID — renumber when inserting rows out of chronological order.
- **Type** is one of `Session`, `Lightning Talk`, or `Workshop`.
- **Topics** must be drawn from the tag list already defined in the "Browse by Topic" section of `README.md` (e.g. `#observability`, `#kubernetes-core`, `#mlops`) — add a new tag to that section if a talk genuinely needs one not yet listed, rather than inventing an ad hoc tag inline.
- **Slide files**: place PDFs directly in `slides/` (no subfolders) and link to them with a relative path from the table's Slides column. Filenames in this repo follow `Title-Case-With-Hyphens_Speaker-Name.pdf` or `Title-Case-With-Hyphens-Speaker-Name.pdf`; match that pattern for new uploads rather than using the file's original download name.
- **Speaker links**: link each speaker's name to their LinkedIn, GitHub, or personal site.
- Video links point to the Cloud Native Valencia YouTube channel once a recording is published; leave the column blank until then.
