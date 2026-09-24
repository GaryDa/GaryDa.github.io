# GaryDevMurmur

Source for https://garyda.github.io/, built with [Hugo](https://gohugo.io/) and the
[hugo-theme-tailwind](https://github.com/tomowang/hugo-theme-tailwind) theme (loaded as a Hugo module).

## Local preview

Requires Hugo (extended) and Go.

```bash
hugo server
```

## New post

```bash
hugo new content post/my-post.md
```

Remove `draft = true` from the front matter when it's ready to publish.

## Deploy

Pushing to `main` runs `.github/workflows/hugo.yml`, which builds the site and deploys it to
GitHub Pages (Settings → Pages → Source must be "GitHub Actions").
