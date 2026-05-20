# CLAUDE.md - La Trappeza Web Project

This file contains guides, commands, and standards for development in the La Trappeza project, specifically designed for Claude Code.

## Development & Build Commands
Since this is a static single-page web project using Tailwind CSS Play CDN:
*   **Run Local Dev Server:** `python -m http.server 3000` (Opens page at `http://localhost:3000/index.html`)
*   **Deploy / Update Web:** `git add .`, `git commit -m "Update message"`, `git push` (Triggers Vercel auto-deployment)

## Code Style & Standards
*   **Architecture:** Single-page static site. The primary entrypoint is `index.html`.
*   **Styling:** Primarily Tailwind CSS utility classes loaded via `https://cdn.tailwindcss.com` play CDN. Avoid adding heavy vanilla CSS unless custom animations/custom fonts require it.
*   **Icons:** Google Material Symbols (`Material Symbols Outlined`).
*   **Format:** HTML5 semantic layout. Keep Tailwind class strings ordered logically where possible. Keep scripts clean and placed at the bottom of the body or deferred.
