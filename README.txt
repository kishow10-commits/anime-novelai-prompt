Anime -> NovelAI prompt builder (iPhone / Cloudflare Pages)
Updated: 2026-11-22

New:
- Random selection from currently filtered characters, with one-tap copy and reroll.
- Common Japanese abbreviated anime-title search; resolves popular nicknames to searchable titles.

Deploy:
1. Open Cloudflare dashboard > Workers & Pages.
2. Select a Pages direct-upload project, or create one.
3. Upload this ZIP (or the index.html file).
4. After deploying, open the *.pages.dev URL in Safari.

The app uses AniList's public GraphQL endpoint. An internet connection is required.
Shortname matching is based on a built-in dictionary; not every abbreviation is supported.
