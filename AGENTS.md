# Repository Guidelines


## 指示
- 本プロジェクトはGitHub Pagesで公開する静的サイトです
- 英語でthinkして日本語でoutputしてください

## Project Structure & Module Organization
This repository is a lightweight static asset collection. The top level contains:
- `image/` for photo assets, organized into named subfolders (e.g., `image/AINU PURI`, `image/CHIMUGURISA`, `image/FUNNIES`).
- `pdf/` for document assets (e.g., `pdf/映画上映会.pdf`).
- `index.html`, currently empty and available for optional static index/preview content.

## Build, Test, and Development Commands
There is no build system or automated tooling in this repo. If you add a simple preview page, you can open it directly:
- `open index.html` to view a local static page in the default browser.

## Coding Style & Naming Conventions
- Keep asset names stable; avoid renaming unless required for organization.
- For new folders, use concise, descriptive names in Title Case to match existing folders (e.g., `image/New Set`).
- For new files, keep original camera/file names unless there is a clear naming standard to follow.

## Testing Guidelines
No automated tests are configured. If you add HTML or scripts, manually verify rendering and file paths in a browser.

## Commit & Pull Request Guidelines
This repository is not currently a Git repository, so there is no commit history or established message format. If you initialize Git, use short, descriptive commit subjects (e.g., `Add CHIMUGURISA images`), and include a brief PR description covering what changed and why.

## Security & Configuration Tips
- Avoid committing secrets or sensitive metadata in assets.
- If sharing publicly, review image metadata (EXIF) before adding new files.

## Agent-Specific Instructions
- Keep the document set small and organized; prefer new content under `image/` or `pdf/`.
- Update `index.html` only if you need a visual catalog or landing page.
