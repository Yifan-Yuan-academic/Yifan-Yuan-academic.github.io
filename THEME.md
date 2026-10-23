# Academic homepage theme

The active homepage, publications index, and publication detail layout use
[Minimal Light](https://github.com/yaoyao-liu/minimal-light) by Yaoyao Liu.

Upstream snapshot: `dd114c3fef2d97adc1c6b6d46901e0d96ab83a7c`.
License: CC0 1.0 Universal; see `LICENSE-Minimal-Light`.
The original repository LICENSE is retained for the pre-existing code.

The light-mode Sass, sans-serif font stylesheet, and publication stylesheet
are copied from upstream. The homepage layout is adapted only to use this
repository's existing content and absolute/relative Jekyll URLs, provide
accessible navigation, retain the portrait's natural proportions, and render
the existing `_publications` collection. Unneeded tracking, placeholder social
links, favicon script, and the legacy mobile zoom-lock script are not used.

The small `assets/css/profile-adapter.css` handles the existing portrait,
publication metadata and keyboard focus. It does not replace the theme's
typography, colours or two-column layout.

## Editing content

- Biography, education and news: `_pages/about.md`
- Identity and contact information: `_config.yml`
- Existing paper metadata and abstracts: `_publications/`
- Portrait: `images/human.png` (retained unchanged)
- Publication index: `_pages/publications.html`

All existing publication sources, PDFs, images, and their URLs are retained.
The previous custom navy/gold card stylesheet has been removed.

A backup branch, `backup/pre-minimal-light-20261023`, records the site before
this migration.
