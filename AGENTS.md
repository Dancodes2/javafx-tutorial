# Project instructions

## Scope

- Follow the SE-EDU Java coding standard (basic + intermediate) and Git conventions:
  - https://se-education.org/guides/conventions/java/intermediate.html
  - https://se-education.org/guides/conventions/git.html
- Follow the JavaFX tutorial's prescribed Gradle/dependency approach closely.
- Preserve the CLI/core logic and the `bye` command while adding the GUI.
- Keep learning notes local; do not commit them.

## Java conventions

- Use PascalCase for classes, camelCase for variables/methods, and SCREAMING_SNAKE_CASE for constants.
- Use four-space indentation, K&R braces, explicit imports, and lines no longer than 120 characters.
- Keep variables in the smallest useful scope and avoid public mutable fields.
- Put descriptive Javadoc on public classes and public methods; overridden methods may rely on inherited documentation.
- Use braces for all loop and conditional bodies.
- Keep code and comments in clear English.
- For this tutorial, preserve the starter repository's existing package structure unless a tutorial step explicitly requires changing it; do not introduce an unrelated package migration.

## Git conventions

- Make focused commits at logical milestones; do not mix unrelated changes.
- Commit subjects use imperative mood, start with a capital letter, have no final period, and stay within 72 characters (prefer 50).
- Non-trivial commits include a body describing what changed and why, wrapped at 72 characters.
- Add tutorial tags after each completed part: `Tutorial-Part1`, `Tutorial-Part2`, etc.
- Do not push unless the user explicitly asks; the user normally pushes commits and tags.

## Verification

- Run the relevant Gradle build/tests and a minimal smoke test after changes.
- Report commands, results, warnings, assumptions, and anything not verified.
- Before committing, inspect the staged file list and diff to ensure the commit contains only its intended milestone.
