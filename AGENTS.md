<!-- Repository Guidelines -->
# Repository Guidelines

Welcome to the **LLM Pricing Calculator** repository. This guide covers structure, conventions, and workflows for contributors.

## Project Structure & Modules

- `index.html`: Main static SPA with embedded CSS/JS.
- `404.html`, `_redirects`, `favicon.png`: Site assets and routing.
- No `src/` folder—single-file entry point for simplicity.

## Development & Preview

- Open `index.html` directly in a browser for local preview.
- (Optional) Run `npx http-server` to serve files over HTTP.

## Coding Style & Naming

- Indentation: 4 spaces.
- Keep all CSS in the top `<style>` block; no stray styles below `</style>`.
- Use clear, descriptive IDs (e.g., `inputTokens`, `addTurnBtn`).
- JS functions use camelCase (e.g., `calculateCost`, `resetAll`).

## Testing & QA

- No automated tests; perform manual testing:
  - Verify token formatting and placeholders.
  - Check per-turn cost calculations.
  - Test reset and filtering functionality.

## Commit & Pull Requests

- Commit messages: `<type>: <short description>` (e.g., `feat: add remove-turn feature`).

## Contributing Tips

- Group feature logic and styling together in `index.html`.
- Refactor repetitious code blocks into helper functions where appropriate.
- Update this guide when adding new workflows or dependencies.

Thank you for improving the project! Open issues or PRs for questions and enhancements.
