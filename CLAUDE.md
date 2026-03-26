# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## About

This repository contains the meeting minutes of the Django Software Foundation (DSF) Board. It is a documentation-only repo with no build system, tests, or dependencies.

## Structure

- `YYYY/template.md` — Year-specific template pre-filled with that year's board members and attendees
- `YYYY/YYYY-MM-DD.md` — Individual meeting minutes, named by meeting date

## Adding New Minutes

1. Copy the current year's template (e.g., `2026/template.md`) to a new file named `YYYY-MM-DD.md` in the same directory
2. Fill in the placeholders: date, meeting leader, attendance, apologies, finance balance, grants, members, business items, and action items
3. Remove any template sections that don't apply (e.g., "Corporate members approved" if none were approved)

## Adding a New Year

1. Create a new directory for the year (e.g., `2027/`)
2. Copy and update the previous year's template, adjusting board member names and default attendees for the new term

## Conventions

- Filenames use the meeting date: `YYYY-MM-DD.md`
- Minutes follow a consistent markdown structure with H1 title, H2 sections (Finance, Grants approved, Individual/Corporate members approved, Ongoing business, New business, Action items), and H3 subsections
- Confidential discussions are noted with: "Discussions under this section are confidential and have been omitted from the public minutes for this month."
- The 2026+ template includes an "Apologies" field
- All minutes files must start with empty YAML front matter (`---\n---`) for Jekyll processing
