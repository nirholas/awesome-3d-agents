# Contributing

This repository is a published mirror. `readme.md` is generated, so an edit made here is overwritten by the next build.

## Add an entry

Open a pull request against [`data/awesome.json`](https://github.com/nirholas/three.ws/blob/main/data/awesome.json) in the source repository. Add an object to the section it belongs in:

```json
{
  "name": "glTF-Transform",
  "url": "https://github.com/donmccurdy/glTF-Transform",
  "description": "Read, edit, optimise, and validate glTF from Node or the CLI.",
  "tags": ["oss", "js", "cli"]
}
```

## What gets in

The bar is "a working engineer would be glad someone showed them this".

- **It has to be usable now.** A repo with no release, no docs, and no commits in two years is a bookmark, not a recommendation.
- **It has to earn its section.** If a new entry beats an existing one at the same job, say so in the description, or replace the old one.
- **One sentence, under 260 characters**, starting with a capital and ending with a period. The build fails otherwise, and so does `awesome-lint`.
- **No em-dash (U+2014) or en-dash (U+2013).** Use a period, a comma, a colon, or parentheses. A plain hyphen is fine.
- **No marketing copy.** "Blazing fast next-generation platform" tells a reader nothing. "Single image to 3D in under a second on one GPU" does.
- **Working links only.** Every url is fetched and classified as ok, moved, bot-filtered, or broken before a change ships. A broken url fails the run.

## Code of conduct

By participating you agree to the [code of conduct](code-of-conduct.md).
