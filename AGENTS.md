# Architecture decisions

- Keep Netlify build and publish settings in the repository-root `netlify.toml`, because Netlify does not read deployment configuration from `public/`.
