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
  description: {
    cs: "Česky: co to je a proč je to užitečné.",
    en: "English: what it is and why it's useful."
  },
  url: "https://...",
  categories: ["anatomie"],
  profiles: ["student"],
  tags: ["free"],
  added: "2026-08-16"
}
```

**Allowed values:**
- `categories` (keys exactly as used in the code): anatomie, gamifikace, databaze, nastroje, legislativa, komory, spolky, roadmapa, emergency, praxe, open-access, citace, klinika, vyhledavani, prehledy, vzdelavani, jak-na-to, humor
- `profiles`: student, vedec, praktik
- `tags`: free, institutional, freemium, paid

## Fixing a dead link

Issue → use the **"Fix link"** template.

## Ideas

Issue → use the **"Idea"** template. No idea is a bad idea – silence is worse.

## Rules

- Only add resources you've used yourself or verified.
- No pirate links – we stick to legal paths.
- Be kind. We're a community, not a corporation.
