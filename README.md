# do you hate me?

A small, cozy, slightly silly one-page website. It asks "do you hate me?" and offers lots of ways to say yes, plus a "No" button that runs away from your cursor and from your finger.

- Any answer except "No" gets a dramatic "wowwww… i knew it."
- The "No" button can't be clicked or tapped. If someone reaches it with the keyboard (or a screen reader), it counts, and the bear is pleasantly surprised.
- Works on desktop and mobile, with a light and a dark look, and it respects reduced-motion settings.

## Files

- `index.html` is the whole site (HTML, CSS and JavaScript in one file). It loads one Google Font (Fredoka) and falls back to a rounded system font if that's blocked.

## Publish with GitHub Pages

1. Create a new repository and upload `index.html` (and this README) to the top level.
2. Go to Settings > Pages, choose "Deploy from a branch", pick your branch and the `/ (root)` folder, and save.
3. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Tweaking

- **Answer buttons:** add or remove `<button class="opt">…</button>` lines in `index.html`, and add a matching line for each in the `details` list in the script to change what the page says after that answer.
- **Dodge sensitivity:** in the script, change the `95` (mouse) and `60` (touch) numbers near the bottom, which are how close in pixels the pointer can get before the button jumps.
- **Funny lines:** the `quips` list holds what the speech bubble says while someone chases "No".
