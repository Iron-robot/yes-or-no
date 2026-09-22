# will-you-go-on-a-date-with-me

A cute, single-file, self-contained "will you go on a date with me" website. No build step, no dependencies, no backend — just one `index.html` you can open locally or host anywhere for free.

## Live demo

Once you enable GitHub Pages (see below), your link will look like:

```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

## Features

- A dodging, shrinking "no" button next to a pulsing "yes" button
- A playful reaction screen after she says yes
- A real date picker plus a time dropdown with a joke on every option
- A 6-option food picker (pizza, sushi, burgers, pasta, tacos, ramen)
- A sweet closing note that fills in her actual answers
- Auto-opens a pre-filled text message to a phone number of your choice (browsers require the final "send" tap themselves — no site can send it for you)
- Small synthesized sound effects (pop, chime, boing) via the Web Audio API — no audio files needed
- Works on mobile: 16px+ inputs (no iOS auto-zoom), large touch targets, safe-area padding for notches
- Zero dependencies except two Google Fonts

## Setup

1. Open `index.html` in a text editor.
2. Find this line near the bottom of the `<script>` section:
   ```js
   var phoneNumber = '+12168946335';
   ```
   Replace it with your own number in `+1XXXXXXXXXX` format.
3. Optionally edit the headline text, food options, or colors (see the `:root` CSS variables near the top of the file).

## Host it for free

**Option A — GitHub Pages (recommended)**
1. Push this repo to GitHub.
2. Go to Settings → Pages.
3. Under "Source," choose the `main` branch and `/ (root)` folder, then save.
4. GitHub gives you a public link in a minute or two.

**Option B — just send the file**
Text, AirDrop, or email `index.html` directly. Any phone or computer can open it in a browser — no hosting needed at all.

## License

MIT — see [LICENSE](./LICENSE). Do whatever you want with it.
