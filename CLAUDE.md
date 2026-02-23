# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This repo is used to generate single-file HTML slide presentation from source notes.

You will be creating a complete HTML presentation with CSS styling and JavaScript functionality. The presentation should be optimized for recording, with minimal text and maximum visual impact.

Your task is to create a single HTML file that contains a complete slide presentation based on provided content. 

Your final output should be a complete, functional HTML file with embedded CSS and JavaScript. The file should be ready to open in a browser. 


## Key Files

- **input.md** — Raw source text: author's thoughts, motivation, unstructured notes.
- **structure.md** — Polished, presentation-ready phrases organized by chapters/slides. Generated from `input.md`.
- **requirements/content.md** — Prompt template describing how to transform text from `input.md` into polished phrases for `structure.md`.
- **requirements/technical.md** — Prompt template describing how to generate the final HTML presentation with the `frontend-design` skill.

## Workflow

1. Author writes raw thoughts and notes into `input.md`
2. Follow `requirements/content.md` to process `input.md`: refine, structure, and turn into polished phrases → save to `structure.md`
3. Follow `requirements/technical.md` to generate the final HTML presentation from `structure.md` using the `frontend-design` skill
4. Output is a single `.html` file with embedded CSS and JS, placed in the `build/` folder
