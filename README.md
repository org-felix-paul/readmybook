# ReadMyBook

A static presentation page for **ReadMyBook**, an AI-based Android app that
reads a children's book aloud.

The app was developed as a complement to a children's book by a private friend,
so that children — especially those with busy parents — could independently have
a book read to them by scanning a page. Page recognition used the text
recognition of Android's ML Kit; three reading modes were available (the
author's recording, the parents' own recording, and the author's recording with
audio description). Button designs and graphics were created by Klarissa Okfen.

**The project has been discontinued.** This repository contains only the
presentation website, not the app's source code.

## Contents

```
index.html     the page
styles.css     styles (no framework, no build step)
favicon.svg    favicon
img/           images
```

## Preview locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## License

MIT — see [LICENSE](LICENSE).
