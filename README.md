# AR Parallax Video

Static GitHub Pages site for `ar_parallax_loop12s.mp4`.

Published URL:

```text
https://k28511956-debug.github.io/ar-parallax-video/
```

QR code file:

```text
qr-ar-parallax-video.png
```

## Publish

After GitHub authentication is fixed:

```powershell
gh auth login -h github.com
gh repo create ar-parallax-video --public --source . --remote origin --push
gh api -X POST repos/k28511956-debug/ar-parallax-video/pages -f source[branch]=main -f source[path]=/
```

If Pages already exists, enable it from repository settings with branch `main` and folder `/`.
