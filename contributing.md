# Contributing

Contributions are welcome! Please read the following guidelines before submitting.

## Adding a Feed

1. Make sure the feed is **actually working** — test it in an RSS reader before submitting.
2. Check that the feed is not already listed.
3. Add the feed to the appropriate category in both `README.md` (and `README-en.md`) and `feeds.opml`.
4. Use the following format in the README table:

| Name | Feed URL | Description |
|------|----------|-------------|
| Example Feed | `https://example.com/feed` | Brief description |

5. Keep descriptions concise and objective.

## Adding a Category

If your feed doesn't fit any existing category, you can propose a new one. Please explain why in your PR description.

## General Guidelines

- Search existing entries before adding a new one to avoid duplicates.
- One pull request per feed or small batch of related feeds.
- Keep entries alphabetically sorted within each category when possible.
- Make sure your contribution follows the existing formatting style.
- Write clear, concise commit messages.

## Updating the OPML File

When adding feeds to the README, please also add the corresponding entry to `feeds.opml` so users can import all feeds at once.

## Reporting Issues

If you find a broken feed or have suggestions, please [open an issue](https://github.com/JackyST0/awesome-rsshub-routes/issues).

Thank you for helping make this list more awesome!
