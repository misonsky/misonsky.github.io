Personal Website: https://misonsky.github.io/

## Deploy

This site is a Jekyll-based GitHub Pages homepage.

### Local preview

```bash
bundle install
bundle exec jekyll serve
```

### GitHub Pages

1. Create a GitHub repository named `misonsky.github.io` for a user homepage, or use any repo name for a project homepage.
2. Push this folder to the repository and make sure the default branch is `main`.
3. In GitHub, open `Settings -> Pages`, set `Source` to `GitHub Actions`.
4. Push to `main`; `.github/workflows/deploy.yml` will build and publish the site automatically.

If you use a project homepage such as `username.github.io/repo-name`, update `baseurl` in `_config.yml` to `/repo-name`.
