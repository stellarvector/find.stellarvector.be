# find.stellarvector.be

This is the link-tree for Stellar Vector.

## Pull the latest hugo modules (theme)

```bash
hugo mod get -u
```

Commit changes to `go.mod` and `go.sum` in your next PR.

## Development

From the root directory, run:

```bash
hugo server -D --disableFastRender
```

The site is available on port 1313.

Tailwind runs as an external binary from the Hugo pipeline, so `npm install` must have
been run at least once and `security.exec.allow` in `hugo.yml` must list `tailwindcss`.