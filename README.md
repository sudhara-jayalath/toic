# the ordinary inquiry club (TOIC)

Website of **the ordinary inquiry club**, a street philosophy table in Hamburg St. Pauli.
Thursdays, 18:00–20:00. One question, up to eight people, your own theory.

Live site: https://sudhara-jayalath.github.io/toic/

## What's here

- `index.html` – the whole site in one file (Club, Records, Chamber, Letter, About me).
- `og.png` – preview image shown when the link is shared.
- `favicon.png` – browser tab icon.

## Updating the content

All content lives in one JSON block near the end of `index.html`:

```html
<script type="application/json" id="toic-data"> ... </script>
```

It holds `settings` (Meetup and newsletter links), `sessions` (the minute-book),
`members` (Chamber of Members), `letters` (the Thursday Letter) and `founder` (About me).
Edit it on GitHub (pencil icon), keep the JSON valid, and commit. The site updates within a minute or two.
