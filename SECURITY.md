# Security policy

This tap tells Homebrew what to install: a formula names a download and its SHA-256. A changed formula would change what lands on someone's computer, so reports about this repository are very welcome.

## Supported versions

Only the formulas on `main` (the newest release of each product). Updating is the fix: `brew update && brew upgrade`.

## Reporting a problem

Please **don't** open a public issue, discussion or pull request for a security problem.

1. Go to the **Security** tab of this repository and click **[Report a vulnerability](https://github.com/Phygital-Key/homebrew-tap/security/advisories/new)**. Only the maintainers see it.
2. Say which formula and version, and what you saw.
3. Never send real tokens, keys or private data.

Problems in a product itself go to its repository: [Phygital Key MCP](https://github.com/Phygital-Key/phygital-key-mcp/security/advisories/new), [Phygital Key A2A](https://github.com/Phygital-Key/phygital-key-a2a/security/advisories/new) or the shared base [Phygital Key](https://github.com/Phygital-Key/phygital-key/security/advisories/new).

## What happens next

| When | What |
|---|---|
| Within 3 days | A first answer saying the report arrived |
| Within 10 days | The problem is confirmed (or explained), with a plan |
| Usually within 30 days | A fix is published |

Please keep the problem private until the fix is out, or for 90 days, whichever comes first.

## In scope

- A formula that points to a download that is not the product's official release.
- A wrong or missing SHA-256, or a download that skips the check.
- A way to change a formula that bypasses review, or a release tag that was moved.
- A formula that runs more than it needs to at install time.

## Out of scope

- Problems in Homebrew itself (report them to Homebrew).
- Problems in the products. Use their repositories.

## Keeping your own setup safe

- Install with `brew install phygital-key/tap/<formula>` and keep Homebrew updated.
- Brew checks the SHA-256 for you. If it ever reports a mismatch, stop and report it here.
