# distilled-spec-github

A git mirror of Github's API spec. The spec is fetched and committed as a JSON file so the repo serves as a versioned snapshot.

The mirror is updated every 24 hours and is designed to be used as a stable git submodule.

## Spec source(s)

- https://raw.githubusercontent.com/github/rest-api-description/refs/heads/main/descriptions-next/api.github.com/api.github.com.2026-03-10.json

## Usage as a submodule

```sh
git submodule add https://github.com/ukstv/distilled-spec-github.git
```

## Updating specs

From `.meta/`:

```sh
bun install
bun run fetch-specs
```
