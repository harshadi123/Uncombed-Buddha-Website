# Uncombed Buddha

The company website. Plain HTML, CSS and JavaScript — no build step, no dependencies.

## Editing

| What you want to change | File |
|---|---|
| Homepage text, quotes, team, contact | `index.html` |
| A film's page | `films/<name>.html` |
| Full film list | `films.html` |
| Songs | `music.html` |
| Colours, type, spacing, anything visual | `assets/style.css` |
| Photographs, logos, fonts, video | `assets/img`, `assets/font`, `assets/video` |

Edit a file on GitHub with the pencil icon, commit, and the site redeploys in about a minute.

## Hero quotes

In `index.html`, search for `hero-quotes`. Each line is a `<span class="hq">`; the part in
`<em class="accent">` is the oblique half. Add or remove spans freely — the rotation adapts.

## Festival logos

In `index.html`, search for `fest-track`. Each festival appears **twice** — the strip is
duplicated so the scroll loops seamlessly. Change both copies.

Logos with a light and dark version use `fl-dark` and `fl-light`; a script swaps them by theme.
