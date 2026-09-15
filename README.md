# JLC Digital Studio Site Infrastructure

Reusable GitHub Actions workflows for JLC Digital Studio websites.

## deploy-static-site.yml

Caller requirements:

- package.json
- package-lock.json
- npm run check
- npm run build
- build output defaults to dist/

The calling repository supplies its own deployment host, user,
path, and SSH credentials.
