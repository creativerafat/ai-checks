# main — VANTA — SS26 Atelier — DesignKoro Export (CSS Stylesheet)

Generated from frame **main — VANTA — SS26 Atelier** in DesignKoro project `file-1793804223377` on `2026-11-25T12:49:09.684Z`.

## 1. What Was Generated
- **Section Name**: main — VANTA — SS26 Atelier
- **Source Frame**: main — VANTA — SS26 Atelier
- **Output Bundle**: CSS Stylesheet (3 files)
- **Assets Referenced**: 10 asset(s) mapped to `assets/` and documented in `assets.json`

## 2. File Tree
```text
main-vanta-ss26-atelier/
├── styles/section.css (49.8 KB)
├── styles/tokens.css (4.5 KB)
├── assets.json (4.6 KB)
```

## 3. How to Open or Import Each File
- **`index.html` / `styles/section.css`**: Open `index.html` directly in a browser or import `styles/section.css` into your web application.
- **`components/MainVantaSs26Atelier.tsx` & `components/MainVantaSs26Atelier.module.css`**: Import `MainVantaSs26Atelier` into any React + TypeScript page. Props are strongly typed with JSDoc descriptions.
- **`tailwind.config.js`**: Merge the `theme.extend` block into your Tailwind configuration.
- **`tokens.json`**: Load into Style Dictionary, CSS variable generators, or design system documentation.
- **`assets.json`**: Inspect the manifest of all images and icons (`name`, `originalSize`, and `exportedPath` inside `assets/`).

## 4. Fonts to Load
This design uses the following font families: **Inter, JetBrains Mono, Plus Jakarta Sans, Bricolage Grotesque**.
Add this Google Fonts `<link>` tag inside your `<head>`:
```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=JetBrains%20Mono:wght@400;500;600;700&family=Plus%20Jakarta%20Sans:wght@400;500;600;700&display=swap" />
```

## 5. Known Limits
- Absolute positioning is reserved strictly for explicit overlays (**18** element(s)); all primary layouts use responsive flex/grid flow.
- Mobile-first responsive breakpoints are emitted for Tablet (`@media (min-width: 768px)`) and Desktop (`@media (min-width: 1024px)`).

## 6. Export and Publishing
- **Export Outputs**: DesignKoro generates 5 developer-ready bundles (`HTML + CSS`, `React + CSS Modules`, `Tailwind`, `CSS Stylesheet`, and `Design Tokens JSON`). Every bundle can be previewed in the Section Code file explorer, copied per-file or all at once, exported as a `.zip` archive with folder paths preserved, or copied as Gist-ready Markdown.
- **GitHub Push Flow**: Publishing uses the GitHub Git Data API (`blobs` -> `trees` -> `commits` -> `refs`) to commit all files in the selected scope atomically in a single commit. Before creating the commit, DesignKoro verifies that the target branch `HEAD` SHA has not moved since the change preview was built, preventing accidental overwrites without ever force-pushing.
- **Token Handling**: Your GitHub Personal Access Token or OAuth token is stored only in the backend session memory (`/api/github/*`) and is never persisted in plain-text browser `localStorage`.