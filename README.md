# HTML Learning Notes

A practical collection of HTML examples and notes covering foundational markup, media, forms, performance, and accessibility. Each numbered file focuses on one topic and includes explanatory comments alongside example code.

This repository is intended as a quick reference for learning, revision, interview preparation, and practicing semantic HTML.

## Topics covered

| File | Topic | What it covers |
| --- | --- | --- |
| [`01-doctype.html`](./01-doctype.html) | HTML document structure | `<!DOCTYPE html>`, the `html`, `head`, and `body` elements, metadata, viewport configuration, and deferred scripts |
| [`02-headings.html`](./02-headings.html) | Headings | Heading hierarchy, page structure, and logical nesting with `h1`–`h6` |
| [`03-paragraphs.html`](./03-paragraphs.html) | Paragraphs | Paragraph structure, line breaks, whitespace, and when to use block-level elements |
| [`04-formatting-elements.html`](./04-formatting-elements.html) | Formatting elements | Semantic and presentational text formatting elements such as emphasis, importance, highlighting, and quotations |
| [`05-links.html`](./05-links.html) | Links | Anchors, URLs, fragments, download links, new-tab behavior, and safer external links |
| [`06-images.html`](./06-images.html) | Images | `img`, `src`, `alt`, dimensions, responsive images, and image performance considerations |
| [`07-videos.html`](./07-videos.html) | Video | Video controls, sources, posters, preload behavior, captions, and fallback content |
| [`08-audios.html`](./08-audios.html) | Audio | Audio controls, sources, preload behavior, and accessible fallback content |
| [`09-iframes.html`](./09-iframes.html) | Iframes | Embedded documents, security considerations, sandboxing, permissions, and responsive embeds |
| [`10-link-relations.html`](./10-link-relations.html) | Link relations | Stylesheets, icons, preload, prefetch, preconnect, DNS prefetch, modulepreload, and canonical URLs |
| [`11-javascript-loading.html`](./11-javascript-loading.html) | JavaScript loading | Blocking scripts, `defer`, `async`, modules, modulepreload, and script execution order |
| [`12-critical-rendering-path.html`](./12-critical-rendering-path.html) | Critical rendering path | How HTML, CSS, JavaScript, the DOM, CSSOM, render tree, layout, and paint work together |
| [`13-core-web-vitals.html`](./13-core-web-vitals.html) | Core Web Vitals | LCP, INP, CLS, FCP, TTFB, performance thresholds, and optimization guidance |
| [`14-forms.html`](./14-forms.html) | Forms | Form submission, labels, input types, validation, textareas, selects, and buttons |
| [`15-file-uploads.html`](./15-file-uploads.html) | File uploads | Multipart forms, file inputs, accepted file types, multiple files, and upload-related attributes |
| [`16-table.html`](./16-table.html) | Tables | Captions, table sections, headers, data cells, scopes, summaries, and accessible tabular data |
| [`17-accessibility.html`](./17-accessibility.html) | Accessibility | Semantic HTML, native controls, ARIA attributes, accessible names, keyboard behavior, and the first rule of ARIA |

## Additional resource

- [`HTML MAANG Q&A.pdf`](./HTML%20MAANG%20Q%26A.pdf) — HTML interview questions and answers for revision and interview preparation.

## How to use this repository

### Browse the examples

Open any `.html` file directly in a browser:

1. Clone or download the repository.
2. Open the selected file in a browser, or use **Open with Live Server** in VS Code.
3. Read the inline comments and modify the examples to experiment.

Most files are self-contained learning snippets. Some files are deliberately focused on markup examples rather than complete production pages, so they may be best read as reference material or embedded into a minimal HTML document.

### Clone the repository

```bash
git clone https://github.com/shishir2305/html.git
cd html
```

No package manager, build step, server, or external dependency is required.

## Suggested learning path

1. Start with document structure, headings, paragraphs, formatting, and links.
2. Continue with images, video, audio, and iframes.
3. Study link relations, JavaScript loading, and the critical rendering path.
4. Practice forms, file uploads, and accessible tables.
5. Finish with Core Web Vitals and accessibility to connect markup decisions with real-world performance and usability.
6. Use the Q&A PDF to review interview-focused concepts.

## Learning goals

By working through this collection, you can practice:

- Writing valid, semantic HTML5
- Structuring content with meaningful elements
- Creating accessible forms, tables, and media
- Choosing appropriate loading and resource hints
- Understanding browser rendering and script execution
- Improving loading performance and responsiveness
- Applying native HTML before reaching for ARIA
- Preparing for HTML-focused technical interviews

## Contributing

Contributions are welcome. Keep new examples focused on one HTML concept, use semantic markup, and add explanatory comments where they improve understanding. If you add a new lesson, follow the existing numbered naming convention and update the topics table in this README.

## License

No license is currently specified for this repository. Add a license before distributing or reusing the contents in other projects.
