# issue with prettier-eslint (probably flat config related)

## What I did

Running `pnpm dlx prettier-eslint-cli index.js --write`

## Expected output

The same thing as `pnpm exec eslint index.js --fix` - adding braces around the statement

## Actual output

Nothing changes

When I set `log-level` to debug, it says "unable to find config" which might be related to the issue
