# Recomps

The collection site for ol.mr game recompilation projects. Each game remains in
its own repository and deployment; this site is the lightweight directory that
links them together.

## Local preview

```sh
python3 -m http.server 8080
```

## Deploy

```sh
npx wrangler pages deploy . --project-name recomps --branch main
```

