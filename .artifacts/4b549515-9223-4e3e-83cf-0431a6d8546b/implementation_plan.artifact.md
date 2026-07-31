# Implementation Plan - SEO Optimization for S²olstice Studio

This plan detail the steps to optimize the SEO for the entire website `ssolstice.dev`. The goal is to ensure each page has a unique and descriptive set of meta tags, correct canonical links, and relevant structured data.

## User Review Required

> [!IMPORTANT]
> **Domain Standardization**: All canonical links and Open Graph URLs will be set to `https://ssolstice.dev/`. Please confirm if there are any other subdomains or mirrors that should be considered.

> [!NOTE]
> **Keywords Strategy**: I have selected general keywords like "Android Camera App", "Manual Camera", "Pro Photography", and app-specific keywords. If you have a specific target keyword list, please provide it.

## Proposed Changes

### 1. Global Metadata & Technical SEO

#### [MODIFY] [sitemap.xml](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/sitemap.xml)
- Add missing pages: `privacy.html`, `terms.html`, `jsonviewer.html`, `happyblocks.html`, `camera-privacy.html`.
- Update `lastmod` to current date.

#### [MODIFY] [index.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/index.html)
- Add `<meta name="description" content="Independent studio building professional Android camera apps, productivity tools, and creative utilities. Home of AuraRAW, Manual 2, and Fieldly.">`.
- Add `<meta name="keywords" content="Android Camera App, Manual Camera, Pro Photography, RAW Capture, GPS Camera, Field Documentation, S2olstice Studio">`.
- Add Twitter Card tags.
- Improve `og:site_name` to "S²olstice Studio".

### 2. App Landing Pages Optimization
Adding `SoftwareApplication` schema and complete meta tags to app pages.

#### [MODIFY] [fieldly.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/fieldly.html)
- Add meta description, keywords, canonical, OG tags, and Twitter tags.
- Add `SoftwareApplication` JSON-LD schema.
- Add `alt` attributes to images currently using data URIs or missing them.

#### [MODIFY] [manual2.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/manual2.html)
- Add canonical, keywords, OG tags, and Twitter tags.
- Add `SoftwareApplication` JSON-LD schema.

#### [MODIFY] [auraraw.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/auraraw.html)
- Add canonical, keywords, OG tags, and Twitter tags.
- Add `SoftwareApplication` JSON-LD schema.

#### [MODIFY] [aurapro.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/aurapro.html)
- Add canonical, keywords, OG tags, and Twitter tags.
- Add `SoftwareApplication` JSON-LD schema.

### 3. Utilities & Game Pages

#### [MODIFY] [jsonviewer.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/jsonviewer.html)
- Update title to "JSON Viewer & Editor | S²olstice Tools".
- Add meta description, keywords, canonical, and OG tags.

#### [MODIFY] [happyblocks.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/happyblocks.html)
- Add meta description, keywords, canonical, and OG tags.

### 4. Info & Legal Pages

#### [MODIFY] [about.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/about.html)
- Add canonical, keywords, OG tags, and Twitter tags.

#### [MODIFY] [privacy.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/privacy.html) / [terms.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/terms.html) / [help.html](file:///Users/phung/Documents/Workspace/google-play/ssolstice216.github.io/help.html)
- Add canonical and OG tags.

## Verification Plan

### Automated Tests
- Check for the existence of `<title>`, `<meta name="description">`, `<link rel="canonical">`, and `og:title` on all HTML files.
- Validate `sitemap.xml` structure.

### Manual Verification
- Review the generated `sitemap.xml` to ensure all URLs are correct.
- Inspect the `<head>` section of each modified page.
