## Project

Mosaic Minds — recreation of the live landing page at https://lp.mmaz.com/ for a
neurodivergent-affirming teen mental health program in Chandler, AZ. Built with
Astro 7 + Tailwind 4, following the same conventions as sibling elev8 projects
(Buena Vista Recovery, Plugged In Recovery): one component per section,
`public/Asset/<Category>/` for real downloaded assets, `Creolia` for display
headings and `Outfit` for body text.

Source material lives in `.research/` (gitignored): the live page's downloaded
assets, sliced renders of the two client-approved Figma PDF exports (desktop
"Mental Health" layer + "Mobile" layer), and notes. Do not change any copy —
all text is client-approved; it was extracted verbatim from the live site and
cross-checked against the Figma PDFs.

## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
