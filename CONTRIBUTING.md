# Contributing

Thank you for your interest in improving The Grand Diwali Celebration.

## Before you start

- Check existing issues and pull requests to avoid duplicate work.
- For larger changes, open an issue to discuss the proposed approach.
- Keep changes focused and explain the user-facing benefit.

## Local setup

1. Clone or download the repository.
2. Open a terminal in the folder containing `index.html`.
3. Run `python -m http.server 8000` (or `python3 -m http.server 8000`).
4. Open `http://localhost:8000`.

The current version is a single-file static project and has no npm build step.

## Pull request process

1. Fork the repository.
2. Create a descriptive branch, for example `fix/mobile-camera-controls`.
3. Make your changes.
4. Test the relevant interactions on desktop and mobile where possible.
5. Open a pull request with:
   - A concise summary.
   - The reason for the change.
   - Steps used to test it.
   - Screenshots or a recording for visual changes.

## Quality expectations

- Avoid adding secrets, API keys, or personal data.
- Do not add third-party media unless its usage rights are clear.
- Keep the experience usable on touch devices.
- Respect browser autoplay restrictions.
- Mention known limitations honestly.
