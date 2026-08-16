# Contributing to VETCompASS

Thanks for helping out! 🐾

## Adding a new resource

1. Open an **Issue** → use the **"New source"** template and fill it in,
2. or submit a **Pull request**: add an object to the `SOURCES` array in `index.html`.

### Source format

```js
{
  id: "name-without-diacritics",
  name: "Display name",
  description: "1–2 sentences: what it is and why it's useful.",
  url: "https://...",
  categories: ["anatomy"],
  profiles: ["student"],
  tags: ["free"],
  platform: "web",
  language: "EN",
  added: "2026-08-16"
}
